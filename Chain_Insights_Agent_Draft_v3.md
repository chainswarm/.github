Chain Insights Agent

Onchain risk scoring, fund-flow tracing, and investigation reports -
delivered via ACP

TL;DR

Chain Insights Agent is an autonomous onchain intelligence agent that
helps traders, protocols, and other agents:

Screen addresses and counterparties with risk scores and evidence

Trace fund flows across DeFi hops, bridges, and known service clusters

Generate investigation-ready reports with timelines, artifacts, and
receipts

Publish real-time scam/threat alerts (opt-in)

Access is pay-per-use through the Chain Insights App and through
Virtuals ACP (via Butler and agent-to-agent commerce).

Positioning notes (credibility-first)

This version of the announcement intentionally avoids over-claims. It
frames outputs as explainable, evidence-based signals and includes clear
disclaimers (no legal advice; probabilistic scoring).

It also aligns terminology and rails with ACP: resource offerings for
read-only queries and job offerings for escrow + onchain receipts.

What it is

Chain Insights Agent is a specialized security and compliance
intelligence layer for the agentic economy. It turns raw onchain data
into explainable risk signals and fund-flow narratives that can be
consumed by humans or by other agents.

What it does

The agent exposes two kinds of offerings on ACP:

1)  Resource offerings (fast, read-only)

For high-frequency queries that do not require escrow or a full job
lifecycle:

Address Risk Check: score + top reasons + closest risky exposures

Transaction Context: what this tx resembles, and why

Live Threat Feed: recent clusters / campaigns (with confidence levels)

2)  Job offerings (escrow + onchain receipt)

For deeper work that benefits from negotiation, deliverables, and
auditability:

Fund-Flow Trace: graph + key hops + service tags (bridges, mixers, CEX
clusters when known)

Incident Report: timeline + evidence table + export (PDF/Markdown)

Monitoring Setup: watchlist + alert rules + periodic summaries

Important: scores and labels are probabilistic signals. Every output
includes evidence and confidence indicators.

Who it's for

Traders & power users

Check counterparties before swaps, OTC trades, NFT deals, and
peer-to-peer transfers.

Protocols & DAOs

Screen deposits, assess exposure, triage suspicious activity, and
generate internal incident notes.

Autonomous agents

Query risk and provenance via ACP to make safer automated decisions
(routing, settlement, policy checks).

Victims & investigators

Reconstruct the path of stolen funds, document the trail, and export
artifacts for follow-up.

Multi-chain scope

Initial scope prioritizes networks that matter most for agent commerce
and onchain activity:

Access channels

You can use Chain Insights Agent in multiple ways:

Chain Insights App: direct UI for risk checks, traces, exports
(pay-per-query).

ACP (Agent Commerce Protocol): agent-to-agent intelligence and job
execution.

Butler: natural language task routing and payments through Virtuals
gateway.

X/Twitter feed (optional): public alerts for high-confidence active
threats.

Chain Chat App vs Butler vs ACP (recommended integration)

Think of these as layers:

ACP = the protocol layer (discovery + job lifecycle + escrow +
receipts).

Butler = a default buyer UI that routes a natural language request to
the best agent.

Your Chain Chat App = a specialized buyer UI optimized for onchain
security workflows.

Recommended integration paths:

Path A - Fastest distribution (provider-first)

Register Chain Insights Agent as a Provider/Hybrid on ACP.

Expose risk checks as Resource offerings and investigations as Job
offerings.

Let Butler drive initial demand (users can pay via their Butler wallet).

Path B - Full product UX (custom buyer app)

Your app calls ACP programmatically (via the Node/Python SDK) to create
Jobs and consume Resources.

You implement a 'spending wallet' UX similar to Butler (deposit USDC on
Base, then pay per job).

You still keep Butler compatibility so any user/agent in the ecosystem
can buy your services.

Wallets (user spending vs agent execution)

There are two distinct wallet concepts in ACP ecosystems:

User spending wallet (Butler wallet): a user-controlled balance used to
pay agents.

Agent wallet (smart contract account): the onchain identity of an ACP
agent; controlled via whitelisted dev wallets signing job memos.

If you want a Virtuals-native wallet UX in your app, the closest pattern
is to mirror Butler: a dedicated spending wallet on Base funded with
USDC, then used for all agent interactions.

How it fits Virtuals (ACP + Butler)

ACP is the settlement and coordination layer. Butler is a buyer
interface that discovers agents, negotiates fees, escrows payment, and
returns an onchain receipt. Chain Insights Agent is built to be
discoverable in the Service Registry and callable by other agents.

Payments and pricing:

Prices are displayed in USD for clarity, and settle in USDC on Base (ACP
standard).

Agent smart wallets are contract-based; development wallets are
whitelisted to authorize job memos.

Resource offerings can serve low-latency read-only requests without full
onchain job creation.

Naming and token

**Token Name:** Chain Insights Agent (\$CIA)

The name is settled: \$CIA conveys autonomy and intelligence alignment with Virtuals Protocol's agent-first positioning.

Token Utility (Alignment with Virtuals Whitepaper):

No custom utility mechanics beyond official Virtuals Protocol specs.

**Burnback Mechanism (Deflation via Revenue Share):**

- **Trigger:** Once Chain Insights Agent FDV reaches \$40M USD
- **Burn Rate:** 20% of net monthly revenue
- **Mechanism:** Revenue directed to market buys of \$CIA, then burned onchain
- **Accounting:** Transparent wallet with published burn events and FDV tracking
- **Denominator:** "Net revenue" = total ACP resource + job payments minus operational costs (infrastructure, development)

This aligns token incentives with agent growth without creating artificial utility walls. Burnback is the only mechanism beyond Virtuals whitepaper specs.

Roadmap

Bittensor era (completed)

Core indexing and value flow normalization

Funds-tracking feature

Analyzers and evaluation framework

Virtuals launch (Q1 2026)

Agent launch on Virtuals Protocol (Service Registry listing)

ACP + Butler integration (jobs + resource offerings)

Base (EVM) support

Risk scoring v1 (explainable reasons)

2026

AI chat interface in the app

Proactive monitoring and alerting (opt-in)

Additional chain coverage and better cross-chain entity resolution

Public threat feed + community submissions pipeline

Disclaimers

Not legal advice. Outputs are informational and probabilistic.

No affiliation with any government intelligence agency.

Risk scores may be wrong; always inspect the evidence and use your own
judgment.

Quick links

Founder: Kamil Wojciechowski (@aphex5)

Built by: Chainswarm Technology

Partners: 1-HORIZON LTD (Infrastructure) \| U1CORE (Development)

Remaining Decisions / Open Questions

**Decided:**
- ✅ Token Name: \$CIA
- ✅ Token Utility: Burnback only (20% monthly at \$40M FDV threshold)
- ✅ Virtuals Alignment: No custom utilities beyond whitepaper

**Still Open:**

Public alerts: default to private alerts only, or also run a public X/Twitter feed?

Launch scope: which chains guaranteed at launch (Base + Ethereum)?

Data policy: accept community submissions? Review process for risk labels?

Buyer UX: pay from Butler only, or custom spending wallet in Chain Chat App?

Revenue tracking: define 'operational costs' + audit frequency for burn accounting?
