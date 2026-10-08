**#Tools for Humanity (The Corporation behind World Coin ) - The Company that was scanning Kenyan People orbs for 7000ksh.**

**SECTION 1: EXECUTIVE SUMMARY**

Worldcoin collected iris scans from citizens in Kenya primarily during July and August 2023.This raised significant ethical concerns particularly in Kenya
— a developing country , where  40 % of its citizens ( an average of twenty million of its total population) live below the poverty
line therefore any form of financial benefit  posed as very tempting to residents. Worldcoin a cryptocurrency project  founded by 
Sam Altman aimed to address  issues of  digital identity and financial inclusion by providing a unique offering : biometric data 
in exchange for cryptocurrency.

At the crux of Worldcoin’s project lay an incentive structure where people were encouraged to share their biometric data , 
specifically iris scans , in exchange for a small amount of cryptocurrency . For many Kenyans  based on their destitution , a
promise of a digital financial reward was very enticing  — as the economic opportunities in this region remain meager and the 
promise of financial inclusion still waits to be upheld. Cryptocurrency for the Kenyan youth seemed like the first step in 
accessing the global financial ecosystem . However , beneath the surface , the floor was cracking and threatening to crash
their hopes with the dear costs of the exchange .

There seemed to be sophistry behind the Worldcoin project and their approach of data collection . There reasons seemed to be
an equivocation — because beneath it lay the issue with inadequate transparency about the risks associated with collection of
biometric data . Earning cryptocurrency is easily understood but the subtleties that came with biometric data value , its permanence
and the long term implications of its collection stretched it complexity even further . Financial data can change — it can  be
encrypted , health data can somehow be anonymized but biometric data is unique and it is impossible to alter once it has been
captured. But the question lingers do the participants understand that this exchange can have irreversible risks if the data is
mishandled ,misused or compromised in any way.

In Kenya the issue etches a bit deeper because of the ignorance of data and its value . They mostly had no idea of how the data 
is going to be used , stored , who has access to it , can they withdraw  their data  — but to some extent the questions of are
they well equipped to ask such questions.

**ARMS RACE** 

Worldcoin’s strategy of collecting data in marginalized countries like Kenya where the larger percentage of the population have no
idea of their rights , the value of their data and financial need is a persistent itch that needs to be scratched — seems extortive
and exploitative .It seems no different from the race of diamonds , cobalt and uranium in Central Africa . It all got  the same 
architecture beneath it  — the extractive practices — it can be said that the  nature of “powerful” countries and organizations extracting precious  resources for a pittance yet to enrich themselves .

**What are the risks of collection of the biometric data** 

**Data Losses and Data Breaches**

Worldcoin’s terms and conditions state the software used to create WorldID is an open source — it is free and open for anyone to use
. This means that anyone can “Fork “ the open source repository and modify the data . The company explicitly stated that it is not
responsible for the losses incurred in whole or in part by the Fork or any network disruption.

Furthermore , the terms and conditions stated that there will be no refund or compensation in the vent where the digital tokens are stolen by “hackers or other malicious groups “ of if there is an intentional or unintentional bug on the open source software they use . 
This left  Kenyans who sold or offered their data — whatever you wish to call it , exposed and vulnerable since Worldcoin had covered
all it's stretches in terms of legal  vulnerabilities and leaving Kenyans in the lurch .

This gives enough loop hole for the  malevolent to access sensitive personal information for their own nefarious designs with no
safe nets or process of recourse through world coin . Checking the checkbox to mean you have agreed to their terms and conditions 
meant that you have agreed to resolve any disputes between you and Worldcoin through binding arbitration rather than litigation . 

**Data Misuse** 

Biometric data is very intricate , and its inbuilt complexity cuts both sides , but this time we are getting the underside . The primary risk of biometric data lays in the permanent identity compromise ; unlike passwords , your finger prints , facial features and voice patterns cannot be changed if stolen — a single breach has the capability of creating a lifelong vulnerability . In case of biometric spoofing — attackers can use the stolen iris scan codes to create digital replicas that trick authentication sensors. Worldcoin project seemed more interested in evading any form of legal complications  than in creating sufficient safeguards .

**Training AI systems and Deepfakes** 

