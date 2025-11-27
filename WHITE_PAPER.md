# Chain Insights Subnet — White Paper

**Decentralised Blockchain Intelligence for the Agentic Economy**

*Powered by Chainswarm Technology*

Version 1.0 | 2025

---

## Table of Contents

1. [Abstract](#1-abstract)
2. [Introduction](#2-introduction)
3. [Problem Statement](#3-problem-statement)
4. [Solution Overview](#4-solution-overview)
5. [Architecture](#5-architecture)
6. [Mechanisms of Intelligence](#6-mechanisms-of-intelligence)
7. [Chain Synthetics Framework](#7-chain-synthetics-framework)
8. [Chain Insights Application](#8-chain-insights-application)
9. [x402 Agent Gateway](#9-x402-agent-gateway)
10. [Token Economics](#10-token-economics)
11. [Use Cases](#11-use-cases)
12. [Roadmap](#12-roadmap)
13. [Team & Partners](#13-team--partners)
14. [Conclusion](#14-conclusion)

---

## 1. Abstract

Chain Insights Subnet is a decentralised blockchain intelligence network built on Bittensor that provides real-time risk scoring, fraud detection, and investigative AI capabilities for the emerging agentic economy. The subnet introduces a novel architecture that separates infrastructure operations from intelligence innovation: the subnet owner maintains reliable core indexing services, while miners compete in tournaments to advance algorithms, train superior machine learning models, discover validated address labels, and fine-tune specialised large language models.

This paper describes the technical architecture, incentive mechanisms, and product ecosystem that positions Chain Insights as the neutral intelligence layer for autonomous agents, enterprises, and retail users requiring blockchain risk assessment. By rewarding breakthroughs rather than mere computation, Chain Insights aligns economic incentives with the continuous advancement of the state of the art in blockchain forensics and anti-money laundering detection.

---

## 2. Introduction

### 2.1 The Agentic Economy

The cryptocurrency ecosystem is undergoing a fundamental transformation. Autonomous AI agents are emerging as economic actors—executing trades, managing portfolios, interacting with DeFi protocols, and making real-time decisions without human intervention. These agents require infrastructure that matches their operational model: programmatic, real-time, and pay-per-use.

When an autonomous agent prepares to execute a transaction, it needs to answer a critical question: *Is this counterparty safe?* Current blockchain intelligence solutions, designed for human compliance officers reviewing quarterly reports, cannot serve this need. The agentic economy demands an intelligence infrastructure built for machines.

### 2.2 The Intelligence Gap

Blockchain intelligence today is characterised by centralisation, high cost, and limited accessibility:

- **Centralised providers** (Chainalysis, Elliptic, TRM Labs) serve enterprise clients at premium prices
- **No programmatic access** suitable for autonomous agents or real-time applications
- **Retail users excluded** from understanding their own risk profiles
- **Closed innovation** where improvements happen behind proprietary walls

Chain Insights Subnet addresses these gaps by building an open, decentralised intelligence network that incentivises innovation, democratises access, and maintains neutrality.

### 2.3 Design Philosophy

> *"Computation is cheap; innovation is priceless. Anyone can deploy servers to run established code—we don't need miners for mere execution. We need miners for breakthroughs, for pushing boundaries, for advancing the state of the art. This subnet rewards those who build the future, not those who replicate the present."*

This philosophy shapes every architectural decision. Miners are not infrastructure providers—they are researchers, data scientists, and AI engineers competing to improve intelligence capabilities. The subnet owner operates stable infrastructure so miners can focus entirely on innovation.

---

## 3. Problem Statement

### 3.1 Accessibility Crisis

The blockchain intelligence market serves a narrow customer base. Enterprise compliance teams at major exchanges can afford contracts costing $50,000+ annually. Everyone else—retail users, small projects, developers, autonomous agents—has no access.

Consider a common scenario: a retail user is banned from a centralised exchange. They receive no explanation, no recourse, and no way to understand what triggered the decision. Their address may have interacted with a flagged entity three hops away in a transaction graph they never knew existed. Without access to the same intelligence tools the exchange uses, they cannot understand, dispute, or remediate the issue.

This asymmetry benefits no one. Users lose access to financial services. Exchanges face customer service burden and potential legal challenges. The ecosystem loses trust.

### 3.2 The Agent Integration Problem

Autonomous AI agents represent the fastest-growing category of blockchain users. These agents need to make risk decisions in milliseconds:

- Should this DeFi protocol accept a deposit from this address?
- Should this wallet alert the user about this recipient?
- Should this trading bot interact with this liquidity pool?
- Do you think this compliance agent should flag this transaction for review?

Current intelligence providers offer no solution for these use cases. Their APIs are designed for batch processing and human review, not real-time autonomous decision-making. The x402 payment protocol enables a new model—pay-per-query micropayments that match the operational reality of autonomous agents—but no intelligence provider has built for this paradigm.

### 3.3 Innovation Stagnation

Centralised intelligence providers innovate on their own timelines. Algorithm improvements, new pattern detection capabilities, and model updates happen behind closed doors. The broader ecosystem cannot contribute to these advances, verify their accuracy, or benefit from collective intelligence.

This is particularly problematic for an adversarial domain. Money launderers, hackers, and fraudsters continuously evolve their techniques. A centralised provider with a small internal research team cannot match the innovation capacity of a decentralised network of incentivised researchers.

### 3.4 Regulatory Expansion

Global cryptocurrency regulation is accelerating:

- **European Union:** Markets in Crypto-Assets (MiCA) framework requires comprehensive compliance
- **United States:** FinCEN Travel Rule extends reporting requirements
- **Global:** FATF recommendations drive KYC/AML requirements worldwide

Every exchange, wallet, DeFi protocol, and crypto service will require compliance tooling. The market for blockchain intelligence is expanding, not contracting. The question is whether this market will be served by centralised gatekeepers or open infrastructure.

---

## 4. Solution Overview

### 4.1 Neutral Intelligence Layer

Chain Insights Subnet provides a **neutral intelligence layer** for blockchain ecosystems. We do not decide who is good or bad—we provide intelligence. Users, applications, and agents choose how to act on that intelligence.

This neutrality is not moral relativism. It is recognition that blockchain intelligence is a dual-use capability:

- **Compliance teams** identify high-risk counterparties to meet regulatory requirements
- **Investigators** trace stolen funds through complex laundering chains
- **Privacy advocates** audit their own transaction graph to understand exposure
- **Researchers** study money flow patterns for academic purposes
- **Users** check addresses before interacting to protect themselves

A neutral tool serves all these use cases. A tool that pre-judges would serve none of them well.

### 4.2 Three Access Channels

Chain Insights delivers intelligence through three complementary channels:

**Chain Insights Application**
A consumer-facing web application providing:

- Risk scoring for any address with explainable factors
- AI-powered chat interface for investigative queries
- Investigation report generation
- Credit-based pricing accessible to individuals and small teams

**Enterprise API**
Direct integration for organisations requiring:

- Bulk query capabilities
- Custom analytics and reporting
- Service level agreements
- Dedicated support

**x402 Agent Gateway**
AI-native payment interface enabling:

- Pay-per-query micropayments
- No accounts or subscriptions required
- Real-time response for autonomous decision-making
- Programmatic access for any agent or application

### 4.3 Decentralised Innovation

Chain Insights separates two functions that are often conflated:

**Infrastructure (Subnet Owner)**

- Operates core indexing services across supported blockchains
- Maintains the "source of truth" data layer
- Ensures production stability and reliability
- Deploys winning innovations to production

**Intelligence (Miners)**

- Compete to improve detection algorithms
- Train superior machine learning models
- Discover and verify address labels
- Fine-tune specialised language models

This separation allows miners to focus entirely on innovation. They do not need to maintain servers, sync blockchains, or worry about uptime. They submit breakthroughs, and breakthroughs are rewarded.

---

## 5. Architecture

### 5.1 System Overview

```
┌─────────────────────────────────────────────────────────────────┐
│                      ACCESS LAYER                                │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐  │
│  │  Chain Insights │  │  Enterprise     │  │  x402 Agent     │  │
│  │  Application    │  │  API            │  │  Gateway        │  │
│  └────────┬────────┘  └────────┬────────┘  └────────┬────────┘  │
└───────────┼────────────────────┼────────────────────┼───────────┘
            │                    │                    │
            └────────────────────┼────────────────────┘
                                 │
                                 ▼
┌─────────────────────────────────────────────────────────────────┐
│                   INTELLIGENCE LAYER                             │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐              │
│  │  Analytics  │  │  Machine    │  │ Intelligence│              │
│  │  Mechanism  │  │  Learning   │  │  Mechanism  │              │
│  │             │  │  Mechanism  │  │  (LLM)      │              │
│  └─────────────┘  └─────────────┘  └─────────────┘              │
│                          │                                       │
│              ┌───────────┴───────────┐                          │
│              │  Labelling Mechanism  │                          │
│              └───────────────────────┘                          │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│                   FOUNDATION LAYER                               │
│              ┌───────────────────────┐                          │
│              │  Core Indexing        │                          │
│              │  Service              │                          │
│              │  (Subnet Owner)       │                          │
│              └───────────────────────┘                          │
│                          │                                       │
│     ┌────────────────────┼────────────────────┐                 │
│     ▼                    ▼                    ▼                 │
│ ┌────────┐          ┌────────┐          ┌────────┐             │
│ │Substrate│         │  EVM   │          │  UTXO  │             │
│ │ Chains │          │ Chains │          │ Chains │             │
│ └────────┘          └────────┘          └────────┘             │
└─────────────────────────────────────────────────────────────────┘
```

### 5.2 Core Indexing Service

The subnet owner operates the Core Indexing Service to provide reliable, consistent data across all mechanisms. This is not a mining opportunity—it is foundational infrastructure that ensures all miners work from the same verified dataset.

#### 5.2.1 Unified Data Model

Traditional blockchain indexing stores every transaction in chain-specific schemas. This approach creates massive storage requirements, slow queries, and incompatible data across chains.

Chain Insights uses a **unified, value-oriented data model**:

| Traditional Approach | Chain Insights Approach |
|---------------------|------------------------|
| Store every transaction | Aggregate money flows |
| Chain-specific schemas | Unified USD-value model |
| Massive storage needs | Compressed representation |
| Focus on transactions | Focus on relationships |
| Currency-specific analysis | Value-normalized analysis |

**Key Principles:**

- **USD Value Normalisation:** All asset transfers converted to USD value at time of transaction, enabling cross-asset and cross-chain analysis without currency complexity
- **Aggregated Money Flows:** Instead of storing individual transactions, the model aggregates flows between address pairs—capturing the relationship rather than every event
- **Address-Centric Features:** Rich pre-calculated features per address, including volume metrics, counterparty analysis, temporal patterns, and graph properties

This model is:

- **Smaller:** Aggregated flows require less storage than raw transactions
- **Faster:** Queries operate on relationships, not event logs
- **Portable:** Same model applies across Substrate, EVM, and UTXO chains
- **Analytical:** Designed for ML and pattern detection, not just retrieval

#### 5.2.2 Multi-Chain Architecture

The indexing service maintains blueprints for three blockchain paradigms:

**Substrate Chains**
Account-based model with native support for Bittensor, Torus, and the Polkadot ecosystem. The initial deployment focuses on the Bittensor and Torus networks.

**EVM Chains**
Support for Ethereum-compatible networks, including Bittensor EVM and Torus EVM layers, with blueprints ready for broader EVM ecosystem expansion.

**UTXO Chains**
Support for Bitcoin-style unspent transaction output models, enabling analysis of Bitcoin and derivative networks.

The unified data model means that adding a new chain requires only implementing an indexer—not redesigning analytics, ML, or intelligence mechanisms.

#### 5.2.3 Data Distribution

To ensure transparency and enable miner participation:

- **Snapshot Distribution:** Regular data snapshots allow anyone to verify data without running a full sync
- **Feature Export:** Pre-calculated ML features available for miner model training
- **Graph Access:** Transaction graph data accessible for pattern detection development

### 5.3 Semi-Real-Time Processing

The system operates with approximately one-hour delay from on-chain events to indexed, analysed data. This semi-real-time approach balances:

- **Timeliness:** Sufficient for compliance, risk scoring, and most operational use cases
- **Reliability:** Time buffer ensures data consistency and processing stability
- **Cost Efficiency:** Avoids the infrastructure overhead of true real-time streaming

For use cases requiring faster response, the architecture supports prioritised processing paths.

---

## 6. Mechanisms of Intelligence

Chain Insights Subnet comprises four interoperable mechanisms, each targeting a different aspect of blockchain intelligence and attracting different miner profiles.

### 6.1 Analytics Mechanism

#### Purpose

Advance the state of the art in on-chain transaction pattern detection and graph algorithm optimisation.

#### Participants

Software engineers and algorithm researchers who:

- Optimise graph algorithms (PageRank, Betweenness Centrality, Community Detection)
- Develop pattern detection for complex topologies (layering networks, circular flows, obfuscation chains, and many more...)
- Improve processing efficiency for large-scale datasets
- Implement high-performance code (Rust, C++, CUDA)

#### Process

1. **Baseline Publication:** Subnet owner publishes baseline implementations for target algorithms
2. **Code Submission:** Miners submit improved implementations via Docker containers
3. **Benchmark Execution:** Validators run submissions against Chain Synthetics test data
4. **Scoring:** Submissions scored on detection accuracy (precision/recall), processing speed, and novelty
5. **Production Deployment:** Best-performing code adopted by subnet owner for production alerts

#### Incentive Model

Miners earn emissions for improvements over baseline. If a miner improves pattern detection accuracy by 5%, they earn emissions for that innovation period (typically one week). Once the improvement is absorbed into the new baseline, emissions stop. Miners must innovate again to earn again.

This tournament-based model ensures continuous advancement. Unlike some subnets that reward continuous infrastructure provision, Chain Insights rewards breakthroughs.

### 6.2 Labelling Mechanism

#### Purpose

Create a decentralised address intelligence layer by aggregating and verifying labelled addresses from across the internet.

#### Participants

Data hunters and OSINT specialists who discover and verify:

- **Exchange Addresses:** Known hot/cold wallets from centralised exchanges
- **Fraud & Scam Addresses:** Reported ponzi schemes, rug pulls, phishing addresses
- **Sanctioned Entities:** OFAC and other regulatory blacklists
- **Theft Reports:** Addresses involved in hacks, exploits, and stolen funds
- **Public Attributions:** Team wallets, protocol treasuries, known whale addresses

#### Process

1. **Discovery:** Miners identify labelled addresses from public sources
2. **Evidence Collection:** Each label requires cryptographic evidence of source
3. **Verification:** Validators verify that the address exists and matches the claimed behaviour againstthe  indexing service
4. **Integration:** Verified labels integrated into the production intelligence layer

#### Incentive Model

Labelling mechanism rewards both quality and quantity:

- **Quality:** Labels that prove accurate over time earn higher scores
- **Quantity:** Comprehensive coverage across address categories
- **Novelty:** Previously unknown labels earn a premium
- **Verification:** Labels that withstand challenge and re-verification

### 6.3 Machine Learning Mechanism

#### Purpose

Train and deploy the most accurate risk scoring models for address classification and behaviour prediction.

#### Participants

Data scientists and ML engineers who:

- Train classification models (address type, risk category)
- Develop prediction models (future behaviour, token movement likelihood)
- Optimise model architectures for accuracy and inference speed
- Create ensemble approaches combining multiple signals

#### Process

1. **Data Access:** Miners access features from the indexing service and labels from the labelling mechanism
2. **Training:** Offline model training using historical data and ground truth labels
3. **Submission:** Miners submit model containers/weights for evaluation
4. **Evaluation:** Models validated against Chain Synthetics ground truth
5. **Temporal Validation:** Predictions validated over time ($T + \tau$) to measure real-world accuracy
6. **A/B Testing:** Candidate models tested against production for drift detection
7. **Deployment:** Best-performing model becomes production "Oracle" for risk scoring

#### Scoring Dimensions

- **Fraud Detection:** Alert candidate identification → scoring → confirmed alert accuracy
- **Address Classification:** Correct categorization of address types
- **Proximity Risk:** Accurate assessment of contamination from related addresses
- **Calibration:** Predicted probabilities match observed frequencies

#### Incentive Model

Similar to Analytics Mechanism—tournament-based emissions for models that exceed current production performance. New submissions continuously challenge models.

### 6.4 Intelligence Mechanism

#### Purpose

Fine-tune and provide large language models capable of understanding blockchain forensics, AML concepts, and Chain Insights data structures.

#### Participants

AI engineers and LLM specialists who:

- Fine-tune open-weights models (Llama, Mistral, etc.) on domain-specific data
- Create training datasets for blockchain/AML terminology
- Integrate knowledge graph capabilities (GraphRAG)
- Optimise models for investigative report generation

#### Process

1. **Base Model Selection:** Miners choose open-weights foundation models
2. **Dataset Curation:** Create domain-specific training data (terminology, scenarios, report formats)
3. **Fine-Tuning:** Train specialised models for the blockchain intelligence domain
4. **Evaluation:** Models tested against the "Golden Dataset" of complex queries and investigation scenarios
5. **Integration Testing:** Validate the model can query the Chain Insights knowledge graph
6. **Deployment:** Winning model powers Chain Insights Chat interface

#### Capabilities

Fine-tuned models should demonstrate:

- **Terminology Understanding:** "Structuring," "peeling chain," "mixer," "layering"
- **Regulatory Context:** KYC/AML requirements, FATF guidelines, jurisdiction-specific rules
- **Data Structure Familiarity:** Query Chain Insights APIs, interpret risk scores, navigate graph data
- **Report Generation:** Create clear, court-admissible investigation narratives

---

## 7. Chain Synthetics Framework

### 7.1 The Ground Truth Problem

Measuring fraud detection accuracy requires ground truth—known examples of fraudulent activity with verified labels. This creates a fundamental challenge:

- Real fraud labels are sensitive and not publicly available
- Historical hacks are documented but not structured for benchmarking
- Synthetic data may not reflect real-world complexity
- Miners could overfit to known test cases

Chain Synthetics solves this through a novel approach to benchmark generation.

### 7.2 Architecture

Chain Synthetics generates test data by **injecting synthetic patterns into real blockchain data**. This is critically important: synthetic patterns are blurred and merged with existing transactions so they appear natural within the transaction graph. This blending directly impacts algorithm design quality—solutions that work only on isolated synthetic data will fail when patterns are embedded in realistic network structures.

#### Pattern Injection

Known fraud topologies are parameterised and injected:

- **Mixing Patterns:** Multi-input, multi-output transactions obscuring fund origin
- **Layering Networks:** Multiple intermediate addresses between source and destination
- **Peel Chains:** Sequential transactions peeling small amounts to the final destination
- **Circular Flows:** Funds returning to origin through complex paths
- **And many more:** Continuously expanding library of fraud topologies

Each pattern is configured with:

- Scale (number of addresses, transaction count)
- Timing (spread across time vs. concentrated)
- Value distribution (uniform vs. varied amounts)
- Blending parameters (how naturally it integrates with surrounding activity)

#### Historical Replay

Chain Synthetics can recreate famous hacks and exploits:

- Transaction patterns from documented incidents (Mt. Gox, Ronin Bridge, FTX, etc.)
- Adapted to any supported blockchain network
- Configurable blueprints per blockchain type

This enables testing whether detection algorithms would have caught historical incidents.

### 7.3 Benchmark Execution

During miner evaluation:

1. **Dataset Generation:** Chain Synthetics produces a test dataset with injected patterns
2. **Blind Evaluation:** Miners do not know which transactions are synthetic
3. **Submission Execution:** Miner code runs against test dataset
4. **Scoring:** Results compared against ground truth labels

#### Metrics

- **Precision:** What fraction of flagged patterns are actually fraudulent?
- **Recall:** What fraction of actual fraud patterns were detected?
- **Speed:** Processing time for dataset analysis
- **Novelty:** Detection of patterns not in the training distribution

### 7.4 Anti-Gaming Measures

To prevent overfitting:

- Test datasets regenerated for each evaluation round
- Pattern parameters randomised within realistic ranges
- Multiple pattern types combined in a single dataset
- Holdout patterns not revealed until post-evaluation

---

## 8. Chain Insights Application

### 8.1 Overview

Chain Insights is the consumer-facing application delivering subnet intelligence to end users. It provides accessible interfaces for risk scoring, investigation, and AI-powered analysis.

### 8.2 Risk Scoring

#### Functionality

- Enter any blockchain address
- Receive a comprehensive risk assessment
- View explainable factors contributing to the score
- Understand connections to flagged entities
- Track score changes over time

#### Explainability

Risk scores include factor breakdown:

- Direct exposure to known bad actors
- Proximity to flagged addresses (graph distance)
- Behavioural pattern matches
- Volume and timing anomalies
- Historical incident associations

Users can understand *why* an address is flagged, not just that it is flagged.

### 8.3 AI Investigator Chat

#### Functionality

Natural language interface for complex queries:

- "Show me all addresses that received funds from this hack"
- "Explain the relationship between these two addresses"
- "What is the risk profile of this wallet's counterparties?"
- "Generate an investigation report for this address"

#### Capabilities

- Query Chain Insights knowledge graph through conversation
- Synthesise complex multi-hop relationships
- Generate structured investigation reports
- Explain technical concepts in an accessible language

### 8.4 Pricing Model

**Credit-Based Access**

- 1,000 credits = 10 USDT
- 1 credit = 1 address risk score query
- Chat usage calculated per interaction (based on complexity and compute)
- Credits never expire

**Beta Period**
During the initial launch, Bittensor community members receive free access to build familiarity and provide feedback.

---

## 9. x402 Agent Gateway

### 9.1 The Agent Payment Problem

Autonomous AI agents face a fundamental challenge when accessing paid services: traditional payment models assume human users with accounts, subscriptions, and manual payment authorisation.

Agents need:

- **No accounts:** Agents should not need to pre-register
- **No subscriptions:** Pay only for what is used
- **Micropayments:** Individual queries may cost fractions of a cent
- **Programmatic:** Payment authorisation without human intervention
- **Real-time:** No delays for payment processing

### 9.2 x402 Protocol Integration

The x402 protocol enables HTTP-native payments. Chain Insights integrates x402 to provide agent-accessible intelligence:

```
┌─────────────────┐         ┌─────────────────┐
│   AI Agent      │         │  Chain Insights │
│                 │         │  x402 Gateway   │
└────────┬────────┘         └────────┬────────┘
         │                           │
         │  1. Request Risk Score    │
         │ ─────────────────────────▶│
         │                           │
         │  2. 402 Payment Required  │
         │ ◀───────────────────────  │
         │     (price, payment addr) │
         │                           │
         │  3. Payment + Request     │
         │ ─────────────────────────▶│
         │                           │
         │  4. Risk Score Response   │
         │ ◀─────────────────────────│
         │                           │
```

### 9.3 Use Cases

**DeFi Protocol Integration**
A lending protocol queries the address risk before accepting deposits. High-risk addresses trigger additional verification or rejection.

**Wallet Safety Warnings**
A wallet application checks recipient addresses before signing a transaction. Users receive warnings about suspicious destinations.

**Trading Bot Risk Management**
An automated trading system avoids interacting with flagged addresses or contaminated liquidity pools.

**Compliance Automation**
A compliance agent monitors portfolio exposure and automatically flags when counterparty risk exceeds thresholds.

**Cross-Protocol Coordination**
Multiple agents share intelligence through Chain Insights, a common infrastructure that builds collective awareness.

### 9.4 Pricing

Agent gateway pricing mirrors credit-based pricing:

- Pay-per-query based on query type and complexity
- Micropayment-compatible (fractions of a cent per query for basic lookups)
- Volume discounts for high-frequency users
- No minimum commitments

---

## 10. Token Economics

### 10.1 Value Flow Architecture

Chain Insights creates sustainable value flow connecting revenue generation to network incentives:

```
┌─────────────────────────────────────────────────────────────────┐
│                     REVENUE SOURCES                              │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐  │
│  │ Chain Insights  │  │  x402 Agent     │  │  Enterprise     │  │
│  │ Credits         │  │  Payments       │  │  Licenses       │  │
│  └────────┬────────┘  └────────┬────────┘  └────────┬────────┘  │
└───────────┼────────────────────┼────────────────────┼───────────┘
            └────────────────────┼────────────────────┘
                                 │
                                 ▼
┌─────────────────────────────────────────────────────────────────┐
│                   VALUE DISTRIBUTION                             │
│                                                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │                 Subnet Operations                        │    │
│  │  Infrastructure • Development • Support                  │    │
│  └─────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │              Alpha Token Buybacks                        │    │
│  │  Revenue-funded purchases supporting token value         │    │
│  └─────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │               Development Fund                           │    │
│  │  Continued R&D • Multi-chain expansion • Partnerships    │    │
│  └─────────────────────────────────────────────────────────┘    │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

### 10.2 Miner Incentives

Miners earn subnet alpha token emissions for validated contributions:

**Analytics Mechanism**

- Emissions for code that exceeds baseline benchmarks
- Tournament-based: earn during the innovation period, then must improve again
- Winning code is open-sourced and deployed to production

**Labelling Mechanism**

- Emissions based on the quality and quantity of verified labels
- Quality is measured by long-term accuracy and resistance to challenges
- Novelty premium for previously unknown attributions

**Machine Learning Mechanism**

- Emissions for models exceeding production performance
- Temporal validation ensures real-world accuracy, not just test set performance
- Continuous challenge from new submissions

**Intelligence Mechanism**

- Emissions for LLMs scoring highest on investigation benchmarks
- Evaluated on the golden dataset of complex queries
- Integration testing with Chain Insights knowledge graph

### 10.3 Open Source Commitment

All winning miner contributions are open-sourced:

- Detection algorithms published for community benefit
- Model architectures and training approaches documented
- Collective intelligence benefits the entire ecosystem

Miners are compensated for innovation through emissions; the ecosystem benefits from open knowledge.

### 10.4 Buyback Mechanism

Revenue from Chain Insights application and x402 gateway funds token buybacks:

- Creates demand pressure supporting token value
- Aligns subnet owner incentives with token holders
- Sustainable model tied to actual usage and revenue

---

## 11. Use Cases

### 11.1 Exchange Compliance

**Scenario:** A centralised exchange needs to screen deposits and withdrawals for AML compliance.

**Solution:**

- Integrate Chain Insights Enterprise API
- Automatic risk scoring for all incoming deposits
- Flag high-risk transactions for manual review
- Generate audit trails for regulatory reporting

**Value:** Automated compliance reduces manual review burden while meeting regulatory requirements.

### 11.2 DeFi Protocol Security

**Scenario:** A lending protocol wants to prevent interaction with stolen funds or sanctioned addresses.

**Solution:**

- Integrate the x402 gateway for real-time queries
- Check depositor addresses before accepting collateral
- Monitor borrower addresses for risk changes
- Automated alerts when counterparty risk increases

**Value:** Protocol protection without manual intervention, suitable for fully autonomous operation.

### 11.3 Hack Investigation

**Scenario:** A protocol suffers an exploit and needs to trace stolen funds.

**Solution:**

- Use the Chain Insights application to analyse attacker addresses
- AI chat interface to explore the transaction graph
- Generate an investigation report documenting the fund flow
- Identify exchange deposits for potential recovery

**Value:** Rapid investigation capability without specialised forensics expertise.

### 11.4 Personal Risk Assessment

**Scenario:** A user is blocked from an exchange and wants to understand why.

**Solution:**

- Check one's own address risk score in the Chain Insights application
- Review explainable factors identifying risk sources
- Understand which counterparty interactions caused contamination
- Take informed action to address or dispute the flag

**Value:** Transparency and recourse for users facing opaque compliance decisions.

### 11.5 Autonomous Agent Risk Management

**Scenario:** An AI trading agent needs to avoid contaminated addresses while maximising returns.

**Solution:**

- Query the x402 gateway before each transaction
- Integrate risk scores into trading decision logic
- Automatically exclude high-risk counterparties
- Log all risk checks for audit purposes

**Value:** Autonomous risk management enabling compliant automated trading.

### 11.6 Privacy Audit

**Scenario:** A privacy-conscious user wants to understand their transaction graph exposure.

**Solution:**

- Analyse own addresses in Chain Insights
- Map connections to known entities
- Identify potential deanonymization vectors
- Make informed decisions about future transaction patterns

**Value:** Empowered privacy management through transparency.

---

## 12. Roadmap

### Phase 1: Foundation (Q4 2025)

**Completed**

- ✅ Core Indexing Service operational for Bittensor and Torus networks
- ✅ Analytics Pipeline baseline implementation
- ✅ Chain Synthetics benchmarking framework

**In Progress**

- 🔄 Analytics Mechanism subnet implementation
- 🔄 Benchmarking system for miner evaluation
- 🔄 Chain Insights Risk Scoring beta (free for Bittensor community)

**Deliverables**

- Functional subnet with Analytics Mechanism
- Public beta of the Chain Insights application
- Initial miner participation and tournament cycles

### Phase 2: Intelligence Expansion (Q1 2026)

**Planned**

- Machine Learning Mechanism launch
- Chain Insights public release with credit system
- Bittensor EVM support
- Torus EVM support
- ML Mechanism leaderboard in Chain Insights

**Deliverables**

- Production risk scoring powered by miner-trained models
- EVM transaction analysis capability
- Revenue generation begins

### Phase 3: Full Intelligence Stack (Q2 2026)

**Planned**

- Labelling Mechanism launch
- Intelligence Mechanism (LLM) launch
- Chain Insights AI Chat interface
- Labelling Mechanism leaderboard

**Deliverables**

- Comprehensive address intelligence from decentralised labelling
- AI investigator chat powered by fine-tuned models
- Complete the intelligence stack operational

### Phase 4: Scale (2026 and Beyond)

**Planned**

- Multi-chain expansion: UTXO chains (Bitcoin ecosystem)
- Additional Substrate chains (Polkadot ecosystem)
- Broader EVM ecosystem coverage
- Enterprise partnership program
- Regulatory compliance integrations
- x402 Agent Gateway public launch

**Vision**
Chain Insights becomes the default intelligence layer for the agentic economy—any agent, any chain, any query, paid for in real time.

---

## 13. Team & Partners

### 13.1 Founder

**Kamil Wojciechowski (aphex5)**

Creator of Chain Insights SN15, the original blockchain intelligence subnet on Bittensor. Following SN15's operation, Kamil invested 1.5 years in deep research and architectural redesign, rebuilding the system from first principles.

This extensive R&D period addressed fundamental questions:

- How should infrastructure and innovation be separated?
- What incentive models drive continuous advancement rather than stagnation?
- How can fraud detection be objectively measured?
- What data model enables cross-chain analysis at scale?

The answers to these questions shaped Chain Insights Subnet's architecture.

**Responsibilities:**

- Indexing infrastructure design and operation
- Subnet mechanics and incentive design
- Overall architecture and technical leadership
- Project management and coordination

### 13.2 Partners

**Hyperclouds — Infrastructure Partner**

- Scalable cloud infrastructure for indexing and validation services
- DevSecOps and AIOps expertise with four decades of combined experience
- Confidential Computing capabilities with TDX/SGX for Trusted Execution Environments
- Active Bittensor miner with deep network understanding

**U1OCORE — Development Partner**

- Chain Insights application development (UI/UX design, frontend implementation)
- Application backend services
- Enterprise-grade development practices
- User experience optimisation

### 13.3 Development Structure

**Core Team (Subnet Owner)**

- Maintains indexing infrastructure
- Operates benchmarking and validation systems
- Deploys winning innovations to production
- Coordinates mechanism development

**Miners (Decentralised Contributors)**

- Software engineers advancing detection algorithms
- Data scientists training ML models
- OSINT specialists discovering address labels
- AI engineers fine-tuning language models

**Application Team (U1OCORE)**

- Chain Insights web application
- User interfaces and experience
- Backend services and integrations

---

## 14. Conclusion

### 14.1 The Opportunity

Blockchain intelligence is at an inflexion point. Regulatory requirements are expanding globally. The agentic economy is emerging rapidly. Current centralised solutions cannot serve the scale, accessibility, and innovation requirements of this new landscape.

Chain Insights Subnet addresses this opportunity by:

**Democratizing Access**

- Credit-based pricing accessible to individuals
- x402 gateway enabling autonomous agent integration
- Free beta access for the Bittensor community

**Maintaining Neutrality**

- Intelligence without judgment
- Tool for compliance, investigation, and privacy audit alike
- Users decide how to act on intelligence

**Accelerating Innovation**

- Tournament-based incentives reward breakthroughs
- Decentralised research community
- Open-source contributions benefit the entire ecosystem

**Building Sustainability**

- Revenue from applications and API
- Token buybacks from operational income
- Aligned incentives across stakeholders

### 14.2 The Vision

Chain Insights becomes the default intelligence layer for the agentic economy.

Any agent, any chain, any query—with real-time risk assessment enabling safe autonomous operation in an increasingly complex blockchain landscape.

We do not predict the future of blockchain compliance and intelligence. We build the infrastructure that makes it possible.

### 14.3 Call to Action

**For Miners:**
Join the innovation competition. Whether you're a software engineer optimizing graph algorithms, a data scientist training ML models, an OSINT specialist discovering address intelligence, or an AI engineer fine-tuning language models—there is a mechanism for your expertise.

**For Users:**
Try Chain Insights during the beta period. Check your addresses. Explore the intelligence. Provide feedback that shapes the product.

**For Builders:**
Integrate the x402 gateway into your agents and applications. Build on a neutral intelligence infrastructure. Join the agentic economy.

**For Validators:**
Support a subnet that rewards innovation over infrastructure. Help build the intelligence layer the ecosystem needs.

---

**Chain Insights Subnet**
*Powered by Chainswarm Technology*

Decentralised blockchain intelligence for the agentic economy.

Founder: Kamil Wojciechowski (aphex5)
GitHub: github.com/chainswarm

*Neutral intelligence for a decentralised world.*

---

*Document Version 1.0 — 2025*
*Chain Insights Subnet — Powered by Chainswarm Technology*
