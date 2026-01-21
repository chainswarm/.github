# Chain Insights Agent — White Paper

**Autonomous Blockchain Intelligence for the Agentic Economy**

*Powered by Chainswarm Technology*

Version 2.0 | 2025

---

## Table of Contents

1. [Abstract](#1-abstract)
2. [Introduction](#2-introduction)
3. [Problem Statement](#3-problem-statement)
4. [Solution Overview](#4-solution-overview)
5. [Architecture](#5-architecture)
6. [Agent Capabilities](#6-agent-capabilities)
7. [Chain Synthetics Framework](#7-chain-synthetics-framework)
8. [Continuous Improvement](#8-continuous-improvement)
9. [Chain Insights Application](#9-chain-insights-application)
10. [x402 Agent Gateway](#10-x402-agent-gateway)
11. [Token Economics](#11-token-economics)
12. [Use Cases](#12-use-cases)
13. [Roadmap](#13-roadmap)
14. [Team & Partners](#14-team--partners)
15. [Conclusion](#15-conclusion)

---

## 1. Abstract

Chain Insights Agent is an autonomous blockchain intelligence system built on Virtuals Protocol that provides real-time risk scoring, funds tracking, and investigative AI capabilities for the emerging agentic economy. The agent operates in two complementary modes: a reactive mode where users ask questions and the agent researches and solves problems, and a proactive mode where the agent autonomously scans the network, warns before threats materialise, and automatically labels risky addresses.

This paper describes the technical architecture, agent capabilities, and product ecosystem that positions Chain Insights as the neutral intelligence layer for autonomous agents, enterprises, and retail users. By employing self-improving AI systems that continuously enhance detection capabilities, Chain Insights stays ahead of evolving threats in blockchain forensics, money flow visualisation, and anti-money laundering detection.

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
- **Static systems** that cannot adapt quickly to evolving threat patterns

Chain Insights Agent addresses these gaps by building an intelligent, self-improving agent that democratises access, maintains neutrality, and continuously evolves its capabilities.

### 2.3 Evolution from Bittensor

Chain Insights originated as SN15 on the Bittensor network, where we pioneered decentralised blockchain intelligence. Through operating a blockchain intelligence subnet, we developed sophisticated methodologies for pattern detection, risk scoring, and continuous system improvement. This experience proved invaluable in understanding how to build truly adaptive intelligence systems.

As the agentic economy emerged, we evolved to Virtuals Protocol, which better aligns with our vision of an autonomous AI agent serving the blockchain intelligence needs of humans and machines alike. The lessons learned from Bittensor—particularly around continuous improvement and objective benchmarking—are now embedded in Chain Insights Agent's core architecture.

### 2.4 Design Philosophy

> *"The best intelligence system is one that improves itself faster than threats evolve. We build agents that learn, adapt, and protect—autonomously."*

This philosophy shapes every architectural decision. Chain Insights Agent is not a static tool—it is a living system that continuously enhances its detection capabilities through self-improving AI loops. The agent operates both reactively (responding to user queries) and proactively (scanning for threats before they materialise).

---

## 3. Problem Statement

### 3.1 Accessibility Crisis

The blockchain intelligence market serves a narrow customer base. Enterprise compliance teams at major exchanges can afford contracts costing substantial annual fees. Everyone else—retail users, small projects, developers, autonomous agents—has no access.

Consider a common scenario: a retail user is banned from a centralised exchange. They receive no explanation, no recourse, and no way to understand what triggered the decision. Their address may have interacted with a flagged entity three hops away in a transaction graph they never knew existed. Without access to the same intelligence tools the exchange uses, they cannot understand, dispute, or remediate the issue.

This asymmetry benefits no one. Users lose access to financial services. Exchanges face customer service burden and potential legal challenges. The ecosystem loses trust.

### 3.2 The Agent Integration Problem

Autonomous AI agents represent the fastest-growing category of blockchain users. These agents need to make risk decisions in milliseconds:

- Should this DeFi protocol accept a deposit from this address?
- Should this wallet alert the user about this recipient?
- Should this trading bot interact with this liquidity pool?
- Should this compliance agent flag this transaction for review?

Current intelligence providers offer no solution for these use cases. Their APIs are designed for batch processing and human review, not real-time autonomous decision-making. The x402 payment protocol enables a new model—pay-per-query micropayments that match the operational reality of autonomous agents—but no intelligence provider has built for this paradigm.

### 3.3 Static Intelligence in a Dynamic Threat Landscape

Centralised intelligence providers update their systems on their own timelines. Algorithm improvements, new pattern detection capabilities, and model updates happen behind closed doors and on slow release cycles.

This is particularly problematic for an adversarial domain. Money launderers, hackers, and fraudsters continuously evolve their techniques. A static system with periodic updates cannot keep pace with rapidly evolving threats. What's needed is an intelligence system that learns and adapts continuously—an agent that improves itself faster than threats evolve.

### 3.4 Regulatory Expansion

Global cryptocurrency regulation is accelerating:

- **European Union:** Markets in Crypto-Assets (MiCA) framework requires comprehensive compliance
- **United States:** FinCEN Travel Rule extends reporting requirements
- **Global:** FATF recommendations drive KYC/AML requirements worldwide

Every exchange, wallet, DeFi protocol, and crypto service will require compliance tooling. The market for blockchain intelligence is expanding, not contracting. The question is whether this market will be served by slow-moving centralised gatekeepers or adaptive, intelligent agents.

---

## 4. Solution Overview

### 4.1 Neutral Intelligence Layer

Chain Insights Agent provides a **neutral intelligence layer** for blockchain ecosystems. We do not decide who is good or bad—we provide intelligence. Users, applications, and agents choose how to act on that intelligence.

This neutrality is not moral relativism. It is recognition that blockchain intelligence is a dual-use capability:

- **Compliance teams** identify high-risk counterparties to meet regulatory requirements
- **Investigators** trace stolen funds through complex laundering chains
- **Privacy advocates** audit their own transaction graph to understand exposure
- **Researchers** study money flow patterns for academic purposes
- **Users** check addresses before interacting to protect themselves

A neutral tool serves all these use cases. A tool that pre-judges would serve none of them well.

### 4.2 Dual Operating Modes

Chain Insights Agent operates in two complementary modes:

**Reactive Mode (ReAct-Style)**
Users ask questions, and the agent researches, analyses, and solves problems:

- "Show me all addresses connected to this hack"
- "Explain the relationship between these two addresses"
- "What is the risk profile of this wallet's counterparties?"
- "Generate an investigation report for this address"

The agent queries its knowledge base, follows transaction trails, synthesises findings, and delivers actionable intelligence.

**Proactive/Autonomous Mode**
The agent continuously scans the network and acts without user prompting:

- **Early Warning System:** Warns before something bad happens—detecting emerging threat patterns and alerting affected users
- **Automatic Threat Labelling:** Detects attack patterns (e.g., dusting attacks) and automatically labels source addresses as risky
- **Pattern Discovery:** Identifies new fraud topologies as they emerge in the wild
- **Continuous Monitoring:** Tracks addresses of interest and alerts on significant changes

### 4.3 Three Access Channels

Chain Insights delivers intelligence through three complementary channels:

**Chain Insights Application**
A consumer-facing web application providing:

- Risk scoring for any address with explainable factors
- Funds Tracking to visualise money flow patterns
- AI-powered chat interface for investigative queries
- Interactive graph visualisations
- Proactive alerts and notifications

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
│                  CHAIN INSIGHTS AGENT                            │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │               AGENT ORCHESTRATION LAYER                  │    │
│  │  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐   │    │
│  │  │   Reactive   │  │  Proactive   │  │   Learning   │   │    │
│  │  │    Mode      │  │    Mode      │  │    Loop      │   │    │
│  │  └──────────────┘  └──────────────┘  └──────────────┘   │    │
│  └─────────────────────────────────────────────────────────┘    │
│                               │                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │               INTELLIGENCE LAYER                         │    │
│  │  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐      │    │
│  │  │  Analytics  │  │  Machine    │  │     AI      │      │    │
│  │  │  Engine     │  │  Learning   │  │ Investigator│      │    │
│  │  │             │  │  Models     │  │    (LLM)    │      │    │
│  │  └─────────────┘  └─────────────┘  └─────────────┘      │    │
│  └─────────────────────────────────────────────────────────┘    │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│                   FOUNDATION LAYER                               │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │            Core Indexing Service                         │    │
│  │        ┌─────────────────────────────┐                   │    │
│  │        │     Label Database          │                   │    │
│  │        │   (External Services +      │                   │    │
│  │        │    Auto-Discovery)          │                   │    │
│  │        └─────────────────────────────┘                   │    │
│  └─────────────────────────────────────────────────────────┘    │
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

The Core Indexing Service provides reliable, consistent data across all intelligence capabilities. This foundational infrastructure ensures the agent works from verified, up-to-date blockchain data.

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

- **USD Value Normalisation:** All asset transfers converted to USD value at time of transaction, enabling cross-asset and cross-chain analysis without currency complexity.
- **Aggregated Money Flows:** Instead of storing individual transactions, the model aggregates flows between address pairs—capturing the relationship rather than every event.
- **Address-Centric Features:** Rich pre-calculated features per address, including volume metrics, counterparty analysis, temporal patterns, and graph properties.

This model is:

- **Smaller:** Aggregated flows require less storage than raw transactions
- **Faster:** Queries operate on relationships, not event logs
- **Portable:** Same model applies across Substrate, EVM, and UTXO chains
- **Analytical:** Designed for ML and pattern detection, not just retrieval

#### 5.2.2 Multi-Chain Architecture

The indexing service maintains blueprints for three blockchain paradigms:

**Substrate Chains**
Account-based model with native support for Polkadot ecosystem networks.

**EVM Chains**
Support for Ethereum-compatible networks, enabling analysis across the EVM ecosystem.

**UTXO Chains**
Support for Bitcoin-style unspent transaction output models, enabling analysis of Bitcoin and derivative networks.

The unified data model means that adding a new chain requires only implementing an indexer—not redesigning analytics, ML, or intelligence mechanisms.

#### 5.2.3 Label Database

Chain Insights maintains a comprehensive database of address attributions:

- **Exchange Addresses:** Known hot/cold wallets from centralised exchanges
- **Fraud & Scam Addresses:** Reported ponzi schemes, rug pulls, phishing addresses
- **Sanctioned Entities:** OFAC and other regulatory blacklists
- **Theft Reports:** Addresses involved in hacks, exploits, and stolen funds
- **Public Attributions:** Team wallets, protocol treasuries, known whale addresses

Labels are sourced from external intelligence services and **automatically discovered** by the agent through its proactive monitoring capabilities.

### 5.3 Semi-Real-Time Processing

The system operates with approximately one-hour delay from on-chain events to indexed, analysed data. This semi-real-time approach balances:

- **Timeliness:** Sufficient for compliance, risk scoring, and most operational use cases
- **Reliability:** Time buffer ensures data consistency and processing stability
- **Cost Efficiency:** Avoids the infrastructure overhead of true real-time streaming

For use cases requiring faster response, the architecture supports prioritised processing paths.

---

## 6. Agent Capabilities

Chain Insights Agent comprises three core intelligence capabilities, each continuously improved through self-learning systems.

### 6.1 Analytics Engine

#### Purpose

Detect complex transaction patterns indicative of money laundering, fraud, or suspicious activity.

#### Capabilities

- **Graph Algorithms:** PageRank, Betweenness Centrality, Community Detection optimised for blockchain transaction graphs
- **Pattern Detection:** Identification of complex topologies including:
  - Mixing patterns (multi-input, multi-output transactions obscuring fund origin)
  - Layering networks (multiple intermediate addresses between source and destination)
  - Peel chains (sequential transactions peeling small amounts to final destination)
  - Circular flows (funds returning to origin through complex paths)
  - And many more fraud topologies
- **High Performance:** Optimised processing for large-scale datasets

#### Continuous Improvement

The Analytics Engine improves itself through agent-driven loops that test new algorithm variations against the Chain Synthetics benchmark framework, automatically adopting improvements that demonstrate superior detection accuracy.

### 6.2 Machine Learning Models

#### Purpose

Provide accurate risk scoring for any blockchain address through trained classification and prediction models.

#### Capabilities

- **Address Classification:** Categorise addresses by type (exchange, DeFi, personal, suspicious)
- **Risk Scoring:** Real-time risk assessment for any address
- **Behaviour Prediction:** Likelihood of future suspicious activity
- **Proximity Risk:** Assessment of contamination from related addresses
- **Calibrated Probabilities:** Predicted probabilities that match observed frequencies

#### Model Architecture

- Ensemble approaches combining multiple signals
- Pre-calculated features from the Core Indexing Service
- Ground truth labels from the Label Database
- Temporal validation to ensure real-world accuracy

#### Continuous Improvement

ML models are continuously refined through automated training loops that:
- Evaluate new model architectures against production performance
- Validate predictions over time to catch overfitting
- A/B test candidate models against current production
- Automatically deploy models that demonstrate improvement

### 6.3 AI Investigator (LLM)

#### Purpose

Enable natural language interaction for complex blockchain investigations and report generation.

#### Capabilities

- **Natural Language Queries:** Users ask questions in plain English
- **Knowledge Graph Integration:** Query Chain Insights data through conversation
- **Multi-Hop Analysis:** Synthesise complex relationships across transaction chains
- **Report Generation:** Create clear, court-admissible investigation narratives

#### Domain Expertise

The AI Investigator understands:

- **AML Terminology:** "Structuring," "peeling chain," "mixer," "layering"
- **Regulatory Context:** KYC/AML requirements, FATF guidelines, jurisdiction-specific rules
- **Chain Insights Data:** Query APIs, interpret risk scores, navigate graph data
- **Investigation Methodology:** Systematic approaches to blockchain forensics

#### Continuous Improvement

The LLM capabilities are enhanced through agent loops that:
- Fine-tune on domain-specific data (terminology, scenarios, report formats)
- Evaluate against complex query benchmarks
- Improve knowledge graph integration
- Enhance report quality and accuracy

---

## 7. Chain Synthetics Framework

### 7.1 The Ground Truth Problem

Measuring fraud detection accuracy requires ground truth—known examples of fraudulent activity with verified labels. This creates a fundamental challenge:

- Real fraud labels are sensitive and not publicly available
- Historical hacks are documented but not structured for benchmarking
- Synthetic data may not reflect real-world complexity
- Systems could overfit to known test cases

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

Chain Synthetics powers the continuous improvement loops:

1. **Dataset Generation:** Chain Synthetics produces test datasets with injected patterns
2. **Blind Evaluation:** The agent's systems do not know which transactions are synthetic
3. **Execution:** Detection algorithms run against test datasets
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

## 8. Continuous Improvement

### 8.1 Self-Improving Agent Architecture

Chain Insights Agent employs autonomous improvement loops that continuously enhance its intelligence capabilities. Rather than waiting for manual updates, the agent runs local improvement agents that test, evaluate, and deploy enhancements automatically.

### 8.2 Improvement Loop Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                  CONTINUOUS IMPROVEMENT SYSTEM                   │
│                                                                  │
│  ┌─────────────┐    ┌─────────────┐    ┌─────────────┐          │
│  │  Generate   │    │  Evaluate   │    │   Deploy    │          │
│  │  Variation  │───▶│  Against    │───▶│   If        │          │
│  │             │    │  Benchmark  │    │   Better    │          │
│  └─────────────┘    └─────────────┘    └─────────────┘          │
│        ▲                                      │                  │
│        │                                      │                  │
│        └──────────────────────────────────────┘                  │
│                    Continuous Loop                               │
│                                                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │                CHAIN SYNTHETICS BENCHMARK                │    │
│  │    Objective ground truth for measuring improvement      │    │
│  └─────────────────────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────────────┘
```

### 8.3 What Gets Improved

**Analytics Engine**
- New graph algorithm implementations
- Pattern detection optimisations
- Processing efficiency improvements
- Novel fraud topology detection

**Machine Learning Models**
- Model architecture variations
- Feature engineering improvements
- Training methodology refinements
- Ensemble combination strategies

**AI Investigator (LLM)**
- Domain-specific fine-tuning
- Knowledge graph query capabilities
- Report generation quality
- Terminology and context understanding

### 8.4 Quality Assurance

All improvements are validated against objective benchmarks before deployment:

| Capability | Validation Method | Key Metrics |
|-----------|-------------------|-------------|
| Analytics | Chain Synthetics benchmark | Precision, recall, speed |
| ML Models | Chain Synthetics + temporal validation | Accuracy over time, calibration |
| LLM | Golden Dataset evaluation | Query accuracy, report quality |

**Temporal Validation**: ML predictions are validated over time ($T + \tau$) to ensure real-world accuracy, not just test set performance.

**A/B Testing**: Candidate improvements tested against production systems before full deployment.

---

## 9. Chain Insights Application

### 9.1 Overview

Chain Insights is the consumer-facing application delivering agent intelligence to end users. It provides accessible interfaces for risk scoring, funds tracking, investigation, and AI-powered analysis—plus proactive alerts from the agent's autonomous monitoring.

### 9.2 Risk Scoring

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

### 9.3 Funds Tracking

#### Functionality

A powerful visualisation tool designed to demystify money flow:

- **Trace Money:** Follow funds across multiple hops and supported chains
- **Visualise Flow Patterns:** Interactive graph visualisation displaying the flow topology
- **Reveal Destinations:** Automatically identify and label ultimate recipients (e.g., exchanges, bridges, mixers, or high-risk services)

This feature allows users to "see" the path of funds, making it easier to identify laundering attempts, structuring, or simple payment trails without manually parsing raw block explorer data.

### 9.4 AI Investigator Chat

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

### 9.5 Proactive Alerts

#### Functionality

The agent's autonomous monitoring capabilities surface through the application:

- **Threat Warnings:** Alerts when addresses you're monitoring interact with newly flagged entities
- **Pattern Detection:** Notifications when suspicious patterns are detected involving watched addresses
- **Early Warning:** Proactive alerts about emerging threats before they impact you

### 9.6 Pricing Model

**Flexible Credit System**

- Users purchase credits using cryptocurrency
- **Pay-Per-Use:** Credits are spent only on specific queries, tracking actions, or chat interactions
- **No Expiration:** Credits remain valid until used
- **Tiered Access:** Options available for casual users versus power users (investigators)

---

## 10. x402 Agent Gateway

### 10.1 The Agent Payment Problem

Autonomous AI agents face a fundamental challenge when accessing paid services: traditional payment models assume human users with accounts, subscriptions, and manual payment authorisation.

Agents need:

- **No accounts:** Agents should not need to pre-register
- **No subscriptions:** Pay only for what is used
- **Micropayments:** Individual queries may cost fractions of a cent
- **Programmatic:** Payment authorisation without human intervention
- **Real-time:** No delays for payment processing

### 10.2 x402 Protocol Integration

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

### 10.3 Use Cases

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

### 10.4 Pricing

Agent gateway pricing mirrors credit-based pricing:

- Pay-per-query based on query type and complexity
- Micropayment-compatible (fractions of a cent per query for basic lookups)
- Volume discounts for high-frequency users
- No minimum commitments

---

## 11. Token Economics

### 11.1 $CIA Token

**$CIA (Chain Insights Agent)** is the native token of the Chain Insights ecosystem on Virtuals Protocol. It powers access to intelligence services, enables ecosystem governance, and captures value from the agent's revenue streams.

#### Token Utility

| Utility | Description |
|---------|-------------|
| **Service Access** | Purchase credits for risk scoring, tracking, and AI chat |
| **x402 Payments** | Pay-per-query for agent gateway access |
| **Premium Features** | Access to advanced capabilities and higher rate limits |
| **Ecosystem Governance** | Participate in protocol decisions and roadmap prioritisation |

### 11.2 Revenue Model

Chain Insights generates revenue through five complementary streams, creating a diversified and sustainable business model:

| Revenue Stream | Description | Target Customer |
|----------------|-------------|-----------------|
| **Chain Insights Credits** | Purchase credits for risk scoring, tracking, & chat | Retail users, small teams, investigators |
| **x402 Agent Gateway** | Pay-per-query micropayments from AI agents | Autonomous AI agents, DeFi protocols, trading bots |
| **Enterprise API Licenses** | Bulk queries, SLAs, custom analytics, dedicated support | Exchanges, compliance platforms, large organisations |
| **Address Label Datasets** | Licensed access to verified, up-to-date address attributions | Other intelligence providers, exchanges, compliance vendors |
| **Investigation Reports** | Premium court-admissible forensic reports via AI Investigator | Law enforcement, legal teams, recovery services |

### 11.3 Value Flow Architecture

Chain Insights creates sustainable value flow connecting revenue generation to token value:

```
┌─────────────────────────────────────────────────────────────────┐
│                     REVENUE SOURCES                              │
│  ┌───────────────┐ ┌───────────────┐ ┌───────────────┐          │
│  │Chain Insights │ │ x402 Agent    │ │ Enterprise    │          │
│  │Credits        │ │ Payments      │ │ Licenses      │          │
│  └───────┬───────┘ └───────┬───────┘ └───────┬───────┘          │
│          │                 │                 │                   │
│  ┌───────┴─────────────────┴─────────────────┴───────┐          │
│  │                                                    │          │
│  │  ┌───────────────┐         ┌───────────────┐      │          │
│  │  │Address Label  │         │ Investigation │      │          │
│  │  │Datasets       │         │ Reports       │      │          │
│  │  └───────┬───────┘         └───────┬───────┘      │          │
│  │          │                         │              │          │
│  └──────────┼─────────────────────────┼──────────────┘          │
└─────────────┼─────────────────────────┼─────────────────────────┘
              └────────────┬────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│                   VALUE DISTRIBUTION                             │
│                                                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │                 Operations & Development                 │    │
│  │  Infrastructure • R&D • Support • Continuous Improvement │    │
│  └─────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │              $CIA Token Buybacks                         │    │
│  │  Revenue-funded purchases supporting token value         │    │
│  └─────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │               Ecosystem Growth Fund                      │    │
│  │  Partnerships • Multi-chain expansion • Integrations     │    │
│  └─────────────────────────────────────────────────────────┘    │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

### 11.4 Address Label Datasets as Monetizable Assets

The auto-discovery capabilities create a unique byproduct: a continuously curated, verified database of address attributions. This dataset has significant standalone value:

**Why Address Labels Are Valuable**

- **Scarcity:** Comprehensive, verified address labels are complicated to source
- **Freshness:** Labels require continuous curation as new addresses emerge and attributions change
- **Verification:** Each label is validated against on-chain behaviour
- **Coverage:** Autonomous discovery means broader coverage than manual curation

**Market Demand**

Multiple market participants need current, accurate address attributions:

- **Exchanges:** For internal compliance systems beyond their primary intelligence provider
- **Compliance Vendors:** To supplement their own datasets
- **Other Intelligence Providers:** Cross-reference and validation
- **Research Institutions:** Academic study of blockchain ecosystems
- **Law Enforcement:** Investigation support

**Licensing Model**

Address label datasets can be licensed in multiple formats:

- **Full Dataset Access:** Complete verified label database with regular updates
- **Category-Specific:** Only exchange labels, only sanctioned addresses, etc.
- **API Access:** Query-based access for integration into existing systems
- **Historical Snapshots:** Point-in-time datasets for research purposes

### 11.5 Buyback Mechanism

Revenue from all five streams funds $CIA token buybacks:

- Creates demand pressure supporting token value
- Aligns ecosystem incentives with token holders
- Sustainable model tied to actual usage and revenue

---

## 12. Use Cases

### 12.1 Exchange Compliance

**Scenario:** A centralised exchange needs to screen deposits and withdrawals for AML compliance.

**Solution:**

- Integrate Chain Insights Enterprise API
- Automatic risk scoring for all incoming deposits
- Flag high-risk transactions for manual review
- Generate audit trails for regulatory reporting

**Value:** Automated compliance reduces manual review burden while meeting regulatory requirements.

### 12.2 DeFi Protocol Security

**Scenario:** A lending protocol wants to prevent interaction with stolen funds or sanctioned addresses.

**Solution:**

- Integrate the x402 gateway for real-time queries
- Check depositor addresses before accepting collateral
- Monitor borrower addresses for risk changes
- Automated alerts when counterparty risk increases

**Value:** Protocol protection without manual intervention, suitable for fully autonomous operation.

### 12.3 Hack Investigation

**Scenario:** A protocol suffers an exploit and needs to trace stolen funds.

**Solution:**

- Use the Funds Tracking tool to visualise flow patterns and identify destinations
- Use the Chain Insights application to analyse attacker addresses
- AI chat interface to explore the transaction graph
- Generate an investigation report documenting the fund flow

**Value:** Rapid investigation capability without specialised forensics expertise.

### 12.4 Personal Risk Assessment

**Scenario:** A user is blocked from an exchange and wants to understand why.

**Solution:**

- Check one's own address risk score in the Chain Insights application
- Review explainable factors identifying risk sources
- Understand which counterparty interactions caused contamination
- Take informed action to address or dispute the flag

**Value:** Transparency and recourse for users facing opaque compliance decisions.

### 12.5 Autonomous Agent Risk Management

**Scenario:** An AI trading agent needs to avoid contaminated addresses while maximising returns.

**Solution:**

- Query the x402 gateway before each transaction
- Integrate risk scores into trading decision logic
- Automatically exclude high-risk counterparties
- Log all risk checks for audit purposes

**Value:** Autonomous risk management enabling compliant automated trading.

### 12.6 Privacy Audit

**Scenario:** A privacy-conscious user wants to understand their transaction graph exposure.

**Solution:**

- Analyse own addresses in Chain Insights using Funds Tracking
- Map connections to known entities
- Identify potential deanonymization vectors
- Make informed decisions about future transaction patterns

**Value:** Empowered privacy management through transparency.

### 12.7 Proactive Threat Detection

**Scenario:** A user wants to be warned before interacting with newly discovered scams.

**Solution:**

- Chain Insights Agent autonomously monitors the network
- Detects dusting attacks and labels source addresses as risky
- Alerts the user before they interact with flagged addresses
- Continuously updates threat intelligence in real-time

**Value:** Protection before harm occurs, not just forensics after the fact.

---

## 13. Roadmap

### Phase 1 (Now — Q4 2025)
*   ✅ Core Indexing Service
*   ✅ Analytics Pipeline baseline
*   ✅ Chain Synthetics framework
*   🔄 Chain Insights Agent launch on Virtuals Protocol
*   🔄 Continuous improvement loops operational

### Phase 2 (Q1 2026)
*   Chain Insights Application public launch
*   Chain Insights Funds Tracking
*   x402 Agent Gateway
*   EVM chain support expansion

### Phase 3 (Q2 — Q3 2026)
*   Chain Insights Risk Scoring (full release)
*   Proactive alerting system
*   ML model enhancement cycle

### Phase 4 (Q4 2026+)
*   AI Investigator Chat (full release)
*   Court-admissible report generation
*   Enterprise API launch

### Beyond
*   Multi-chain expansion (UTXO, Substrate, EVM ecosystems)
*   Enterprise partnerships
*   Regulatory compliance integrations
*   Advanced autonomous capabilities

---

## 14. Team & Partners

### 14.1 Founder

**Kamil Wojciechowski (aphex5)**

Creator of Chain Insights, who pioneered blockchain intelligence on the Bittensor network with SN15. Following extensive operation of a decentralised intelligence subnet, Kamil invested 1.5 years in deep research and architectural redesign, rebuilding the system from first principles for the agentic economy.

This extensive R&D period addressed fundamental questions:

- How should intelligence systems continuously improve themselves?
- What architectures enable both reactive and proactive agent capabilities?
- How can fraud detection be objectively measured and benchmarked?
- What data model enables cross-chain analysis at scale?

The answers to these questions shaped Chain Insights Agent's architecture. The evolution from Bittensor to Virtuals Protocol represents the natural progression toward a truly autonomous AI agent paradigm.

**Responsibilities:**

- Indexing infrastructure design and operation
- Agent architecture and continuous improvement systems
- Overall technical leadership
- Project management and coordination

### 14.2 Partners

**1-HORIZON LTD — Infrastructure Partner**

- Scalable cloud infrastructure for indexing and intelligence services
- DevSecOps and AIOps expertise with four decades of combined experience
- Confidential Computing capabilities with TDX/SGX for Trusted Execution Environments
- Deep blockchain ecosystem understanding

**U1CORE — Development Partner**

- Chain Insights application development (UI/UX design, frontend implementation)
- Application backend services
- Enterprise-grade development practices
- User experience optimisation

### 14.3 Why Virtuals Protocol?

Chain Insights evolved from Bittensor to Virtuals Protocol for strategic alignment with the agentic economy:

**Agent-Native Platform**
Virtuals Protocol is purpose-built for autonomous AI agents, providing native infrastructure for agent deployment, tokenisation, and ecosystem integration.

**Alignment with Vision**
The Chain Insights vision of an autonomous, self-improving intelligence agent aligns perfectly with Virtuals' agent-first approach.

**Ecosystem Synergies**
Integration with other Virtuals agents enables collaborative intelligence—agents sharing insights and building collective awareness.

**Proven Technology**
The core technology was battle-tested on Bittensor. Virtuals provides the optimal environment for the next evolution.

---

## 15. Conclusion

### 15.1 The Opportunity

Blockchain intelligence is at an inflexion point. Regulatory requirements are expanding globally. The agentic economy is emerging rapidly. Current centralised solutions cannot serve the scale, accessibility, and innovation requirements of this new landscape.

Chain Insights Agent addresses this opportunity by:

**Democratizing Access**

- Flexible credit-based pricing accessible to individuals
- x402 gateway enabling autonomous agent integration
- Self-service application for anyone to check addresses

**Maintaining Neutrality**

- Intelligence without judgment
- Tool for compliance, investigation, and privacy audit alike
- Users decide how to act on intelligence

**Continuous Evolution**

- Self-improving AI systems that learn faster than threats evolve
- Autonomous improvement loops enhance capabilities continuously
- Proactive threat detection, not just reactive analysis

**Building Sustainability**

- Diversified revenue from five complementary streams
- Token buybacks from operational income
- Aligned incentives across stakeholders

### 15.2 The Vision

Chain Insights becomes the default intelligence layer for the agentic economy.

Any agent, any chain, any query—with real-time risk assessment enabling safe autonomous operation in an increasingly complex blockchain landscape.

We build agents that protect agents. Intelligence that improves itself. Safety infrastructure for the autonomous future.

### 15.3 Call to Action

**For Users:**
Try Chain Insights. Check your addresses. Visualise the funds flow. Explore the intelligence. Experience what proactive protection feels like.

**For Builders:**
Integrate the x402 gateway into your agents and applications. Build on a neutral intelligence infrastructure. Join the agentic economy.

**For Enterprises:**
Contact us for API integration, bulk access, and custom solutions tailored to your compliance needs.

**For the Curious:**
Follow our progress. Watch the agent improve. Witness the future of blockchain intelligence.

---

**Chain Insights Agent**
*Powered by Chainswarm Technology — Built on Virtuals Protocol*

Autonomous blockchain intelligence for the agentic economy.

Founder: Kamil Wojciechowski (aphex5)
GitHub: github.com/chainswarm

*Neutral intelligence for an autonomous world.*


*Document Version 2.0 — 2025*
*Chain Insights Agent — Powered by Chainswarm Technology*
