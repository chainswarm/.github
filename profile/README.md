## Vision

A system that **monitors blockchain networks for suspicious activity**, **analyzes alerts**, and **identifies risk**—helping track **stolen funds** and disrupt fraud. It is **expandable** across major blockchain types, **open source**, and **rapidly evolving** by design.

## Mission

Deliver field-ready crypto AML intelligence by:

* **Detecting & prioritising risk** on addresses/alerts with calibrated scoring and clear ranking.
* **Tracing funds across chains** (multi-hop flows, counterparties, clusters) to support recovery.
* **Surfacing typologies** (mixers, peel chains, cross-chain bridges, smurfing, flash-exploit routes) with human-readable rationale.
* **Providing investigator tools**: explanations, evidence artefacts, graph views, exposure summaries, and exports.
* **Scaling coverage** quickly across new chains/families with consistent data quality and reproducibility.
* **Staying adaptive** through continuous model updates, drift checks, and measurable quality gates.

## Ecosystem

ChainSwarm AML is a modular ecosystem composed of four reinforcing **mechanics** plus agent capabilities:

1. **Risk-Scoring**
   Predictive models produce **calibrated probabilities** and **ranked risk** for addresses/alerts, with drift monitoring and reproducible runs.

2. **Blockchain Indexing**
   A multi-chain data layer that **ingests and normalizes** blocks/transactions/events, **builds features** (temporal windows, proximity to known bad actors, entity/link stats), **constructs graphs** (entities, relations, flows), and **publishes deterministic batches** for downstream scoring and analysis—guarded by quality gates (completeness, de-duplication, timestamp sanity, lineage).

3. **Address Labeling**
   High-coverage labels from curated sources and community contributions, maintained via **validation loops** to keep precision high and staleness low.

4. **AI-Agents**
   Autonomous **investigation assistants** that trace flows, highlight typologies, draft narratives, and generate **case artefacts**, plugging into the outputs of #1–#3 and surfacing results in the app/APIs.

## Roadmap

* **Phase 1: Risk-Scoring + SOT**
  Stand up the Source-of-Truth (SOT) data products and baseline risk models; expose risk checks via app/API.

* **Phase 2: Indexing**
  Expand multi-chain ingestion, feature engineering, graph construction, and batch publication with strict quality gates.

* **Phase 3: Address Labelling**
  Launch labelling programs, imports, and validation; raise label coverage and freshness.

* **Phase 4: AI-Agents**
  Introduce investigator assistants for assisted tracing, typology suggestions, and narrative drafts.

* **Phase 5: Continuous Improvements**
  Ongoing performance/reliability upgrades, drift & calibration management, provenance/audit packs, and rapid chain/family expansion.