Frontier Artificial Intelligence models ( like Chat GPT , Deepseek and Claude) are trained by crawling and scraping billions of public web pages to build massive text , image , and video datasets . Keep in mind that the open source software with Kenyan biometric data is a public web page that can be scraped with out any restriction .

The biometric data can be used to create deepfakes — especially using stolen facial scans ,voice recordings, or mapped markers are fed into generative AI models to synthesize hyper-realistic impersonations that bypass security.
The biometric data can be combined with other information to build comprehensive profiles of individuals without consent to categorize , track and make assumptions about individuals .

**Section 2 :The System Architecture and Data Pipeline**

The Worldcoin’s data collection pipeline in Kenya as I have broken it down to the 5 steps system to be able to draw the kind of governance havoc it wrecked at each stage. I had previously tried to treat it as an undifferentiated mass dump of “ biometric data collection” which left my thoughts tangled — which is what led to this subsequent failure analysis tracing each statutory violation back to a specific architectural design decision rather than treating  the breach as one dump of undifferentiated act of negligence .

**Capture** 


The Orb device , a spherical chrome colored  hardware unit deployed by WorldCoin at registration sites placed in malls , various streets  across Nairobi  and other urban centers ; captured high - resolution images of  a participant’s iris and face .This stage is where the incentive structure did its work: a cryptocurrency payment of roughly 7,000 Kenyan shillings, pegged at approximately USD 50–55 depending on the exchange rate at time of payment and conversion , was offered in direct exchange for the scan. The High Court  later found this payment structure sufficient to invalidate consent under Section 32 of the KDPA — not because payment for data is inherently unlawful, but because the record showed the promise of payment functioned as the prompt rather than compensation for freely given participation — meaning most likely with out the incentive , the Kenyan citizens would have hardly stared at the orb for a second, particularly given the economic context in which it was offered.


**Transformation**


This was getting me confused  so let me  clarify . The raw capture is not what gets stored or transmitted onward . It is processed through an iris - recognition algorithm the industry-standard approach originating from John Daugman’s wavelet-based encoding method - into a compact binary representation known as an IrisCode , alongside a derived unique identity hash used to generate the World ID . 

**The Process**


The scan converted the eye image into a unique number code(an IrisCode) to prove the person was a unique , real human being , issuing them a digital World ID.
Worldcoin had (IRIS) Iris Recognition Inference System represents the step-by-step process that transforms an iris image into an iris code , the numeric representation of one's iris texture . It is the core engine that validates a person's uniqueness .
The Orb allows the secure verification of their World Id. The Orb also contains a suite of fraud detection models that enables humanness verification
which is not included in IRIS. The IRIS pipeline can generally be broken down into the following steps:

- Segmentation(to segment iris texture using our open-source AI model)

- Normalization(to convert iris texture from cartesian to Polar coordinates)

- Feature extraction (to generate IrisCode using Gabor filters)

- Iris Code matching(to generate Hamming distance between IrisCodes)

Each step in the process is vital for accurately validating the humanness and uniqueness of every Orb-verified World ID holder.

This is the stage at which Worldcoin’s  own public defense rested : company representatives , including Alex Blania , repeatedly characterized the IrisCode as a privacy-protective abstraction ,something closer to a one way hash than to the raw biometric itself, and argued that this transformation meant no one — "not even Tools for Humanity" — could link the stored code back to an identifiable person.

That defense does not hold up against the published security literature on iris template protection, because this  is the architectural claim the company's entire privacy case depended on. Unlike a cryptographic hash, which is designed so that recovering the input from the output is computationally infeasible, an IrisCode is designed primarily for matching accuracy — which means it necessarily retains more of the original structure than true one-way encryption would allow. Researchers at West Virginia University's Center for Identification Technology Research, working with Universidad Autónoma de Madrid, demonstrated that synthetic iris images could be reconstructed directly from iris-code data, convincingly enough to pass as a match against the original image in a live recognition system. Separately, security evaluations of biometric template-protection schemes specifically engineered to be irreversible — so-called "cancelable biometrics" — found that 75 to 95 percent of the original iris-code bits could be recovered through targeted attacks, and that two supposedly unlinkable protected templates could be correlated back to the same individual with complete accuracy under tested conditions. The practical implication for this case: storing the derived code rather than the raw image reduced exposure, but did not eliminate it, and did not meet the standard the company's own public reassurances implied. A compromised IrisCode is not equivalent to a compromised password — it cannot be reissued, and the research above indicates it carries more residue in  identifiability than a true anonymization technique would.

