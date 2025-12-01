# Chain Insights Subnet — Light Paper

**Decentralised Blockchain Intelligence for the Agentic Economy**

*Powered by Chainswarm Technology*

Version 1.1 | 2025

---

## Executive Summary

Chain Insights Subnet is a decentralised blockchain intelligence network built on Bittensor that provides real-time risk scoring, funds tracking, and investigative AI capabilities. Unlike centralised solutions that charge enterprises significant annual fees and offer no access to developers or retail users, Chain Insights delivers intelligence through three channels: a consumer application, an enterprise API, and an x402-enabled gateway for autonomous AI agents.

The subnet operates on a novel principle: **computation is cheap, innovation is priceless**. Rather than rewarding miners for running infrastructure, Chain Insights rewards researchers, data scientists, and AI engineers for improving algorithms, training superior models, and discovering validated intelligence. The subnet owner operates core infrastructure to ensure reliability, while miners compete in tournaments to advance the state of the art.

This architecture positions Chain Insights as the default intelligence layer for the emerging agentic economy—where autonomous systems require real-time, programmatic access to risk assessment before executing transactions.

---

## The Problem

### Centralised Intelligence is Broken

The blockchain intelligence market is dominated by a handful of centralised providers—Chainalysis, Elliptic, TRM Labs—who serve enterprise clients at premium prices. This model creates three critical gaps:

**1. Accessibility Gap**
Retail users are blocked by exchanges/services but have no visibility into their own risk profiles or way to understand why their address was flagged.

**2. Developer Gap**
The agentic economy is emerging rapidly. Autonomous AI agents, DeFi protocols, and smart wallets need programmatic access to risk intelligence. Current providers offer no API access suitable for real-time, pay-per-query autonomous systems.

**3. Innovation Gap**
Closed systems innovate on their own timelines. Algorithm improvements, new pattern detection, and model updates happen behind proprietary walls. The broader ecosystem cannot contribute to or benefit from these advances.

### The Regulatory Imperative

Global regulation is accelerating. The EU's MiCA framework, US FinCEN Travel Rule, and expanding KYC requirements worldwide mean that every exchange, wallet, and DeFi protocol will require compliance tooling. The market for blockchain intelligence is not shrinking—it is about to expand dramatically.

---

## The Solution

### Neutral Intelligence Layer

Chain Insights Subnet provides a **neutral intelligence layer** for any blockchain. We don't decide who is good or bad—we provide the intelligence. Users, applications, and agents choose how to act on that intelligence.

This solution is tailored for three distinct audiences:

| For Agents (x402) | For Enterprises | For Retail Users |
|-------------------|-----------------|------------------|
| Programmatic risk queries | API integration | Chain Insights App |
| Pay-per-call via x402 | Compliance tools | Credit-based access |
| Real-time scoring | Custom analytics | Visualize flow patterns |

### Three Core Capabilities

**1. Risk Scoring**
Enter any address to get an instant risk assessment. Understand *why* an address is flagged and check your own wallets before interacting with exchanges.

**2. Funds Tracking**
Trace money across multiple hops and chains. The system creates interactive graph visualisations of flow topology, revealing ultimate destinations (exchanges, mixers, high-risk services).

**3. AI Investigator Chat**
Use natural language queries to investigate blockchain activity (e.g., "Show me all addresses connected to this hack"). This feature can generate court-admissible investigation reports.

### Flexible Access Model

**Chain Insights Application**
A consumer-facing web application offering tiered access for casual users and power users.
*   **Flexible Credit System:** Users purchase credits using crypto.
*   **Pay-Per-Use:** Credits are spent only on specific queries, tracking actions, or chat interactions.
*   **Community Benefit:** Free access for the Bittensor community during beta.

**Enterprise API**
Direct API integration for exchanges, wallets, and compliance platforms requiring bulk queries, SLAs, and dedicated support.

**x402 Agent Gateway**
An AI-native payment interface enabling autonomous agents to query risk intelligence. No accounts, just pay-per-query micropayments. A DeFi protocol can check counterparty risk before a swap, or a trading bot can avoid tainted addresses.

---

## Architecture

### Design Philosophy

> *"We don't need miners for mere execution. We need miners for breakthroughs."*

Chain Insights separates infrastructure from innovation:

- **Subnet Owner** operates core indexing infrastructure, ensuring a reliable "source of truth" across supported blockchains.
- **Miners** compete to provide intelligence improvements—better algorithms, superior models, validated labels.

This separation allows miners to focus entirely on advancing capabilities (Research & Data Science) rather than maintaining servers.

### Core Indexing Service

The foundation layer provides:

- **Unified Data Model:** Assets converted to USD value, enabling cross-chain analysis.
- **Aggregated Money Flows:** Focus on value relationships ("Flows") rather than raw transactions—resulting in smaller storage needs and faster queries.
- **Rich Feature Sets:** Pre-calculated ML features per address.
- **Multi-Chain Support:** Architecture compatible with Substrate, EVM, and UTXO chains.

### Four Mechanisms of Intelligence

**Analytics Mechanism**
Miners submit optimised code for graph algorithms and pattern detection. Submissions are benchmarked against Chain Synthetics test data.
*   *Participants:* Software engineers, algorithm researchers.
*   *Output:* Production-ready fraud detection (mixers, layering, peel chains).

**Labelling Mechanism**
Miners discover and verify address labels with cryptographic evidence (OSINT, public attributions).
*   *Participants:* OSINT specialists, data hunters.
*   *Output:* Verified database of exchange wallets, sanctioned addresses, known scams.

