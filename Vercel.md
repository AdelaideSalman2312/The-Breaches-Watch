Date of Incident - April 19 , 2026
Tags-[supply chain attack, -OAuth permissions escalations ]

**Summary**
In April 2026 , Vercel suffered a security incident originating from a supply chain attack via the third-party AI tool Context.ai .
The incident originated with a compromise of Context.ai, a third-party AI tool used by a Vercel employee. The attacker used that access to take over the employee's individual Vercel Google Workspace account, which enabled them to gain access to that employee’s Vercel account. From there, they were able to pivot into a Vercel environment, and subsequently maneuvered through systems to enumerate and decrypt non-sensitive environment variables.

Vercel  assessed the attacker as highly sophisticated based on their operational velocity and in-depth understanding of Vercel's product API surface.
