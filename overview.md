# **Decentralized Quantum Computing Funding — QC-DAO**


---

## **Vision**

A global, transparent DAO for quantum computing research and start-ups — funding innovation through collective intelligence.

---

## **Overview**

The Quantum Computing DAO (QC-DAO) proposes a decentralized, transparent, and expertise-driven funding ecosystem to accelerate global quantum innovation by providing research support from a community-governed, milestone-based model powered by blockchain. Through governance tokens (QFT), reputation-weighted voting, and stablecoin funding pools, the platform enables researchers, experts, contributors, and funders to collaboratively evaluate and advance high-quality quantum computing projects. Built on principles of open-source development, verifiable progress, and Sybil-resistant identity, QC-DAO integrates modern Web3 infrastructure to democratize access, reduce bias, and channel capital efficiently into start-ups, academic research, and foundational quantum technologies. This framework aims to foster rapid innovation, global participation, and long-term sustainability in the quantum computing ecosystem.


---

## **1. The Problem**

Quantum computing research is currently funded through a highly centralized model dominated by large government initiatives and corporate programs. Although billions of dollars flow into national programs like QEP3 and corporate ventures from companies like D-Wave, the funds rarely reach the long-tail of innovation—namely university researchers, small labs, and early-stage start-ups. These smaller players often hold the breakthrough ideas but lack efficient and accessible funding pathways.

At the same time, public interest in quantum computing is growing, yet individuals and smaller investors have no clear entry points to participate. Media narratives contribute confusion by alternating between exaggerated hype and skepticism, leaving potential contributors unsure how to engage. Without a mechanism to support bottom-up innovation and demonstrate near-term impact, the industry risks entering a “quantum funding winter,” which would significantly slow global progress.

---

## **2. The Solution — Decentralized Funding **

A decentralized funding model—built on blockchain and inspired by the DeSci movement—aims to democratize access to quantum research and accelerate innovation. By distributing decision-making and capital allocation across a global community, this model reduces bias, encourages transparency, and promotes a more diverse pipeline of ideas and contributors. Blockchain provides verifiable votes, auditable funding flows, and programmable incentives tied to measurable progress.

This approach also enables a broader set of participants to meaningfully contribute: researchers can propose projects, experts can evaluate them, and the public can support promising directions through governance tokens. The result is a system where good ideas can emerge from anywhere, credibility is earned through contribution rather than influence, and funding can flow more efficiently toward impactful research and start-ups.

---

## **3. Solution Overview**

The DAO ecosystem consists of proposers, experts, voters, and funders interacting through governance tokens and stablecoin pools. Proposers submit detailed quantum-related projects, which are pre-screened by experts before being opened to a wider voting community. Governance tokens (QFT) shape influence through reputation, delegation, and contribution history, while stablecoins form the actual funding mechanism for selected projects.

Through this layered structure, only the highest-quality and best-reviewed proposals advance to funding rounds. The system includes KPI tracking, milestone verification, and transparent reporting, ensuring accountability from proposers and confidence for funders. This creates a governance flow that blends decentralized decision-making with expert oversight, resulting in a reliable pipeline for quantum innovation.

---

## **4. Detailed System Design**

The platform defines five primary actors: proposers seeking funding, experts offering scientific review, voters shaping early-stage filtering, funders staking capital, and qualified investors participating in regulated environments. Each group plays a distinct role in ensuring that projects are vetted, evaluated, and funded based on their merit and potential impact. Governance tokens align incentives by rewarding knowledgeable participation, while stablecoins ensure predictable financial operations.

Incentive structures are designed to promote long-term engagement. Members can earn rewards through reviewing milestones, contributing code or datasets, producing educational resources, or providing mentorship. This makes the ecosystem not just a funding mechanism but also a community-driven accelerator for quantum computing research and talent development.

### **Actors**

| Actor        | Role                                                             |
| ------------ | ---------------------------------------------------------------- |
| **Proposer** | Proposes a quantum project; receives stablecoins if funded.      |
| **Expert**   | Verified credentials; comments and votes with governance tokens. |
| **Voter**    | Holds governance tokens; votes or delegates to experts.          |
| **Funder**   | Stakes stablecoins; votes on shortlisted projects.               |
| **Investor** | Regulated, qualified investors participating in later phases.    |

### **Tokens**

* **QFT** — governance token for expertise-weighted voting, reputation, and incentives.
* **Stablecoins** — actual funding pool for project grants.

### **Incentives**

* Networking & community access
* Education (courses, AMAs)
* Access to experts, research, and start-ups
* Reputation-based rewards

---

## **5. Proposal Requirements**

