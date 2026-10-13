Date of Incident - April 19 , 2026
Tags-[supply chain attack, -OAuth permissions escalations ]

# Summary


In April 2026 , Vercel suffered a security incident originating from a supply chain attack via the third-party AI tool Context.ai .
The incident originated with a compromise of Context.ai, a third-party AI tool used by a Vercel employee. The attacker used that access to take over the employee's individual Vercel Google Workspace account, which enabled them to gain access to that employee’s Vercel account. From there, they were able to pivot into a Vercel environment, and subsequently maneuvered through systems to enumerate and decrypt non-sensitive environment variables.

Vercel  assessed the attacker as highly sophisticated based on their operational velocity and in-depth understanding of Vercel's product API surface.

# Dwell Time

**Initial Infection**

February 2026
The attack vector began when a Context.ai employee's device was infected with Lumma Stealer malware. This infostealer harvested OAuth session tokens and credentials.

**The Quiet Period**

 The attackers maintained access undetected for roughly two months, using the stolen tokens to bypass multi-factor authentication (MFA) and pivot through the Vercel employee's enterprise Google Workspace into Vercel’s internal systems.

**Discovery & Public Disclosure**

April 19 2026
The dwell time finally ended when the group ShinyHunters publicly listed the exfiltrated data for sale on BreachForums for $2 million, forcing immediate discovery and mitigation.

# Technical Failure 

**1.Broad Auth Scopes and "Standing Access"**

A Vercel employee authorized the third-party productivity application, Context.ai, using "Login with Google". The integration relied on an "Allow All" permissions dialog that granted overbroad, full read/write access to the corporate Google Workspace environment (such as Google Drive). This meant that once the third-party app was compromised upstream via infostealer malware, the attackers inherited these extensive permissions seamlessly.

**2.Lack of Token Binding and Proof Key for Code Exchange (PKCE)**

 The integration lacked token binding or Proof Key for Code Exchange (PKCE) controls. Because the OAuth architecture did not bind the generated session or refresh tokens to a specific physical device or IP address, the attackers were able to steal the refresh tokens out of Context.ai's backend database and replay them from their own servers. They bypassed multi-factor authentication (MFA) entirely because the OAuth token established a "trusted path," allowing them to blend into normal corporate traffic undetected

**3.Plaintext Default for Environment Variables**

Once inside Vercel's internal environments, the attackers were able to mass-enumerate customer configuration files. A major architecture gap on Vercel's platform at the time was the "plaintext default" for standard environment variables. While variables explicitly marked as "sensitive" were strongly encrypted at rest, many developers used standard environment variables as a catch-all repository for database credentials, third-party secrets, and API keys. These unencrypted keys were easily harvested in bulk.





















 

