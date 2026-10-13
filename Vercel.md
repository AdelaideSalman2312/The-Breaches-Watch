Date of Incident - April 19 , 2026
Tags-[supply chain attack, -OAuth permissions escalations ]

**Summary**


In April 2026 , Vercel suffered a security incident originating from a supply chain attack via the third-party AI tool Context.ai .
The incident originated with a compromise of Context.ai, a third-party AI tool used by a Vercel employee. The attacker used that access to take over the employee's individual Vercel Google Workspace account, which enabled them to gain access to that employee’s Vercel account. From there, they were able to pivot into a Vercel environment, and subsequently maneuvered through systems to enumerate and decrypt non-sensitive environment variables.

Vercel  assessed the attacker as highly sophisticated based on their operational velocity and in-depth understanding of Vercel's product API surface.

**Dwell Time**

**Initial Infection**

February 2026
The attack vector began when a Context.ai employee's device was infected with Lumma Stealer malware. This infostealer harvested OAuth session tokens and credentials.

**The Quiet Period**

 The attackers maintained access undetected for roughly two months, using the stolen tokens to bypass multi-factor authentication (MFA) and pivot through the Vercel employee's enterprise Google Workspace into Vercel’s internal systems.

**Discovery & Public Disclosure**

April 19 2026
The dwell time finally ended when the group ShinyHunters publicly listed the exfiltrated data for sale on BreachForums for $2 million, forcing immediate discovery and mitigation.





















 

