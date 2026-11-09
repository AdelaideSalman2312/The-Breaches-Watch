 # Executive Summary

The Plaintiffs Andrea Bartz, Charles Graeber, and Kirk Wallace Johnson on behalf of
themselves and all other similarly situated (the “Class,”), for their complaint
against Defendant Anthropic PBC (“Anthropic”)
Their complaint was that :

Anthropic has built a multibillion-dollar business by stealing hundreds of thousands
of copyrighted books. Rather than obtaining permission and paying a fair price for the creations it
exploits, Anthropic pirated them. Authors spend years conceiving, writing, and pursuing
publication of their copyrighted material. The United States Constitution recognizes the
fundamental principle that creators deserve compensation for their work. Yet Anthropic ignored
copyright protections. An essential component of Anthropic’s business model—and its flagship
“Claude” family of large language models (or “LLMs”)—is the largescale theft of copyrighted
works.
Bartz and the other plaintiffs  are authors of an array of works of fiction and non fiction .
They brought this action under the Copyright Act to address the harm caused by Anthropic’s brazen infringement.
Anthropic downloaded known pirated versions of Plaintiffs’ works, made copies of them, and fed
these pirated copies into its models. Anthropic took these drastic steps to help computer algorithms
generate human-like text responses. 
Anthropic had not even attempted to compensate Plaintiffs for the use of their
material. In fact, Anthropic has taken multiple steps to hide the full extent of its copyright theft.
Copyright law prohibits what Anthropic has done here: downloading and copying hundreds of
thousands of copyrighted books taken from pirated and illegal websites
Anthropic’s Claude LLMs compromise authors’ ability to make a living, in that the
LLMs allow anyone to generate—automatically and freely (or very cheaply)—texts that writers
would otherwise be paid to create and sell. Anthropic’s LLMs, which dilute the commercial market
for Plaintiffs’ and the Class’s works, were created without paying writers a cent.
nthropic’s immense success is a direct result of its copyright infringement. The
quality of Claude, or any LLM, is a consequence of the quality of the data used to train it. The more
high-quality, longform text on which an LLM is trained , the more adapt an LLM will be in generating 
lifelike, complex, and useful text responses to prompts. Without usurping the works of
Plaintiffs and the members of the Class to train its LLMs to begin with, Anthropic would not have
a commercial product with which to damage the market for authors’ works. Anthropic has enjoyed
enormous financial gain from its exploitation of copyrighted material. Anthropic projects it will
generate more than $850 million of revenue in 2024.
 After ten rounds of funding, Anthropic has
raised $7.6 billion from tech giants like Amazon and Google. As  of December 2023, those investments
valued the company in excess of $18 billion and is likely even higher today in 2026.. Anthropic’s 
commercial gain has come at the expense of creators and rightsholders,
including Plaintiffs and members of the Class. Book readers typically purchase books. Anthropic
did not even take that basic and insufficient step. Anthropic never sought—let alone paid for—a
license to copy and exploit the protected expression contained in the copyrighted works fed into its
models. Instead, Anthropic did what any teenager could tell you is illegal. It intentionally
downloaded known pirated copies of books from the internet, made unlicensed copies of them, and
then used those unlicensed copies to digest and analyze the copyrighted expression-all for its own 
commercial gain. The end result is a model built on the work of thousands of authors, meant to
mimic the syntax, style, and themes of the copyrighted works on which it was trained.
The irony is that Anthropic styles itself as a public benefit company, designed to improve humanity.
In the words of its co-founder Dario Amodei, Anthropic is “a company that’s focused on public
benefit.”

**Anthropic Safety values**

"At Anthropic our motto has been “show, don't tell”, and we've focused on releasing a steady stream of safety-oriented research that 
we believe has broad value for the AI community."
"In short, we believe that AI safety research is urgently important and should be supported by a wide range of public and private actors."


 For holders of copyrighted works, however, Anthropic already has wrought mass
destruction. It is not consistent with core human values or the public benefit to download hundreds
of thousands of books from a known illegal source. Anthropic has attempted to steal the fire of
Prometheus. It is no exaggeration to say that Anthropic’s model seeks to profit from strip-mining
the human expression and ingenuity behind each one of those works.



**What Fair use actually implies**

A court ruling that "the training use was fair use" means that an AI company did not commit copyright infringement when it used 
copyrighted text, books, or data to train its artificial intelligence model.


**What This Means in Practice**

• **Transformative Learning**: Courts comparing AI training to human learning have found that feeding books or data
into an AI model is transformative—meaning the AI analyzes patterns, styles, and facts to build a new tool rather 
than just making copies to sell the original works.