## **IDENTITY.**


The transformed data feeds into the World ID system, generating a unique global hash intended to serve as cryptographic proof of "personhood" — distinguishing a human registrant from an AI agent or bot without requiring a persistent, named identity. This layer is the architectural core of Worldcoin's stated mission, and it is also where the purpose-limitation problem in the KDPA analysis originates: Kenyan data subjects were told, with varying degrees of clarity across different disclosures, that their data would serve this proof-of-humanity function, but were not meaningfully informed of the downstream systems — the mobile wallet, the token economy, the broader Worldcoin app ecosystem — that the same identity layer would also support.

**CUSTODY**


Custody this answers the question — Who is responsible for the data ?

This was a question the design incorporated by Worldcoin cleverly avoided from four companies in four different locations  and a well curated terms of agreement that aided them to avoid the thin edge of the wedge of legal bureaucractic marathons.

**The Architecture behind Worldcoin Foundation .**

 Tools for Humanity (TFH)a Delaware US corporation headquartered at San Francisco , California a wholly owned subsidiary , Tools for Humanity GmbH based in Germany. On October 31st , 2022 the Worldcoin Foundation (”Foundation”) was established as the non-profit steward of the WorldCoin protocol , supporting and growing an ecosystem until it becomes self-sufficient . The foundation is an exempted limited guarantee foundation company , which is a type of non-profit , incorporated in Cayman Islands . It is a wholly-owned business company subsidiary in the British Virgin Islands called World Assets Limited. This structure is currently in use by protocol decentralized autonomous Organizations (DAOs).  The Foundation's own whitepaper frames its purpose as building "an inclusive identity and financial network" operated as a public utility, with governance intended to decentralize over time. That framing is worth holding up against the custody structure above: a network described as heading toward decentralized public governance was, at the time Kenyan biometric data was being collected under it, controlled through a four-entity offshore structure in which the two entities holding the deepest claim to the data had no registered presence in the country whose citizens supplied it.

The High Court's own judgment in the court proceedings presided by Lady Justice Roselynn Aburili  , in the Judicial Review proceedings brought by Katiba Institute and the Law Society of Kenya ( LSK), named the parties directly: Tools for Humanity Corporation, incorporated in  California  the United States; Tools for Humanity GmbH, its German subsidiary; Worldcoin Foundation, incorporated in the Cayman Islands; World Assets Limited, incorporated in the British Virgin Islands; and Platinum De Plus Ltd, the local Kenyan agent. Critically, only the two Tools for Humanity entities were registered with the ODPC — and only as data controllers, not processors — while Worldcoin Foundation and World Assets Ltd, identified entities  as the principal beneficiaries of the collected data, had no registration in Kenya at all. This was not  a random accidental tapestry of organized complexity. A four-entity structure spanning three offshore jurisdictions, in which the two entities with the deepest claim on the data were also the two with no registered presence, meant no single regulator could compel a complete accounting from any one party.

**TERMS OF AGREEMENT**


This answers the question of liability. What is at stake ?

WorldCoin’s terms and conditions state that the software used to create WorldID  is open-source and free for anyone to copy and use. This means that anyone can create a modified version of World ID, otherwise known as a “Fork.” The company stated that they are not responsible for any losses incurred which are caused in whole or in part by a Fork or other network disruption.

In addition, terms and conditions stated that there will be no refund or compensation in the event of digital tokens being stolen by “hackers or other malicious groups”, or if there is an “intentional or unintentional bug” on the open source software they use.

Agreeing to their terms meant that “You agree to resolve any disputes between you and Worldcoin through binding arbitration rather than in court.” the terms read in part, adding that the Worldcoin tokens accrued do not amount to an investment advice, nor can they be guaranteed to appreciate, hence the possibility to have zero value.

In what would potentially be a wild-goose chase for users, the terms further specified that there was no guarantee that the platform would  even be launched worldwide, and did not even guarantee its operation after all, as it is an open source software, which ‘anyone can copy, paste and use’.

