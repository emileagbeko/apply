# 📝 Land Trust

## 🌟 Project Overview

Please provide the following:

**Tagline**:
Verified land ownership. Anchored on-chain. Built for Africa.

**Description**:
LandTrust is a blockchain-based platform for securing and verifying land ownership. Trusted agents — such as chiefs, lawyers, 
and surveyors. upload verified land records that are anchored on-chain and issued as tamper-proof certificates.
We’re starting with a pilot in Ghana, where land fraud is widespread. Long term, we aim to become the digital trust layer for land across sub-Saharan Africa.

**How this integrates with Polkadot**:
We use ink! smart contracts and IPFS to store and anchor land records. Polkadot allows us to stay lean while remaining compatible with future integrations
like DeFi, digital identity, and cross-chain registries.

     For example, a farmer could use a verified record from LandTrust to access a loan through a DeFi app without any bank visits,
     no fraud, just verified ownership. This is possible because of Polkadot’s interoperability.
  
**Why we’re building this**:
Land fraud has destroyed lives in Ghana, including in our own families. We’re building LandTrust to protect ownership, prevent disputes, and open access to 
land-based financing.



### 🔍 Project Details

We expect applicants to have a solid idea about the project's expected final state. Therefore, please submit (where relevant):

Tech Stack:
- **Smart Contracts:** ink! (Substrate)
- **Frontend:** Lovable MVP → React or Flutter later
- **Storage:** IPFS to anchor land record files (PDFs, certificates) + generate QR codes
- **Auth:** Web3Auth — simple email or social login for non-crypto-native users

Core Components:
- Agent dApp to submit land records
- QR code generation
- Traditional file storage (e.g. Firebase), with on-chain hash anchoring for tamper-proof verification
- Read-only explorer for stakeholders
- Admin dashboard mockup

Out of scope (MVP):
- Biometric/GPS data
- Ghana Card or ID linkage
- End-user interface
- Governance or tokenization features



### 🧩 Ecosystem Fit

Help us locate your project in the Polkadot landscape and what problems it tries to solve by answering each of these questions:

Where we fit:
Public-good infra in Polkadot’s DePIN + real-world asset stack

Target users:
- Traditional authorities
- Land commissions
- NGOs, rural banks, individuals

Needs solved:
- Land record fraud and disputes
- No verifiable digital trail
- Inability/Slow access land-backed finance

Differentiation:
- Other projects focus on tokenization or speculation. LandTrust starts with trust, verified ownership and anchored
  by the people who hold real authority on the ground.

> **Note**: We prioritize projects building on Plaza/Polkadot Hub, games, and DeFi applications, though all types of projects will be considered.

## 👥 Team

- **Team Name:** LandTrust.
- **Contact Name:** Emile Delali Agbeko
- **Contact Email:** delali4647@gmail.com
- **Website:** [Your website, GitHub org, blog, or similar](https://www.linkedin.com/in/emileagbeko/)

### Team members

Please list the legal name of all grant beneficiaries. Solo developers (1-person teams) are eligible for funding.

#### LinkedIn Profiles (if available)

- [https://www.linkedin.com/{person_1}](https://www.linkedin.com/in/emileagbeko/)
- [https://www.linkedin.com/{person_2}](https://www.linkedin.com/in/lawrence-ofosu-8b4592a1/)

### Team Code Repos

- https://github.com/{your_organisation}/{project_1} N/A
- https://github.com/{your_organisation}/{project_2} N/A

Please also provide the GitHub accounts of all team members:

- [https://github.com/{team_member_1}](https://github.com/emileagbeko)
  

### Team's experience

**Emile Delali Agbeko** – Product & Technical Lead
- Leads product, technical architecture, and stakeholder engagement
- Participated in the most recent Polkadot hackathon
- Experienced in building fast, lean MVPs with real-world users in mind

**Lawrence Takyi Ofosu** – UX & Community
- Web Content Specialist at doTERRA Europe
- AWS Certified Cloud Practitioner
- Brings strong UX, stakeholder outreach, and deep connections in Ghana

*We're focused on delivering the MVP ourselves including the smart contract.
If we find an experienced ink! dev who can help us move faster, we may bring them in. But we're not dependent on it.*

## 📊 Development Status

- ink! contract development is underway
- Lovable MVP frontend in progress (A live prototype is available at https://nhyira.online showing the concept)
- Traditional storage system set up with QR + file hash workflow
- We’re in active conversations with officials from the Ghana Lands Commission and regional chiefs.
  These relationships give us a strong foundation to secure a formal LOI and launch a credible pilot.

## 📅 Development Roadmap

This section should break the development roadmap down into milestones and deliverables. Since these will be part of the agreement, please describe *the functionality we should expect in as much detail as possible*, plus how we can verify and test that functionality.

**Important notes:**
- Each milestone is capped at **$5,000 USD**
- Milestones must be delivered within **3 months** of approval
- The maximum grant amount is **$10,000 USD** per application (up to **$15,000 USD** per project in exceptional cases)
- You will only receive payment after successful milestone delivery

### Overview

- **Estimated Duration:** 3 months
- **Full-Time Equivalent (FTE):**  2
- **Total Costs:** $10,000 USD

> Note that deliverables 0a to 0d are mandatory. Please adapt their specification to your project.

#	Deliverable	Description
0a	License	MIT
0b	Documentation	Setup instructions and inline code comments
0c	Testing	Unit tests for smart contract logic
0d	Article	Recap of pilot and learnings
1	LOI + Pilot Plan	Signed LOI + rollout plan for 1–2 districts
2	MVP	Agent record submission UI + QR + file hash logic
3	Agent Demo	10–15 mock records, 5+ stakeholders, feedback summary

### 💰 Budget Breakdown

Please provide a breakdown of your budget by milestone:

| Milestone | Deliverables | Cost (USD) | Estimated Completion |
| --- | --- | --- | --- |
| 1 | Features X, Y | $5,000 | 1.5 months |
| 2 | Feature Z | $5,000 | 1.5 months |
| **Total** | | **$10,000** | **3 months** |

Milestone	Description	Amount (USD)	Timeline
1	Government LOI + Pilot Plan	$3,000	1-45 days
- Legal or community consultation for drafting the LOI
- In-country outreach (in-person/remote), including meetings with officials and agents
- Document drafting, legal review, and printing if required
- Stakeholder and logistics prep for rollout
  
2	MVP dApp + Hash Verification	$3,000 1-60 days
- File storage (Firebase or similar), with QR generation for each record
- Smart contract deployment using ink!
- Developer tooling, testing environments, and initial documentation



3	Agent Demo + Feedback	$4,000	60- 90 days
  - Incentives or travel support for pilot participants
  - Coordination and scheduling of agent onboarding sessions
  - Iteration on the user flow based on real-world feedback
  - Documentation of findings, including user experience report

## 🔮 Future Plans

Please include:
- Expand to more districts and agents
- Add land tokenization (e.g. verified digital certificates or SBTs)
- Explore mapping and spatial verification tools
- Integrate with identity and credit systems
- Apply for Treasury grants and early-stage funding (if needed)
  
## ℹ️ Additional Information

Here you can add any additional information that you think is relevant to this application, such as:
- We’re not taking salaries from this grant — funds go directly into the pilot
- The MVP is scoped to ship quickly and prove value fast
- We’re doing things that don’t scale — including direct outreach to chiefs, agents, and ministries

Remember that the Fast-Grants Programme is designed as a first step for promising projects. We're looking for projects that can continue to grow beyond this initial funding.