• **No Permission or Payment Required**: Under the U.S. doctrine of fair use (outlined in Section 107 of the Copyright Act), a user or company can legally use copyrighted material without the creator's permission or paying a license fee if the use meets specific legal standards.
• **Landmark Decisions**: This principle was reinforced in high-profile court cases like Bartz v. Anthropic and Kadrey v. Meta, where federal judges ruled that training large language models (LLMs) on copyrighted text qualifies as fair use.

**Important Limits and Caveats**

•**Not a Blanket Shield for All Actions**: Fair use applies to the process of training the model on the data, not necessarily to everything an AI company does. For example, in the Anthropic case, the judge ruled that storing millions of pirated books in a central library database was not protected fair use and could still lead to liability

# System Architecture
Court documents showed Anthropic downloaded over 7 million books  from  pirate sites , in part to use as training data for its AI development . It also bought and scanned millions for the same purpose .
In this landmark copyright lawsuit *Bartz vs Anthropic* ,U.S. District Judge William Alsup drew a sharp legal line between how an AI model is trained and how its training data is acquired. Initially , the lawsuit  attacked the entire practice of using copyrighted works to train AI  but in June 2025 the Judge split the baby . He ruled that Anthropic usage of legally acquired books for AI training was "quintessentially transformative" and protected as fair use—but simultaneously held that downloading and keeping pirated copies was not fair use, and strongly suggested that he would find such uses to be straight-up infringement. This split decision left Anthropic partially vindicated on the big question of AI training but still facing massive liability for downloading books from LibGen and similar sources. 


<img width="1000" height="1490" alt="Acquisation pipeline" src="https://github.com/user-attachments/assets/eef3b650-4efc-4859-a7e4-48e3ec3c464a" />

# Legal / Governance Failure 

So far Bartz vs Anthropic is a copyright case - therefore no data governance framework was used to make the final or procedural judgements of the case.

**Decision Governance**
**Lineage and Record-Keeping**
Anthropic said it could not count all of its copying (pp. 8–9), and the order notes that even estimating the training copies would be impractical (p. 6). A spreadsheet showing the composition of data mixes was produced and then withdrawn (p. 9). Anthropic carried the burden on summary judgment, and the court held the deficiencies against it (pp. 8–9). It could not decide the status of other library copies because the record was too thin (p. 31). The missing lineage records therefore became a legal exposure, not only an operational gap.
Anthropic argues at one point that the books were being used for transformative purposes - this now brings the question of machine unlearning ?

**Retention and Access**
The planning described in the order was to keep everything with no compelling reason to delete any book (p. 5). Copies were retained after the decision not to train on them (p. 19). Hundreds of engineers could access the library, and the order describes no limits on access or use (pp. 22, 31).

**Controls that Operated**
Print originals were destroyed, so one copy replaced another with no redistribution, which the court treated as material (pp. 16–17).
Input and output filtering meant no infringing outputs were alleged (pp. 7, 12).
From 2024, purchasing replaced downloading (p. 4). The court noted Anthropic could have bought the books and later did (pp. 21, 29).






# Project Panama 

<img width="1000" height="1490" alt="Panama" src="https://github.com/user-attachments/assets/0f1803ca-cf1e-40ad-80c1-5bbf26c822dd" />

Incident date : Early 2024


An extension of the piracy and copy right infringement that Anthropic was prior accused of.Project 
Panama is a destructive book scanning operation started in early 2024 by the American artificial 
intelligence corporation Anthropic.
Prior to Project Panama, Anthropic used pirated books and was sued, agreeing in 2025 to pay $1.5 
billion in a settlement. The class-action copyright lawsuit revealed the existence of Project Panama
through unsealed court filings, in which it was described internally as an "effort to destructively
scan all the books in the world". In the same 2025 litigation, Judge William Alsup ruled that 
Anthropic's use of legally purchased books for digitization and model training constituted fair use, in contrast to its prior use of pirated copies.
Project Panama aims to develop a dataset of books for training Anthropic's large language models.
# **Operation**

Anthropic began by obtaining millions of previously digitized works through digital piracy. According to court documents, Anthropic used Books3, LibGen, 
and Pirate Library Mirror for this purpose, and may have acquired up to 7 million books in this way.
Project Panama was started in early 2024, aiming to "destructively scan all the books in the world".

**Core details of the Operation**

**The main idea behind Panama** 

 Anthropic executives wanted high-quality training material to teach its Claude AI chatbot human-level writing style and reasoning. They explicitly sought to avoid training models on "low-quality internet speak."

 **The Execution**
 