https://citizen.digital/article/surprising-worldcoin-terms-and-conditions-kenyans-skipped-during-verification-n324827

https://fichauchi.org/fichauchi-worldcoin/

(originates directly from the **official Worldcoin Whitepaper** (originally published in July 2023 under the title ***A New Identity and Financial Network***)).



# **Section 3 : Failure Analysis**

**TECHNICAL FAILURE**


The failure stems upstream from a single statutory violation :a consumer-grade biometric capture device (orb) was deployed at public , high-foot-traffic sites like the KICC  with a payment-induced enrollment flow, and the resulting derived biometric templates were distributed across a custody structure the Kenyan Data Protection Officer  could not fully see through. The even bigger problem was the obscurity by design . Each subsequent legal failure is downstream of this initial design choice — a system built for rapid, incentivized, high-volume enrollment was structurally in tension with a compliance regime that required impact assessment before processing begins.


#### **GOVERNANCE FAILURE**

The failures compounded rather than sitting latitudinal to each other - they followed a series of meticulously designed break downs . The root failure was dismissing the Data Protection Impact Assessment (DPIA) under Section 31 - this the precondition the entire regime is built around . A DPIA is meant to surface exactly the risk (incentive-based consent, cross-border transfer , registration gaps ) that later materialized . This emanated mainly because this precondition was skipped , every downstream safeguard had nothing to pacify  it . Consent followed the collapse under Section 32 because inducement wasn't flagged in advance . The duty to notify  under Section 29 was satisfied superficially , with latent facts  since data data subjects were told about the "proof of humanity" purpose but not about the broader token-economy use or the specific jurisdictions their data would transit . The data subject rights under section 26 were unexercisable in practice because the custody structure meant no single entity could straightforwardly access their data or demand a withdrawal , this obsurity was scrupulously tailored in the Terms of Agreement. The principle of transparency under Section 25 was equally breached by similar custody opacity — a data subject could not meaningfully assess “lawful , fair and transparent” processing when the entity holding their data changes description depending on which hearing is being asked. The top layer that exposed  the underlying failures : unregistered controller/processor status for the two entities with the deepest claim to the data (Worldcoin Foundation, World Assets Ltd), and a cross-border transfer under Sections 48–49 to a location the company itself could not consistently state.

**Why Does This Matter Beyond Kenya :EU-AI ACT**


Under the EU-AI act , a system functionally identical to Worlscoin's orb would by default fall under Annex III , Category 1 as a high risk biometric identification system . This kind of classification would have triggered chapter III's full compliance package as a precondition for lawful deployment . A compliance package that would have entailed : a conformity assessment , a documented risk management system , data governance obligations and a mandatory registration in the European Union's high risk systems database , before a single individual actually stares at the orb. 
This is the closest equivalent to Section 31 of the Kenyan Data Protection Act named Data Protection Impact Assessment (DPIA) requirement , it imposes a comparable substantive obligation but the EU -AI act enforces it reactively . The Worldcoin's two year drag across the Kenyan litigation chain is a amongst the records of regulators catching a violation after deployed with out prior clearance.





#### **REGULATORY IMPLICATION**

This notes challenged my earlier assumption that the Kenyan Data Protection Act ( KDPA - 2019) lacked teeth . This research has proved otherwise potraying the KDPA as a binding with not only teeth but sharp canines cutting across jurisdictions. 

**This is the first perspective**  : 

 KDPA worked exceeding my expectations . A 2019 statute, applied patiently across three enforcement instruments over two years, produced a remedy (court-supervised cross-border destruction of biometric data) that few data protection regimes globally have achieved against a well-capitalized foreign technology company.

**The second perspective (the counter argument)** :

Worldcoin conduct was unusually negligent  - no DPIA at all ,inconsistent public statements under oath-adjacent parliamentary testimony, unregistered entities holding the most sensitive data . This means  almost any functioning regulator would have caught this, and the case tells us little about how KDPA performs against a  shrewd non- compliant who is a master at regulatory arbitrage , too clever by half . This could be a competent violator who clears the procedural bar by teetering at the edge of legality but still causes harm .