**Machine Learning Mechanism**
Miners train risk scoring models using features from the indexing service and labels from the labelling mechanism.
*   *Participants:* Data scientists, ML engineers.
*   *Output:* Real-time risk scores for any address.

**Intelligence Mechanism**
Miners fine-tune LLMs for AML, forensics, and investigative queries.
*   *Participants:* AI engineers, LLM specialists.
*   *Output:* AI Investigator powering the Chat interface.

### Chain Synthetics: Objective Benchmarking

A critical challenge in fraud detection is measuring accuracy—there is no public "ground truth" dataset of labelled fraudulent activity. **Chain Synthetics** solves this by:

- **Injecting Synthetic Patterns:** Known topologies (mixers, layering) are injected into real data.
- **Historical Replay:** Recreating famous hacks (Mt. Gox, Ronin, FTX) on any chain.
- **Objective Scoring:** Submissions are judged on precision, recall, and speed—no subjective bias.

---

## How Miners Are Validated

Each mechanism uses objective, gaming-resistant validation tailored to its contribution type:

### Analytics & Machine Learning Mechanisms

Both mechanisms leverage the **Chain Synthetics Framework**:
1.  **Blind Evaluation:** Miners submit code/models without knowing which transactions are synthetic.
2.  **Objective Scoring:** Precision, recall, speed, and novelty.
3.  **Anti-Gaming:** Test datasets regenerate each round; parameters are randomized; holdout patterns remain hidden.
4.  **Temporal Validation (ML):** Predictions validated over time ($T + \tau$) to ensure real-world accuracy.

### Labelling Mechanism

Validated through **evidence-based verification**:
1.  Miners submit labels with cryptographic evidence.
2.  Validators verify the address exists and matches the claimed behaviour against the indexing service.
3.  Scoring based on Quality, Quantity, Novelty, and Long-term accuracy.

### Intelligence Mechanism (LLM)

Validated through **Golden Dataset evaluation**:
1.  Models tested against complex investigative queries.
2.  Scored on query accuracy, graph integration capability, and report quality.

---

## Token Economics

### Revenue Model

Chain Insights generates revenue through five complementary streams:

| Revenue Stream | Description |
|----------------|-------------|
| **Chain Insights Credits** | Purchase credits for risk scoring, tracking, & chat |
| **x402 Agent Gateway** | Pay-per-query micropayments from AI agents |
| **Enterprise API Licenses** | Bulk queries, SLAs, and dedicated support |
| **Address Label Datasets** | Licensing verified address attributions to exchanges & compliance providers |
| **Investigation Reports** | Premium court-admissible forensic reports |

**Value Distribution:**
Revenue flows into Subnet Operations, $ALPHA Buybacks (creating demand pressure), and a Development Fund for R&D and expansion.

**Why Address Labels Matter:**
Verified address datasets are extremely valuable and difficult to source. Exchanges and compliance providers need accurate attributions. Chain Insights creates this as a byproduct of the Labelling Mechanism—monetizing miner innovation.

---

## Roadmap

### Phase 1 (Now — Q4 2025)
*   ✅ Core Indexing Service (Bittensor)
*   ✅ Analytics Pipeline baseline
*   ✅ Chain Synthetics framework
*   🔄 Analytics Mechanism subnet implementation
*   🔄 Chain Insights Miners Leaderboards

### Phase 2 (Q1 2026)
*   Subnet API Launch
*   Labelling Mechanism subnet
*   **Chain Insights Funds Tracking** (Public Release)
*   **Chain Insights Labels** integration
*   Bittensor EVM support

### Phase 3 (Q2 — Q3 2026)
*   Machine Learning Mechanism subnet
*   Chain Insights Risk Scoring (Full release)

### Phase 4 (Q4 2026+)
*   Intelligence Mechanism subnet
*   **Chain Insights Chat** (AI Investigator)

### Beyond
*   Multi-chain expansion (UTXO, Substrate, EVM ecosystems)
*   Enterprise partnerships
*   Regulatory compliance integrations

---

## Team

### Founder
**Kamil Wojciechowski (aphex5)**
Creator of Chain Insights SN15, the original blockchain intelligence subnet on Bittensor. Following SN15, Kamil invested 1.5 years in deep R&D, redesigning the architecture from first principles.
*Role: Full-stack subnet architect (indexing, analytics, ML, mechanics).*

### Partners
**1-HORIZON LTD — Infrastructure Partner**
*   Scalable cloud infrastructure for indexing and validation.
*   DevSecOps/AIOps with 4 decades of expertise.
*   Confidential Computing (TDX/SGX) for TEE.
*   Active Bittensor Miner.

**U1CORE — Development Partner**
*   Chain Insights application development (UI/UX, backend).
*   Enterprise-grade frontend expertise.

---

## Why Bittensor?

Chain Insights launches on Bittensor for specific strategic advantages:

1.  **Community First:** Bittensor users become natural beta testers and evangelists.
2.  **Prove the Model:** We validate the unified data model on a manageable dataset before multi-chain expansion.
3.  **Aligned Incentives:** Miners are rewarded for **innovation**, not just infrastructure provision.
4.  **Path to Production:** The best contributions are automatically deployed to the live environment.

---

**Chain Insights Subnet**
*Powered by Chainswarm Technology*

Founder: Kamil Wojciechowski (aphex5)
GitHub: github.com/chainswarm

*Neutral intelligence for a decentralised world.*