Anthropic hired Tom Turvey—the former head of partnerships for Google Books—to spearhead the acquisition. The company spent tens of millions of dollars  purchasing  millions of used books from online retailers such as Better World Books, World of Books, and Zoom Books. 

**The "Destructive Scan" Process**

To handle the immense volume (estimated between 500,000 and 2 million books over a six-month period), Anthropic utilized automated facilities.
The company then sliced off their spines and scanned their pages in order to train its AI chatbot Claude. This process involved the use of hydraulic cutters chopped off the bindings and book spines , allowing loose pages to be rapidly fed through high-speed imaging scanners before being discarded for paper recycling.
The dataset was then kept private and used only for training models. According to the Project Panama planning document,
Anthropic did not "want it to be known that it was  working on this" , but Unsealed court documents from a subsequent author class-action lawsuit (Bartz v. Anthropic) revealed the inner workings of the project, including an internal memo that explicitly defined its objective: "Project Panama is our effort to destructively scan all the books in the world".

Sources 
https://www.euronews.com/2026/08/05/project-panama-how-anthropic-secretly-destroyed-millions-of-books-to-train-its-ai

# Conclusion 

Judge William Alsup's ruling is the sharp line drawn between data ingestion for model training and permanent data warehousing . This gives this case study a whole different angle : data governance . I came in thinking this was an AI governance case study but just like Anthropic this was shattered by Alsup's take on the case - procedurally .

For AI GRC this marked a turning point formally decoupling AI model training from upstream data management.
Before this case, AI GRC primarily focused on model behavior, output safety (guardrails against harmful/infringing content), and algorithmic bias. Bartz proved that a company can build a legally defensible model and still face a $1.5 billion financial exposure due to poor data governance at the ingestion layer.

# What shift did it make in Enterprise AI governance

**Data Lifecycles -Upstream Data Ingestion vs Model Training**

**Model Training (Transformative Use)**: Extracting non-expressive statistical patterns from text to train a neural network is fair use. GRC teams do not need to assume that feature extraction itself violates copyright. -- in this one companies will be protected in the fair use policy .

**Central Mandate(Non transformative Piracy)**:Accumulating, holding, or archiving unauthorized datasets (such as Books3 or LibGen dumps) into central research repositories is an unexcused copyright violation, even if intended for subsequent model training.

Where does this leave governance - As a governance specialist I can no longer treat "data ingestion" as a single step . Alsup's ruling showed that Frame works must separate Data Sourcing and storage from Model Feature Extraction they are not the same .

**Influence and Integration into Standard Risk Frameworks (NIST AI RMF & ISO/IEC 42001)

| Framework Phase | Pre-Bartz GRC Focus | Post-Bartz GRC Requirement |
| :--- | :--- | :--- |
| **Map / Categorize** | Model type, deployment context, user safety. | **Dataset Lineage Mapping:** Identifying source origin, copyright status, and usage rights for every raw dataset. |
| **Measure / Audit** | Hallucination rates, toxicity, latency, PII leaks. | **Retention & Purge Audits:** Automated verification that raw training files are deleted or decoupled post-tokenization. |
| **Manage / Govern** | Terms of Service, prompt guardrails, output filters. | **Data Provenance & Vendor Due Diligence:** Verification that third-party data providers have clean rights of acquisition. |

**3.Standardizing Data Lifecycle Purging Controls**
From an operational GRC perspective, Bartz introduced the necessity of Data Minimization - (like in data governance) and Ephemeral Processing for AI development pipelines:

**Transient Processing Buffers**: Technical controls must enforce that raw web scrapes or ingested texts exist only in temporary, ephemerally isolated scratch space during cleaning and tokenization.

**Automated Destruction Protocols**: Proof-of-deletion mechanisms must be logged in audit trails once dataset weights or embeddings are extracted.

**Prohibition of "Hoarding"**: Corporate AI governance policies must explicitly ban maintaining general-purpose, non-expiring data libraries of unverified or pirated third-party content.

**4. Vendor Risk Management (VRM) for Enterprise AI Buyers**

For enterprise buyers integrating 3rd-party foundation models (or fine-tuning custom adapters), Bartz reshaped procurement risk questionnaires:

**Indemnification Scope**: Organizations now require model providers to explicitly indemnify them not just against output infringement, but against input-side statutory data liabilities. 

**Attestation of Data Rights**: Enterprise RFPs increasingly require AI vendors to submit certified evidence of data provenance (e.g., verifying that data mix components were either licensed, created under format-shifting purchase rules, or sourced from compliant public web crawls)