To maintain rigorous quality and transparency, proposals must include essential information such as detailed descriptions, milestone structures, funding needs, and openness levels. Proposers must also provide verified identities through LinkedIn or ORCID and present their work in accessible formats like whitepapers, demo videos, or app links. These requirements ensure both accountability and clarity for voters evaluating the project.

Large Language Models can also be used to generate readable summaries for busy voters, improving the community’s ability to quickly understand and assess technical proposals. This helps streamline the review process and increases participation without sacrificing scientific depth or clarity.

Each proposal must include:

* Project name
* Description (whitepaper, video, links)
* Key personnel + LinkedIn / ORCID
* Minimum funding needed
* Milestones + tranche structure
* Openness / open-source level
* Reward model (IP, updates, etc.)

**LLMs used to generate TL;DR summaries.**

---

## **6. Expert Requirements**

* Name, affiliation, short bio
* ORCID / LinkedIn
* Motivation for joining
* Photo for profile

---

## **7. Governance Principles**

Governance rules emphasize fairness, transparency, and scientific rigor. Expertise is prioritized over popularity by weighting votes according to reputation, evaluation history, and delegated authority. All governance decisions—from proposal progression to funding—are fully auditable on-chain, enabling independent verification and reducing bias. Milestone-based funding further ensures projects only receive additional support after delivering measurable progress.

The principles also promote open-source contributions, reinforcing the broader scientific mission of quantum research. The system remains adaptable, allowing modules such as investment functions or IP marketplaces to be added as the DAO matures.

* **Expertise over popularity** — weight votes by reputation/delegation.
* **Transparent & auditable** results.
* **Milestone-based funding** — only after verified progress.
* **Open-source bias** — prioritising open quantum algorithms & tools.
* **Adaptability** — modular expansion (e.g., investment platform later).

The DAO uses a combination of non-transferable credentials, reputation systems, and staking mechanisms to ensure integrity. Soul-Bound Tokens (SBTs) or verifiable credentials prevent identity manipulation by linking expertise to cryptographic badges. Quadratic voting reduces the impact of token-rich actors, while stake-to-vote systems ensure participants commit their tokens for a minimum duration.

Reputation decay and slashing mechanisms discourage spam, fraud, and low-quality participation. Meanwhile, lightweight KYC for experts and proposers reduces the risk of fabricated proposals or unqualified reviewers, all while maintaining pseudonymity for general voters.

---

## **8. QFT Token Incentive Model**

### **Proof-of-Contribution (PoC)**

QFT minted for:

* Reviewing/validating milestones
* Contributing code, datasets, results
* Writing documentation or educational content
* Hosting workshops / mentorship

### **Proposal Participation**

* Verified votes → micro-rewards scaled by reputation
* Anti-spam: decaying rewards (quadratic/log-weighted)

### **Delegation Incentives**

* Experts with strong track records receive QFT bonuses
* Based on oracle-verified success metrics

### **Reputation-Based Vesting**

* QFT is vested
* Can be clawed back if fraudulent or inactive

---

## **9. Anti-Manipulation & Sybil Protection**

* **Soul-Bound Credentials** (non-transferable SBTs) for experts/voters
* **Quadratic voting / staking**
* **Stake-to-vote** + slashing for misconduct
* **Light KYC for proposers & experts**
* **Reputation decay** for inactivity

---

## **10. Regulatory Strategy**

To avoid classification as a security, QFT tokens have no profit expectation and cannot be traded on exchanges. Instead, QFT serves strictly as a governance and utility token within the DAO. Stablecoins act as the funding layer, keeping financial flows compliant and straightforward.

The system incorporates minimal but essential regulatory considerations, such as lightweight KYC for proposers and experts, AML awareness, and jurisdiction-sensitive practices. This ensures that the DAO can scale responsibly across different regions and avoid regulatory pitfalls while maintaining accessibility.

* Governance/utility tokens only — **no yield, no investment promise**
* Non-tradeable (no DEX listing)
* Optional future airdrop (no guarantee)
* Clear tokenomics separation:

  * **QFT = governance**
  * **Stablecoin = funding**
* Minimal KYC (e.g., ZKPassport)
* AML awareness
* Avoid geopolitical bias

---

## **11. Technology Stack**

The technical stack integrates modern Web3 infrastructure with scalable off-chain systems. The front end relies on Next.js with wallet integrations via wagmi and RainbowKit. Data is stored using Supabase or MongoDB with Prisma, while Hardhat and ethers.js provide development and testing support. Identity can be managed using ZKpassport for privacy-preserving verification.

