Tags - [- ransomware , Scattered Spider, retail ,UK ,UK GDPR ,ISO 27001  ]
**SUMMARY**
The attack was a chain of exploitation of loose end or vulnerable points.
Attackers impersonated an employee , got a third party service desk to reset a password , then took the NTDS.dit file from Active Directory and deployed DragonForce .Each link had a control that would have broken it : caller verification , a second approver for resets , tiering of privileged accounts , and monitoring for NTDS.dit access(A.8.5 ,A.8.2 ,A.8.16)


