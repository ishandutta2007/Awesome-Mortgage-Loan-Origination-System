# Awesome-Mortgage-Loan-Origination-System

## Top Mortgage Loan Origination System (LOS) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Mortgage Loan Origination, Point-of-Sale, Underwriting Workflows, Compliance, Closing & Lender Technology Stacks*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Mortgage Loan Origination Systems (LOS)**. These systems manage the end-to-end process of originating residential mortgage loans—from application and point-of-sale through processing, underwriting, closing, and secondary-market delivery—while enforcing regulatory compliance and document management.



**Examples** include ICE Encompass, Blend, LendingPad, Byte Software, SimpleNexus, Calyx Point, MeridianLink Mortgage, LendingQB, LoanLogics, and Shape LOS (the category leaders).



**Open-source emphasis**: Full-featured, production-ready mortgage LOS platforms are almost entirely commercial due to heavy regulatory, compliance, and integration requirements. Open-source activity is limited to general loan-origination experiments (including Apache Fineract-related work), historical open LOS efforts, and small academic or demo projects. This section lists every relevant project and realistic building block found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ICE Encompass](https://www.icemortgagetechnology.com/)**  

  Dominant enterprise mortgage loan origination system used by large lenders for the full origination lifecycle, compliance, underwriting, closing, and extensive partner integrations.



- **[Blend](https://blend.com/)**  

  Digital lending and point-of-sale platform focused on modern borrower experiences, application intake, and seamless handoff into LOS environments such as Encompass.



- **[Calyx Point](https://www.calyxsoftware.com/)**  

  Widely used LOS popular with mortgage brokers, smaller lenders, and credit unions for loan origination, processing, and pipeline management.



- **[LendingPad, Byte Software, SimpleNexus](https://www.lendingpad.com/)**  

  Cloud-native and mobile-friendly LOS / POS solutions targeting independent mortgage banks, brokers, and lender productivity.



- **[MeridianLink Mortgage, LendingQB, LoanLogics, Shape LOS](https://www.meridianlink.com/)**  

  Additional mortgage technology platforms covering origination, pricing, compliance, and specialized lender workflows.



- **[Other mortgage LOS & POS platforms](https://www.icemortgagetechnology.com/)**  

  Commercial systems supporting retail, wholesale, and correspondent origination channels with varying degrees of configurability and compliance tooling.



## Open-Source GitHub Projects



- **[Apache Fineract Loan Origination (PoC)](https://github.com/apache/fineract-loan-origination)**  

  Proof-of-concept loan origination service built around Apache Fineract. Manages pre-disbursement workflows (application, credit assessment, multi-stage approval) before creating the loan in Fineract. Explicitly marked as non-production-ready.



- **[Historical / community open LOS efforts (e.g., DigiFi lineage)](https://github.com/search?q=loan+origination+system+OR+LOS+open+source)**  

  Earlier open-source or open-core loan origination platforms that aimed to provide modular lending CRM, underwriting, and workflow capabilities. Status and licensing should be verified carefully.



- **[Small / academic mortgage LOS demos](https://github.com/search?q=mortgage+loan+origination+OR+LOS)**  

  Educational and prototype repositories illustrating basic loan application, document tracking, status workflows, and simple mortgage calculations.



- **[General lending & microfinance open systems](https://github.com/search?q=loan+management+OR+microfinance+OR+NBFC+LOS)**  

  Open-source loan management and NBFC-oriented tools that can be adapted for simplified origination flows outside strict U.S. residential mortgage compliance.



- **[Form, workflow & document engines](https://github.com/search?q=workflow+engine+OR+document+management+open+source)**  

  Self-hosted workflow, e-signature, and document-management components frequently used as building blocks for custom origination processes.



- **[Credit & decisioning open libraries](https://github.com/search?q=credit+scoring+OR+decision+engine+open+source)**  

  Open tools and models that support basic credit assessment or rules engines within a larger custom stack.



- **[CRM & case-management open tools](https://github.com/search?q=CRM+open+source+lending+OR+case+management)**  

  Open CRM platforms customized by some organizations for pipeline and borrower relationship management alongside a commercial LOS.



- **[Compliance & disclosure helpers](https://github.com/search?q=TRID+OR+mortgage+disclosure+OR+HMDA)**  

  Limited open utilities related to disclosure tracking or data reporting that may supplement commercial systems.



### Additional Strong Open-Source Options



- **Fineract ecosystem**: Core banking + the loan-origination PoC as a research or non-U.S. starting point.

- **Workflow + forms stacks**: Combine open workflow engines, form builders, and document stores for lightweight internal origination tools.

- **Data & analytics layers**: Open tools for pipeline reporting and basic HMDA-style analytics on top of LOS data extracts.

- **Integration middleware**: Open API gateways and iPaaS-style projects used to connect POS, LOS, pricing, and closing systems.

- Fully custom builds remain rare for regulated U.S. residential mortgage origination because of TRID, HMDA, fair-lending, and investor delivery requirements.



**Frameworks for building custom systems**:  

There is no mature, production-ready open-source equivalent to ICE Encompass, Blend, Calyx Point, or other commercial mortgage LOS platforms.  

The closest public efforts are the **Apache Fineract loan-origination proof-of-concept** and earlier open LOS initiatives whose current status must be verified.  

Most lenders rely on commercial LOS/POS systems for compliance, investor integrations, pricing engines, and auditability.  

Open-source components are best used for prototypes, internal tools, non-mortgage lending verticals, or integration layers around a commercial core. Any custom solution intended for U.S. residential mortgages requires extensive legal, compliance, and security review.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Mortgage loan origination is a heavily regulated activity. Systems must support applicable consumer-protection, fair-lending, disclosure (TRID), data-reporting (HMDA), privacy, and investor requirements. Incorrect configuration or missing controls can create significant legal and financial risk.

- Open-source projects in this space are generally experimental, incomplete, or not designed for regulated U.S. residential mortgage production. Do not deploy them for live loan origination without thorough security, compliance, and legal validation.



---



**Made for mortgage lenders, brokers, fintech builders, and technology teams evaluating loan origination platforms.**  

Let's document both the dominant commercial LOS ecosystem and the limited open-source experiments, while underscoring the regulatory realities that shape this category.