Monitoring and transparency are built into the system through oracle services, milestone verification tools, blockchain event logs, and analytical dashboards such as Dune, Tally API, or custom Voila/Streamlit apps. This ensures all stakeholders have real-time visibility into project progress and governance metrics.

### **App Integration**

* **Next.js**, **wagmi**, **RainbowKit**
* **Supabase / MongoDB + Prisma**
* **Hardhat + ethers.js** for testing

### **Identity**

* **ZKpassport**

### **Tokens**

* ERC-20 / ERC-1155 / Hybrid

### **Monitoring**

* Oracle-assisted milestone verification (Chainlink, events, API triggers)
* Dashboards via Dune, Tally API, or custom Streamlit / Voila

### **Transparency Metrics**

* Voter participation
* Funds allocated
* Project progress

---

## **12. Project Phases**

The project roadmap unfolds across three major phases. Phase 0 focuses on development, testing, and early community building. Phase 1 expands the ecosystem through marketing, governance token distribution, and the first grant round. It also introduces a public-facing presence via a website, social media, and a communication hub like Discord.

Phase 2 deepens engagement through dashboards, regional ambassador teams, hackathons, and cross-DAO collaborations. Finally, Phase 3 introduces the Quantum IP Sandbox, explores compliant IP tokenization models, and expands scientific outreach globally. These phases guide the DAO’s evolution from a prototype into a fully operational, globally recognized funding ecosystem.

### **Phase 0 — Build**

* Development, testing, community conversations

### **Phase 1 — Launch Community**

* Promote QDAO
* Build ecosystem partners
* Gather feedback
* Open the first grant round
* Distribute governance tokens

**Deliverables:**

* MVP App + landing page
* X/Twitter account
* Public Discord/Telegram

### **Phase 2 — Growth**

* Dashboards
* Regional ambassadors
* Hackathons & bounties
* Begin Foundation formation
* Cross-DAO partnerships

### **Phase 3 — Expansion**

* Quantum IP Sandbox
* Legal & academic partnerships
* Explore tokenized IP models
* Expand global fellowships

---

## **13. To-Do List**

Key action items include completing the whitepaper, building the DAO’s smart contracts, and conducting a third-party audit. The outreach plan is structured around a funnel that progresses from whitepaper publication to partnerships with quantum companies such as QCi, IBM, Quantinuum, and finance institutions like HSBC and DBS.

Additional focus areas include preparing hackathons, designing token reward systems, and organizing a launch event. These tasks collectively build the foundation needed for a successful testnet deployment and eventual mainnet operation.

* Smart contract development
* DAO audit
* Whitepaper
* Official website
* Outreach plan (whitepaper → site → proposals → partnerships)
* Corporate partnerships: QCi, IBM, Binance, Classiq, Quantinuum, HSBC, OCBC, DBS
* Hackathons + token rewards
* Launch event

---

## **14. Expectations**

The estimated setup cost is low—around $200 for hosting and testnet infrastructure—while audits and future upgrades may require additional investment. The DAO is expected to operate leanly using platforms like Vercel for hosting and Sepolia for testing. Long-term success is measured by the volume of funded proposals, with an aspirational goal of at least one funded project per month.

Financial projections envision rapid growth in funding flows: $10M in Year 1, $100M in Year 2, and $1B in Year 3. These targets reflect the belief that decentralized funding can unlock massive global interest in quantum technologies once a trustworthy and transparent platform exists.

* Setup cost: ~$200
* Network: Sepolia (testnet)
* Audit: Ottersec
* Hosting: Vercel (free plan)
* Target funding flow:

  * **Year 1:** $10M
  * **Year 2:** $100M
  * **Year 3:** $1B
* Target: Fund **1+ proposal per month**

---

## **15. Timeline**

The timeline includes a development and testing phase concluding in December 2025, followed by a full launch in January 2026. This schedule allows adequate time for contract testing, website deployment, initial community activation, and smart contract audits.

* **Dec 2025:** Design → Development → Testing
* **Jan 2026:** Public Launch

Immediate next steps include finalizing the website design, coding smart contracts, preparing the Sepolia test environment, and developing automated testing scripts. Marketing plans and audit preparations must also begin in parallel. Funding for the DAO may involve accelerator programs (such as Binance), venture capital, or angel investment.

---

## **17. Potential Projects**

quantum machine learning applications, Q-GPT systems, and collaborative initiatives between Japan and Singapore. These projects provide high-impact candidates for initial grant rounds and serve as compelling use cases to attract community engagement.

* QRE (Quantum Risk Engine)
* Quantum Finance
* QML for Fraud Detection
* Q-GPT

