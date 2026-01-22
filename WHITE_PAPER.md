# Chain Insights Agent — White Paper

**Autonomous Blockchain Intelligence for the Agentic Economy**

*Powered by Chainswarm Technology — Built on Virtuals Protocol*

Version 2.1 | 2025

---

## Table of Contents

1. [Abstract](#1-abstract)
2. [Introduction](#2-introduction)
3. [Problem Statement](#3-problem-statement)
4. [Solution Overview](#4-solution-overview)
5. [Use Cases](#5-use-cases)
6. [Architecture](#6-architecture)
7. [Virtuals Protocol Integration](#7-virtuals-protocol-integration)
8. [Chain Synthetics Framework](#8-chain-synthetics-framework)
9. [Chain Insights Application](#9-chain-insights-application)
10. [Token Economics](#10-token-economics)
11. [Roadmap](#11-roadmap)
12. [Team & Partners](#12-team--partners)
13. [Conclusion](#13-conclusion)

---

## 1. Abstract

Chain Insights Agent is an autonomous blockchain intelligence system built on Virtuals Protocol that provides real-time risk scoring, funds tracking, and investigative AI capabilities for the emerging agentic economy. The agent operates in two complementary modes: a reactive mode where users ask questions and the agent researches and solves problems, and a proactive mode where the agent autonomously scans the network, warns before threats materialise, and automatically labels risky addresses.

Fully integrated with Virtuals Protocol's ecosystem, Chain Insights provides its intelligence services through the Agent Commerce Protocol (ACP) for seamless agent-to-agent transactions, Butler for user discovery, and maintains an active social presence on X (Twitter) to broadcast threat intelligence in real-time. The agent employs self-improving systems that continuously enhance detection capabilities through automated evaluation and A/B testing against the Chain Synthetics benchmark framework.

This paper describes the technical architecture, agent capabilities, and product ecosystem that positions Chain Insights as the neutral intelligence layer for autonomous agents, enterprises, and retail users.

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

As the agentic economy emerged, we evolved to Virtuals Protocol, which better aligns with our vision of an autonomous AI agent serving the blockchain intelligence needs of humans and machines alike. Virtuals Protocol provides the ideal infrastructure for agent-to-agent commerce, user discovery through Butler, and ecosystem-wide coordination—capabilities that enable Chain Insights to reach its full potential.

### 2.4 Design Philosophy

> *"The best intelligence system is one that improves itself faster than threats evolve. We build agents that learn, adapt, and protect—autonomously."*

This philosophy shapes every architectural decision. Chain Insights Agent is not a static tool—it is a living system that continuously enhances its detection capabilities through self-improving loops. The agent operates both reactively (responding to user queries) and proactively (scanning for threats and broadcasting warnings via social channels).

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

Current intelligence providers offer no solution for these use cases. Their APIs are designed for batch processing and human review, not real-time autonomous decision-making. The agentic economy requires intelligence infrastructure that agents can access natively—through standardised protocols like ACP that enable seamless agent-to-agent transactions.

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
- **Social Broadcasting:** Posts real-time threat intelligence on X (Twitter), similar to how aixbt shares market insights
- **Continuous Monitoring:** Tracks addresses of interest and alerts on significant changes

### 4.3 Access Channels

Chain Insights delivers intelligence through multiple complementary channels:

**Chain Insights Application**
A consumer-facing web application providing:

- Risk scoring for any address with explainable factors
- Funds Tracking to visualise money flow patterns
- AI-powered chat interface for investigative queries
- Interactive graph visualisations
- Proactive alerts and notifications

**Agent Commerce Protocol (ACP)**
Native Virtuals Protocol integration enabling:

- Pay-per-query transactions with other agents
- Standardised service schema for risk queries
- Smart contract-based escrow for service delivery
- Seamless agent-to-agent commerce

**Butler Integration**
Discovery and interaction through Virtuals' consumer gateway:

- Users find Chain Insights through Butler's agent directory
- Natural language job requests for investigations
- Guided requirement collection for service fulfilment

**Social Presence (X/Twitter)**
Real-time threat intelligence broadcasting:

- Automated alerts about emerging threats
- Risk warnings for trending addresses/protocols
- Educational content about blockchain security
- Community engagement and threat reporting

---

## 5. Use Cases

### 5.1 Trading Agent Risk Check

**Scenario:** An autonomous trading agent on Virtuals needs to verify counterparty addresses before executing swaps.

**Solution:**
- Agent queries Chain Insights via ACP for risk scores
- Pay-per-query with smart contract escrow
- Real-time response enables risk-informed trading decisions
- Integration through standardised ACP schema

**Value:** Autonomous risk management without human intervention.

### 5.2 DeFi Protocol Security

**Scenario:** A lending protocol wants to prevent interaction with stolen funds or sanctioned addresses.

**Solution:**
- Integrate Chain Insights via ACP for deposit screening
- Automatic risk scoring for all incoming deposits
- Flag high-risk addresses for additional verification
- Continuous monitoring for risk changes

**Value:** Protocol protection with seamless agent-to-agent integration.

### 5.3 User Risk Assessment

**Scenario:** A user is blocked from an exchange and wants to understand why.

**Solution:**
- Check own address in Chain Insights Application
- Review explainable risk factors
- Understand which interactions caused contamination
- Take informed action to address the issue

**Value:** Transparency and recourse for opaque compliance decisions.

### 5.4 Hack Investigation

**Scenario:** A protocol suffers an exploit and needs to trace stolen funds.

**Solution:**
- Use Funds Tracking to visualise flow patterns
- AI chat to explore transaction graph
- Generate investigation report documenting fund flow
- Share findings with law enforcement

**Value:** Rapid investigation without specialised forensics expertise.

### 5.5 Proactive Threat Detection

**Scenario:** Users want protection from emerging scams before interaction.

**Solution:**
- Chain Insights Agent monitors network autonomously
- Detects attack patterns (dusting, phishing drops, etc.)
- Posts warnings on X/Twitter in real-time
- Labels source addresses for future queries

**Value:** Community protection through proactive intelligence.

### 5.6 Multi-Agent Coordination

**Scenario:** A complex investigation requires coordination between multiple specialised agents.

**Solution:**
- Investigation agent requests intelligence from Chain Insights via ACP
- Chain Insights provides risk data and flow analysis
- Investigation agent synthesises with other sources
- Collaborative intelligence across Virtuals ecosystem

**Value:** Network effects from agent-to-agent commerce.

---

## 6. Architecture

### 6.1 System Overview

```
┌─────────────────────────────────────────────────────────────────┐
│                    INTERACTION LAYER                             │
│  ┌──────────────┐ ┌──────────────┐ ┌──────────────┐ ┌────────┐  │
│  │Chain Insights│ │   Butler     │ │    ACP       │ │X/Twitter│ │
│  │ Application  │ │  Discovery   │ │  Gateway     │ │  Bot   │  │
│  └──────┬───────┘ └──────┬───────┘ └──────┬───────┘ └────┬───┘  │
└─────────┼────────────────┼────────────────┼──────────────┼──────┘
          │                │                │              │
          └────────────────┴────────┬───────┴──────────────┘
                                    │
                                    ▼
┌─────────────────────────────────────────────────────────────────┐
│                   INTELLIGENCE LAYER                             │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │              AGENT ORCHESTRATION                         │    │
│  │  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐   │    │
│  │  │   Reactive   │  │  Proactive   │  │   Learning   │   │    │
│  │  │    Mode      │  │    Mode      │  │    Loop      │   │    │
│  │  └──────────────┘  └──────────────┘  └──────────────┘   │    │
│  └─────────────────────────────────────────────────────────┘    │
│                               │                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │              INTELLIGENCE CAPABILITIES                   │    │
│  │  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐      │    │
│  │  │  Analytics  │  │  ML Risk    │  │   Social    │      │    │
│  │  │  Engine     │  │  Scoring    │  │ Intelligence│      │    │
│  │  └─────────────┘  └─────────────┘  └─────────────┘      │    │
│  └─────────────────────────────────────────────────────────┘    │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│                   FOUNDATION LAYER                               │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │              CORE DATA & PROCESSING                      │    │
│  │  ┌───────────┐ ┌───────────┐ ┌───────────┐ ┌─────────┐  │    │
│  │  │ Indexing  │ │  Money    │ │    ML     │ │ Pattern │  │    │
│  │  │ Service   │ │  Flows    │ │ Features  │ │Detection│  │    │
│  │  └───────────┘ └───────────┘ └───────────┘ └─────────┘  │    │
│  │  ┌───────────┐ ┌───────────┐ ┌─────────────────────┐    │    │
│  │  │   Risk    │ │Evaluation │ │   Chain Synthetics  │    │    │
│  │  │  Scoring  │ │ A/B Test  │ │   (Benchmarking)    │    │    │
│  │  └───────────┘ └───────────┘ └─────────────────────┘    │    │
│  └─────────────────────────────────────────────────────────┘    │
│                          │                                       │
│     ┌────────────────────┼────────────────────┐                 │
│     ▼                    ▼                    ▼                 │
│ ┌────────┐          ┌────────┐          ┌────────┐             │
│ │Substrate│      │  EVM   │      │  SVM   │      │  UTXO  │    │
│ │ Chains │      │ Chains │      │(Solana)│      │ Chains │    │
│ └────────┘      └────────┘      └────────┘      └────────┘    │
└─────────────────────────────────────────────────────────────────┘
```

### 6.2 Foundation Layer

The Foundation Layer provides all core data infrastructure and analytical capabilities. This is where value flows are captured, processed, and analysed.

#### 6.2.1 Core Indexing Service

The indexing service captures blockchain data across multiple chains and transforms it into the unified data model.

**Multi-Chain Support:**
- **Substrate Chains:** Account-based model with native support for Polkadot ecosystem networks
- **EVM Chains:** Support for Ethereum-compatible networks across the EVM ecosystem
- **SVM Chains:** Solana Virtual Machine support for the Solana ecosystem
- **UTXO Chains:** Support for Bitcoin-style unspent transaction output models

#### 6.2.2 Money Flows (Unified Data Model)

Chain Insights uses a **value-oriented data model** focused on money flows rather than individual transactions:

| Traditional Approach | Chain Insights Approach |
|---------------------|------------------------|
| Store every transaction | Aggregate money flows |
| Chain-specific schemas | Unified USD-value model |
| Massive storage needs | Compressed representation |
| Focus on transactions | Focus on value relationships |
| Currency-specific analysis | Value-normalized analysis |

**Key Principles:**

- **USD Value Normalisation:** All asset transfers converted to USD value at time of transaction, enabling cross-asset and cross-chain analysis
- **Aggregated Money Flows:** Flows between address pairs capture the relationship rather than every individual event
- **Relationship-Centric:** The model answers "how much value moved between A and B" not "list every transaction"

This model is **smaller** (aggregated vs. raw), **faster** (query relationships, not events), **portable** (same model across all chains), and **analytical** (designed for ML and pattern detection).

#### 6.2.3 ML Features

**100+ pre-calculated features per address across 9 categories:**

| Category | Features | Description |
|----------|----------|-------------|
| **Base** | 9 | Degree, counterparties, transaction counts |
| **Volume** | 10 | Inflow, outflow, net flow, averages, medians |
| **Statistical** | 5 | Variance, skewness, kurtosis, coefficient of variation |
| **Flow** | 6 | Concentration, diversity, reciprocity, velocity |
| **Graph** | 14 | PageRank, betweenness, closeness, k-core, community |
| **Directional** | 5 | In/out ratio, asymmetry, flow direction entropy |
| **Behavioral** | 40+ | Temporal patterns, burst detection, structuring signals |
| **Edge** | 7 | Relationship age, bidirectionality, multi-asset ratios |
| **Label** | 12 | Entity type indicators, risk proximity scores |

#### 6.2.4 Pattern Detection

**7 specialized detectors** for identifying suspicious topologies:

| Detector | Purpose |
|----------|---------|
| **Cycle Detector** | Circular flows returning funds to origin |
| **Layering Detector** | Multiple intermediate hops obscuring source/destination |
| **Network Detector** | Coordinated activity across address clusters |
| **Proximity Detector** | Risk propagation through transaction graph |
| **Motif Detector** | Known fraud subgraph patterns (mixers, peel chains) |
| **Burst Detector** | Sudden activity spikes indicating automated operations |
| **Threshold Detector** | Structuring patterns to evade reporting limits |

#### 6.2.5 Risk Scoring

Real-time risk assessment for any address:

- Address classification (exchange, DeFi, personal, suspicious)
- Risk score with explainable factors
- Proximity risk from related addresses
- Calibrated probabilities that match observed frequencies
- Confidence intervals for score uncertainty

#### 6.2.6 Evaluation & A/B Testing

Continuous improvement through automated evaluation:

- **Chain Synthetics Integration:** All improvements tested against synthetic benchmark
- **A/B Testing:** Candidate models and algorithms tested against production
- **Temporal Validation:** Predictions validated over time to catch overfitting
- **Automatic Deployment:** Improvements that exceed benchmarks are deployed automatically

### 6.3 Intelligence Layer

The Intelligence Layer contains the agent's cognitive capabilities and learning systems.

#### 6.3.1 Agent Orchestration

**Reactive Mode:**
- Receives queries from users (via App, Butler) or agents (via ACP)
- Plans multi-step investigations
- Queries Foundation Layer components as needed
- Synthesises findings into coherent responses

**Proactive Mode:**
- Continuously monitors blockchain activity
- Detects emerging threats and anomalies
- Triggers alerts and social broadcasts
- Updates threat labels automatically

**Learning Loop:**
- Monitors system performance against benchmarks
- Generates algorithm/model variations
- Evaluates variations against Chain Synthetics
- Deploys improvements that exceed current performance

#### 6.3.2 Intelligence Capabilities

**Analytics Engine:**
Orchestrates graph algorithms and pattern detection, combining multiple signals to identify complex fraud schemes.

**ML Risk Scoring:**
Ensemble model combining address features, graph properties, and pattern matches into calibrated risk scores.

**Social Intelligence:**
Monitors X/Twitter and other social sources for:
- Reported scams and exploits
- Community-flagged addresses
- Emerging threat discussions
- Market sentiment affecting risk assessment

### 6.4 Interaction Layer

The Interaction Layer provides all interfaces for humans and agents to access Chain Insights intelligence.

#### 6.4.1 Chain Insights Application

Consumer web application with full access to all capabilities (see Section 8).

#### 6.4.2 Butler Discovery

Integration with Virtuals Protocol's Butler enables:
- Agent discovery through Butler's directory
- Natural language job requests
- Guided requirement collection
- Service delivery through ACP

#### 6.4.3 ACP Gateway

Native Agent Commerce Protocol integration:
- Standardised service schema for intelligence queries
- Pay-per-query with smart contract escrow
- Cryptographic verification of service delivery
- Seamless integration with Virtuals agent ecosystem

#### 6.4.4 X/Twitter Bot

Autonomous social presence similar to aixbt:
- Real-time threat alerts and warnings
- Risk assessments for trending addresses
- Educational content about blockchain security
- Community engagement for threat reporting

---

## 7. Virtuals Protocol Integration

### 7.1 Why Virtuals Protocol?

Chain Insights evolved to Virtuals Protocol for strategic alignment with the agentic economy:

**Agent-Native Platform**
Virtuals Protocol is purpose-built for autonomous AI agents, providing native infrastructure for agent deployment, tokenisation, and ecosystem integration.

**Agent Commerce Protocol (ACP)**
ACP enables Chain Insights to provide services to other agents seamlessly:
- Standardised schemas for service requests
- Smart contract-based escrow ensures service delivery
- Cryptographic verification of agreements
- Trust through technology, not intermediaries

**Butler Integration**
Butler serves as the consumer gateway to the agent economy:
- Users discover Chain Insights through Butler
- Natural language interface for job requests
- Guided requirement collection for complex queries
- Service delivery tracked through ACP

**Ecosystem Synergies**
Integration with other Virtuals agents creates network effects:
- Trading agents query Chain Insights for counterparty risk
- DeFi agents validate addresses before transactions
- Investigation agents coordinate on complex cases
- Collaborative intelligence across the ecosystem

### 7.2 ACP Service Schema

Chain Insights will expose services through standardised ACP schemas:

| Service | Description |
|---------|-------------|
| **Risk Score** | Real-time risk assessment for any address |
| **Funds Tracking** | Multi-hop flow analysis with destination identification |
| **Investigation** | Natural language queries and report generation |
| **Address Labels** | Entity attribution and classification data |
| **Batch Screening** | Bulk address verification for compliance |
| **Monitoring Alerts** | Webhook notifications for watched addresses |

### 7.3 Social Intelligence (X/Twitter)

Following the model of successful Virtuals agents like aixbt, Chain Insights maintains an active social presence:

**Automated Threat Alerts:**
- Real-time warnings about detected threats
- Risk assessments for trending addresses or protocols
- Alerts when monitored addresses show suspicious activity

**Educational Content:**
- Explanations of common fraud patterns
- Risk literacy for the crypto community
- Best practices for avoiding scams

**Community Interaction:**
- Responds to user queries about address risk
- Accepts community reports of suspicious activity
- Engages with the security research community

---

## 8. Chain Synthetics Framework

### 8.1 The Ground Truth Problem

Measuring fraud detection accuracy requires ground truth—known examples of fraudulent activity with verified labels. This creates a fundamental challenge:

- Real fraud labels are sensitive and not publicly available
- Historical hacks are documented but not structured for benchmarking
- Synthetic data may not reflect real-world complexity
- Systems could overfit to known test cases

Chain Synthetics solves this through a novel approach to benchmark generation.

### 8.2 Architecture

Chain Synthetics generates test data by **injecting synthetic patterns into real blockchain data**. Synthetic patterns are blurred and merged with existing transactions so they appear natural within the transaction graph. This blending ensures that improvements work in real-world conditions, not just on isolated test data.

#### Pattern Injection

Known fraud topologies are parameterised and injected:

- **Mixing Patterns:** Multi-input, multi-output transactions obscuring fund origin
- **Layering Networks:** Multiple intermediate addresses between source and destination
- **Peel Chains:** Sequential transactions peeling small amounts to final destination
- **Circular Flows:** Funds returning to origin through complex paths
- **Custom Patterns:** Continuously expanding library

Each pattern is configured with scale, timing, value distribution, and blending parameters.

#### Historical Replay

Chain Synthetics can recreate famous hacks and exploits:
- Transaction patterns from documented incidents (Mt. Gox, Ronin Bridge, FTX, etc.)
- Adapted to any supported blockchain network
- Tests whether detection would have caught historical incidents

### 8.3 Continuous Improvement

Chain Synthetics powers the agent's self-improvement loop:

1. **Variation Generation:** Agent creates algorithm/model variations
2. **Benchmark Execution:** Variations tested against Chain Synthetics data
3. **Objective Scoring:** Precision, recall, speed, and novelty measured
4. **Automatic Deployment:** Variations exceeding current performance are deployed

This ensures Chain Insights continuously improves without manual intervention.

---

## 9. Chain Insights Application

### 9.1 Overview

Chain Insights Application is the consumer-facing interface delivering agent intelligence to end users. It provides accessible interfaces for risk scoring, funds tracking, and AI-powered investigation.

### 9.2 AI Chat Interface

Natural language interface for complex queries:

- "Show me all addresses that received funds from this hack"
- "Explain the relationship between these two addresses"
- "What is the risk profile of this wallet's counterparties?"
- "Generate an investigation report for this address"

**Capabilities:**
- Query Chain Insights knowledge through conversation
- Synthesise complex multi-hop relationships
- Generate structured investigation reports
- Explain technical concepts in accessible language

### 9.3 Funds Tracking

A powerful visualisation tool designed to demystify money flow:

- **Trace Money:** Follow funds across multiple hops and supported chains
- **Visualise Flow Patterns:** Interactive graph visualisation displaying the flow topology
- **Reveal Destinations:** Automatically identify and label ultimate recipients (exchanges, bridges, mixers, high-risk services)

This feature allows users to "see" the path of funds, making it easier to identify laundering attempts, structuring, or simple payment trails.

### 9.4 Risk Scoring

- Enter any blockchain address
- Receive a comprehensive risk assessment
- View explainable factors contributing to the score
- Understand connections to flagged entities
- Track score changes over time

**Explainability:** Risk scores include factor breakdown—direct exposure to known bad actors, proximity to flagged addresses, behavioural pattern matches, volume and timing anomalies, and historical incident associations. Users understand *why* an address is flagged, not just that it is flagged.

### 9.5 Proactive Alerts

The agent's autonomous monitoring surfaces through the application:

- **Threat Warnings:** Alerts when addresses you're monitoring interact with newly flagged entities
- **Pattern Detection:** Notifications when suspicious patterns involve watched addresses
- **Early Warning:** Proactive alerts about emerging threats before they impact you

### 9.6 Pricing Model

**Free Credits + Pay-As-You-Go**

- **Free Tier:** New users receive free credits to explore the platform
- **Pay-Per-Use:** After free credits, pay only for what you use
- **On-Chain Payments:** Native support for x402 protocol enabling seamless crypto micropayments
- **$CIA or $VIRTUAL:** Purchase additional credits with ecosystem tokens
- **No Subscriptions:** No monthly fees, no enterprise contracts—just usage-based pricing

---

## 10. Token Economics

### 10.1 $CIA Token

**$CIA (Chain Insights Agent)** is the native token of the Chain Insights ecosystem on Virtuals Protocol.

#### Token Utility

| Utility | Description |
|---------|-------------|
| **Service Access** | Purchase credits for risk scoring, tracking, and chat |
| **ACP Payments** | Pay-per-query for agent-to-agent services |
| **Premium Features** | Access to advanced capabilities and higher rate limits |

### 10.2 Revenue Model

Chain Insights generates revenue through pay-per-use services:

| Revenue Stream | Mechanism |
|----------------|-----------|
| **Chain Insights App Credits** | Pay-per-use via application |
| **ACP Service Payments** | Pay-per-query via Agent Commerce Protocol |
| **Investigation Reports** | Premium court-admissible forensic reports |

**No Enterprise Licenses:** All services are available pay-as-you-go. This ensures accessibility and aligns with the agent-native Virtuals ecosystem.

### 10.3 Token Burns & Value Flow

Once Chain Insights reaches profitability (covering development and infrastructure costs), **20% of net earnings will be used for $CIA token burns**:

```
┌─────────────────────────────────────────────────────────────────┐
│                        REVENUE                                   │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│              COVER COSTS (Development + Infrastructure)          │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼ After Profitability
┌─────────────────────────────────────────────────────────────────┐
│                   NET EARNINGS DISTRIBUTION                      │
│                                                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │                    80% — Operations                      │    │
│  │       Growth • R&D • Continuous Improvement              │    │
│  └─────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │                    20% — $CIA Burns                      │    │
│  │            Deflationary mechanism from profits           │    │
│  └─────────────────────────────────────────────────────────┘    │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

This burn mechanism:
- Activates only after sustainable profitability
- Creates deflationary pressure on $CIA supply
- Aligns token holder interests with agent success

---

## 11. Roadmap

### Phase 1 (Now — Q4 2025)
- [x] Core Indexing Service
- [x] Money Flows data model
- [x] Chain Synthetics framework
- [ ] Chain Insights Agent launch on Virtuals Protocol
- [ ] ACP service integration
- [ ] Butler onboarding
- [ ] SVM (Solana) indexing support
- [ ] Token launch ($CIA)

### Phase 2 (Q1 2026)
- [ ] Chain Insights Application public launch
- [ ] Funds Tracking feature
- [ ] X/Twitter bot deployment
- [ ] EVM chain support expansion
- [ ] Continuous improvement loops operational
- [ ] x402 on-chain payments integration
- [ ] Free credits system

### Phase 3 (Q2 — Q3 2026)
- [ ] Full Risk Scoring release
- [ ] Proactive alerting system
- [ ] ML model enhancement cycle
- [ ] Additional Virtuals ecosystem integrations
- [ ] AI Chat interface (beta)

### Phase 4 (Q4 2026+)
- [ ] AI Chat interface (full release)
- [ ] Court-admissible report generation
- [ ] UTXO chains support (Bitcoin)
- [ ] Token burn mechanism activation (post-profitability)

### Beyond
- [ ] Broader chain coverage
- [ ] Advanced autonomous capabilities
- [ ] Ecosystem partnerships
- [ ] Cross-chain flow tracking
- [ ] Regulatory compliance certifications

---

## 12. Team & Partners

### 12.1 Founder

**Kamil Wojciechowski (aphex5)**

Creator of Chain Insights, who pioneered blockchain intelligence on the Bittensor network with SN15. Following extensive operation of a decentralised intelligence subnet, Kamil invested 1.5 years in deep research and architectural redesign, rebuilding the system from first principles for the agentic economy.

This R&D period addressed fundamental questions:

- How should intelligence systems continuously improve themselves?
- What architectures enable both reactive and proactive agent capabilities?
- How can fraud detection be objectively measured and benchmarked?
- What data model enables cross-chain analysis at scale?

The answers shaped Chain Insights Agent's architecture. The evolution from Bittensor to Virtuals Protocol represents the natural progression toward a truly autonomous AI agent paradigm.

**Responsibilities:**

- Foundation Layer design and operation
- Agent architecture and continuous improvement systems
- Overall technical leadership
- Virtuals Protocol integration

### 12.2 Partners

**1-HORIZON LTD — Infrastructure Partner**

- Scalable cloud infrastructure for indexing and intelligence services
- DevSecOps and AIOps expertise with four decades of combined experience
- Confidential Computing capabilities with TDX/SGX for Trusted Execution Environments
- Deep blockchain ecosystem understanding

**U1CORE — Development Partner**

- Chain Insights Application development (UI/UX design, frontend implementation)
- Application backend services
- Enterprise-grade development practices
- User experience optimisation

---

## 13. Conclusion

### 13.1 The Opportunity

Blockchain intelligence is at an inflection point. Regulatory requirements are expanding globally. The agentic economy is emerging rapidly. Current centralised solutions cannot serve the scale, accessibility, and innovation requirements of this new landscape.

Chain Insights Agent addresses this opportunity by:

**Democratizing Access**

- Pay-as-you-go via ACP for any agent or user
- Consumer application with credit-based access
- Discovery through Butler for easy onboarding

**Full Virtuals Integration**

- Native ACP services for agent-to-agent commerce
- Butler integration for user discovery
- Social presence for community engagement
- 20% $VIRTUAL buybacks from all revenue

**Continuous Evolution**

- Self-improving systems that learn faster than threats evolve
- Chain Synthetics benchmarking ensures objective improvement
- Proactive threat detection, not just reactive analysis

**Maintaining Neutrality**

- Intelligence without judgment
- Tool for compliance, investigation, and privacy audit alike
- Users decide how to act on intelligence

### 13.2 The Vision

Chain Insights becomes the default intelligence layer for the agentic economy.

Any agent, any chain, any query—with real-time risk assessment enabling safe autonomous operation. Intelligence that improves itself. Protection that operates autonomously.

We build agents that protect agents.

### 13.3 Call to Action

**For Users:**
Try Chain Insights through Butler or our Application. Check your addresses. Explore the intelligence.

**For Agents:**
Integrate via ACP for seamless risk queries. Build safer autonomous systems.

**For the Community:**
Follow us on X/Twitter. Report threats. Help build collective intelligence.

---

**Chain Insights Agent**
*Powered by Chainswarm Technology — Built on Virtuals Protocol*

Autonomous blockchain intelligence for the agentic economy.

Founder: Kamil Wojciechowski (aphex5)
GitHub: github.com/chainswarm

*Neutral intelligence for an autonomous world.*


*Document Version 2.1 — 2025*
*Chain Insights Agent — Powered by Chainswarm Technology*
