<p align="center">
  <img src="https://img.shields.io/badge/AI%20Product%20Management-Portfolio-0D1117?style=for-the-badge&labelColor=0D1117&color=58A6FF" alt="AI PM Portfolio"/>
</p>

<h1 align="center">AI Product Teardowns</h1>

<p align="center">
  <strong>Four strategic teardowns of AI-native products — architecture, decisions, and competitive positioning.</strong><br/>
  <em>By <a href="https://github.com/AnushkaaMarwahh">Anushka Marwah</a> · March 2026</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/teardowns-4-58A6FF?style=flat-square" alt="4 Teardowns"/>
  <img src="https://img.shields.io/badge/focus-AI%20Product%20Strategy-8B949E?style=flat-square" alt="AI Product Strategy"/>
  <img src="https://img.shields.io/badge/role-Technical%20PM-8B949E?style=flat-square" alt="Technical PM"/>
</p>

---

## What This Is

This repository contains four product teardowns written from the perspective of an AI Technical Product Manager. Each one goes beyond surface-level feature comparison to analyze **architecture, product decisions, competitive dynamics, and unit economics** — the things that actually determine whether an AI product wins or dies.

Every teardown follows a consistent structure: executive summary → architecture analysis → product decision deep-dives → competitive positioning → recommendations → key metrics. Every claim cites public sources. Every recommendation includes trade-offs.

---

## The Teardowns

<table>
<tr>
<td width="50%" valign="top">

### 🟦 Cursor AI

**The AI-native code editor that bet the company on a VS Code fork.**

Cursor crossed $2B+ ARR by forking VS Code instead of building an extension. This teardown examines the architectural bet that unlocked codebase-wide indexing and multi-file agents, the economic logic behind proprietary models for completions vs. frontier APIs for complex tasks, and the existential question: what happens to the IDE if coding becomes prompt-driven?

<kbd>Architecture</kbd> <kbd>Build vs. Buy</kbd> <kbd>Model Cost Layering</kbd> <kbd>Enterprise GTM</kbd>

[📄 **Read the Teardown (PDF)**](https://drive.google.com/file/d/1j51giyhsyUaT1bBklknECJxTUmBzHPHl/view) · [📁 Browse Files](./01-cursor-ai)

</td>
<td width="50%" valign="top">

### 🟩 Perplexity AI

**The answer engine that tried ads, then killed them.**

Perplexity abandoned advertising in Feb 2026 after concluding that sponsored answers undermined the trust their product depends on. This teardown maps the five-stage RAG pipeline powering cited answers, analyzes the subscription-only bet against Google's $200B ad machine, and asks whether trust-first monetization can survive at scale.

<kbd>RAG Pipeline</kbd> <kbd>Monetization Strategy</kbd> <kbd>Citation as Product</kbd> <kbd>Trust Economics</kbd>

[📄 **Read the Teardown (PDF)**](https://drive.google.com/file/d/1Qt7QQc_oPiBIQdH4flWX7SiV2P5ObnLX/view) · [📁 Browse Files](./02-perplexity-ai)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🟧 Claude / Anthropic

**The company that turned AI safety into a $14B revenue engine.**

Anthropic reached $14B run-rate revenue with 80% from enterprises and 500+ customers at $1M+. This teardown analyzes how Constitutional AI became a go-to-market strategy, the multi-surface architecture spanning claude.ai, API, Claude Code, and Cowork, and the three-cloud distribution play no other frontier model has replicated.

<kbd>Constitutional AI as GTM</kbd> <kbd>Model Tiering</kbd> <kbd>Multi-Cloud</kbd> <kbd>Platform Architecture</kbd>

[📄 **Read the Teardown (PDF)**](https://drive.google.com/file/d/1GCsQcl7u9bj-AJp3srHbHqJsHjZNIYnp/view) · [📁 Browse Files](./03-claude-anthropic)

</td>
<td width="50%" valign="top">

### 🟥 OpenMRS

**The open-source EMR that teaches you what's inside the healthcare black box.**

While the other three teardowns cover AI-native products, this one covers the healthcare infrastructure layer any AI product must integrate with. OpenMRS runs in 40+ countries, and its concept dictionary, EAV data model, and FHIR APIs define how clinical data is actually structured — and where AI creates real value vs. where the data isn't ready.

<kbd>Healthcare Data Architecture</kbd> <kbd>FHIR</kbd> <kbd>AI in Global Health</kbd> <kbd>Open Source Strategy</kbd>

[📄 **Read the Teardown (PDF)**](https://drive.google.com/file/d/1ozLmUzBWiWXoBJjy_JOKepiF8Gau3ZSt/view) · [📁 Browse Files](./04-openmrs)

</td>
</tr>
</table>

---

## Skills Demonstrated

<table>
<thead>
<tr>
<th align="left">Domain</th>
<th align="left">What These Teardowns Show</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>🎯 Product Strategy</strong></td>
<td>Market positioning, build-vs-buy decisions, monetization trade-offs, competitive response planning</td>
</tr>
<tr>
<td><strong>🔧 Technical Architecture</strong></td>
<td>System design analysis, model routing, RAG pipelines, API design patterns, EAV data modeling</td>
</tr>
<tr>
<td><strong>📊 Business Analysis</strong></td>
<td>Unit economics, margin structure, revenue mix analysis, enterprise vs. consumer growth dynamics</td>
</tr>
<tr>
<td><strong>🤖 AI/ML Product Sense</strong></td>
<td>Model cost layering, inference optimization, proprietary vs. frontier API trade-offs, safety-as-GTM</td>
</tr>
<tr>
<td><strong>🏥 Healthcare Domain</strong></td>
<td>EMR architecture, FHIR interoperability, clinical data models, regulated-industry product constraints</td>
</tr>
<tr>
<td><strong>✍️ Strategic Communication</strong></td>
<td>Every recommendation includes trade-offs. No hand-waving. Sources cited throughout.</td>
</tr>
</tbody>
</table>

---

## Repo Structure

```
ai-pm-teardowns/
│
├── 01-cursor-ai/
│   ├── README.md
│   ├── cursor-ai-teardown.pdf
│   ├── architecture-diagram.svg
│   └── competitive-landscape.svg
│
├── 02-perplexity-ai/
│   ├── README.md
│   ├── perplexity-ai-teardown.pdf
│   ├── architecture-diagram.svg
│   └── competitive-landscape.svg
│
├── 03-claude-anthropic/
│   ├── README.md
│   ├── claude-anthropic-teardown.pdf
│   ├── architecture-diagram.svg
│   └── competitive-landscape.svg
│
├── 04-openmrs/
│   ├── README.md
│   ├── openmrs-teardown.pdf
│   ├── architecture-diagram.svg
│   └── competitive-landscape.svg
│
└── README.md              ← You are here
```

Each folder contains the full teardown PDF, architecture diagram, competitive landscape map, and a folder-level README. Start with whichever product interests you — they stand alone, though together they tell a broader story about how AI products compete on architecture, trust, and distribution.

---

## Methodology

These are not summaries of press coverage. Each teardown is built from primary sources: company announcements, published architecture documentation, engineering deep-dives, and direct product experience. Where figures are estimated or reported, they are labeled as such. Where a judgment call is made, it is stated explicitly.

---

<p align="center">
  <sub>AI Technical Product Manager Portfolio · All analysis reflects publicly available information as of March 2026</sub>
</p>