KDPA was exercised its capabilities as far as Worldcoin is concerned . Nevertheless bear in mind that nothing in the enforcement history required a novel legal theory: every finding maps to an existing, unambiguous statutory provision.
This  should temper any claim that this case proves KDPA is well-calibrated for an  AI -era  kind of harms generally — it proves KDPA can catch obvious, undisguised non-compliance. Whether it can reach a more sophisticated actor is the open question this case is not well equipped to answer.

# **Section 4:** Statutory Compliance Table


| Provision | Requirement | Violation Found | Instrument |
| :--- | :--- | :--- | :--- |
| **Section 31** | DPIA before high-risk processing | No Data Protection Impact Assessment (DPIA) was conducted | 2025 Judgment (Aburili J), E119 of 2023, [2025] KEHC 5629 (KLR) |
| **Section 25** | Lawful, fair, transparent processing | Custody opacity breached transparency principle | Same 2025 Judgment |
| **Section 26** | Data subject access/objection rights | Rights unexercisable given custody structure | Same 2025 Judgment |
| **Section 29** | Duty to notify before collection | Notice given for stated purpose only, not downstream uses/transfers | Same 2025 Judgment |
| **Section 32 / Section 32(4)** | Consent must be free, specific, informed | Crypto-token inducement invalidated consent | 2023 ODPC administrative determination |
| **Section 18(1)/(3)** | Accurate controller/processor registration | Misleading registration information | 2023 ODPC administrative determination |
| **Section 19(2)** | Basis for processing disclosure | Misrepresented legal basis | 2023 interlocutory injunction (Ngaah J) |
| **Section 37(3)** | Transfer safeguards | Inadequate safeguards disclosed to court | 2023 interlocutory injunction (Ngaah J) |
| **Section 48–49** | Cross-border transfer conditions | Transfer without proof of adequate safeguards | 2025 Judgment |
| **Art. 28, 31 Constitution** | Dignity, right to privacy | Underlying constitutional violation | 2025 Judgment |
 
**Section 5 : Evidentiary Gaps**

Three items I could not make a clean conclusion about and are flagged here for being unwholly resolved . First, the claim that Worldcoin's open-source software infrastructure made Kenyan biometric data scrapable for AI training or deepfake generation is plausible but unverified — the open-source status applies to the World ID protocol code, and no primary source in this record confirms that the actual biometric templates themselves were exposed through that channel; this claim should not be treated as established until a technical source confirms it directly.
Second, the Worldcoin Foundation's incorporation details (Delaware registration of Tools for Humanity Corp, the 31 October 2022 Cayman Islands establishment date) are sourced to the project's own whitepaper rather than an independent corporate registry filing, and carry the lower evidentiary weight that self-reported detail implies.
Third, secondary press accounts of the 2025 judgment are not fully consistent with each other — one outlet cites breach of "Sections 25, 31, and 38," while ICJ Kenya's own statement, corroborated independently, cites "Sections 25, 26, 29, 30, and 31." This note follows ICJ Kenya's account as the better-attested version, but the underlying judgment text itself (available via Kenya Law) remains the authoritative source and should be the final check before publication.


**Section 6: Why This Matters Beyond Kenya**

The Worldcoin case demonstrates something more useful, than a general claim that Kenya's data protection regime is either strong or weak relative to global peers. What it actually shows is that KDPA, applied patiently across three enforcement instruments over two years, can compel a remedy — court-supervised, cross-border deletion of derived biometric data — 


**Where did the Kenyan Data Protection Act shield Kenyans and what parts did Worldcoin Project Violate**

KDPA Section 19(2) 
An application under sub-section (1) shall provide the following particulars—
(a) a description of the personal data to be processed by the data
controller or data processor;
This is where the I see Worldcoin project introduced a lot of legal ambiguity and became as slippery as an eel 
KDPA Section 19(2)(b) a description of the purpose for which the personal data is to be
processed;- - The Worldcoin project stated that the purpose of collecting iris and facial scans was to provide "proof of humanity" and create a decentralized digital ID (World ID) to confirm a person is a unique, living human rather than an AI bot - This was the beginning of ambiguity.
13
No. 24 of 2019
Data Protection
(c) the category of data subjects, to which the personal data relates;
(d) contact details of the data controller or data processor;
(e) a general description of the risks, safeguards, security measures and
mechanisms to ensure the protection of personal data;
(f)
any measures to indemnify the data subject from unlawful use of data
by the data processor or data controller; and
(g) any other details as may be prescribed by the Data Commissioner.

