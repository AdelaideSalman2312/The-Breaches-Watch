Tags - [- ransomware , Scattered Spider, retail ,UK ,UK GDPR ,ISO 27001  ]

--
**SUMMARY**

--
The attack was a chain of exploitation of loose end or vulnerable points.
Attackers impersonated an employee , got a third party service desk to reset a password , then took the NTDS.dit file from Active Directory and deployed DragonForce .Each link had a control that would have broken it : caller verification , a second approver for resets , tiering of privileged accounts , and monitoring for NTDS.dit access(A.8.5 ,A.8.2 ,A.8.16)


**Technical Failure**
1.**Human Layer Failure** 

--
Threat actors linked to the Scattered Spider group impersonated an M&S employee and tricked a third party contractor into resetting access credentials.


--
2.**Weak Vendor Governance**

--
Excessive implicit trust and weak verification controls at the third-party help desk allowed initial entry without a direct technical exploit

--
3.**Segmentation**
Norman - M&S Chairperson told MPs that M&s has many legacy systems that make segmentation difficult and in case of an attack like that they experienced in April 2025 , the minimal segmentation enables easy lateral movement.Good — let's build the actual copy now, ready to paste in directly, section by section.The lack of robust microsegmentation allowed the DragonForce ransomware to spread broadly, impacting internal logistics alongside customer systems

.

--

4.**Lateral Movement**
Attackers leveraged the compromised credentials to escalate privileges and move through the enterprise network due to a lack of strictly identity -based access.

**Dwell time and Detection time**

--
**Initial Access**
Attackers gained unauthorized entry into the network via a compromised third-party vendor on April 17,2025(through foundational reconnaissance and early credential extraction , such as Active Directory database access - the attack 
reportedly began as early as February 2025)

--
**Detection Time**
M&S leadership and security teams identified that a breach had occurred on the late afternoon of April 19,2025 - roughly two days after the active operational infiltration occurred.

--
**Total Dwell Time**
The attackers maintained undetected or uncontained access moving laterally through the network for roughly two months(from February through April 24,2025) before the full ransomware payload and operational disruption took effect.

**Response**
Mark and Spencer retail shop sent emails to their customers after the breach on the 19th of April. The contents of the email :
"To proactively manage the incident, we immediately took steps to protect our systems and engaged leading cyber security experts. We also reported the incident to relevant government authorities and law enforcement, who we continue to work closely with.

Unfortunately, the nature of the incident means that some personal customer data has been taken, but there is no evidence that it has been shared. The personal data could include contact details, date of birth and online order history. However, importantly, the data does not include useable card or payment details, and it also does not include any account passwords."