**Breach of Data Protection Principles**

**Violation**

Section 25(b) of the act outlines data shall be  processed lawfully, fairly and in a transparent manner in relation to
any data subject;

**Ruling**


 The project lacked transparency. Most Kenyans were not given clear information about how their sensitive biometric data would be secured, stored, or institutionalized, directly violating the principle of accountability



**#Failure to Conduct a Data Protection Impact Assessment**


31.  Data protection impact assessment
(1)  Where a processing operation is likely to result in high risk to the rights and
freedoms of a data subject, by virtue of its nature, scope, context and purposes,
a data controller or data processor shall, prior to the processing, carry out a data
protection impact assessment.


**The Violation** : 

Under Section 31 of the KDPA, any entity processing data that poses high risks to the rights and freedoms of individuals—specifically sensitive biometric data like iris and facial scans—must complete and submit a mandatory DPIA before starting operations.


**The Ruling**:

Under Section 31 of the KDPA, any entity processing data that poses high risks to the rights and freedoms of individuals—specifically sensitive biometric data like iris and facial scans—must complete and submit a mandatory DPIA before starting operations.

**Violation of the rights of the data subject**


The data subjects were denied the rights below : They could not access their data in custody of Worldcoin or object to the processing of their personal data .

_KDPA Section 26_


(b) to access their personal data in custody of data controller or data
processor;
(c) to object to the processing of all or part of their personal data

**#Violation of the Duty to Notify**


29.  Duty to notify

30.  
A data controller or data processor shall, before collecting personal data, in so
far as practicable, inform the data subject of—
(a) the rights of data subject specified under section 26; 
They violated the data subjects rights by denying them access to their own data in custody of the data controller in this case Worldcoin project.
(b) the fact that personal data is being collected;
(c) the purpose for which the personal data is being collected;
Worldcoin never explicitly shared with the data subjects that their data is being used to build an open source platform that will have their biometric data - and use it to distinguish humans from Artificial Intelligence bots 
(d) the third parties whose personal data has been or will be transferred
to, including details of safeguards adopted;
(e) the contacts of the data controller or data processor and on whether
any other entity may receive the collected personal data;
The fact that the data would have been used as first hand training data for an open source  platform where anybody can access - meant the data could be used by anybody and it could be modified for whatever purpose. 
(f)
a description of the technical and organizational security measures
taken to ensure the integrity and confidentiality of the data; -Worldcoin made it very clear in their terms and conditions that "it is not liable for any forms of data losses or breaches " it shall therefore not offer any compensation to the participants in case of a breach in their open source platform . Furthermore , the participants can only resolve their issues with Worldcoin through arbitration and not litigation.



**#Violation Of Consent**

_KDPA Section 32(4)_ 


In determining whether consent was freely given, account shall be taken of
whether, among others, the performance of a contract, including the provision of
a service, is conditional on consent to the processing of personal data that is not
necessary for the performance of that contract.
In August 2023, the Kenyan ODPC collaborated with the Communications Authority of Kenya (CA) and the Ministry of Interior to halted all Worldcoin activities in the country. The agencies warned citizens that Worldcoin's practice of offering cryptocurrency tokens in exchange for iris and facial scans bordered on financial inducement rather than freely given consent.

**Cross-border data transfers**


KDPA Part VI - Section 48 and 49 


**Violation**


 The KDPA strictly regulates how personal and sensitive data can leave Kenya, ensuring the receiving nation or entity has equivalent legal safeguards.

 
 **The Ruling**

 
 Worldcoin transferred the collected biometric data outside Kenyan borders (storing it on Amazon Web Services servers in South Africa and other global locations) without obtaining proper authorization or valid clearance from the ODPC

 
**Misleading Registration Information**


**Violation** 

 Under the broader regulations supporting the KDPA, entities processing data must accurately register as data controllers or processors.


Section 18(3) of the KDPA: This section explicitly states that any person who "furnishes to the Data Commissioner any information which the person knows to be false or misleading, commits an offence".

**The Ruling**:


The High Court found that Worldcoin provided misleading information to authorities regarding its true activities and classification during registration.
