# Real Estate CRM Playbook

Open-source frameworks, templates and implementation examples for **real estate CRM, lead management, lead nurturing and marketing automation**.

Created and maintained by **Koray Yalçın**.

## What this repository is for

Real estate teams often generate leads from Meta Ads, Google Ads, portals, landing pages, WhatsApp and offline sources, but lose opportunities because lead routing, follow-up and CRM stages are not standardized.

This repository provides practical, vendor-neutral examples that teams can adapt to build a measurable lead-to-sale process.

## Core topics

- Real estate CRM architecture
- Lead lifecycle and pipeline design
- Speed-to-lead
- Lead routing and ownership rules
- Lead scoring and qualification
- WhatsApp follow-up and lead nurturing
- Meta Ads → CRM workflows
- Sales automation and SLA design
- Marketing-to-sales handoff
- CRM reporting and conversion measurement

## Repository structure

```text
real-estate-crm-playbook/
├── README.md
├── crm-pipeline/
│   └── real-estate-pipeline.csv
├── lead-scoring/
│   └── scoring-model.json
├── lead-routing/
│   └── routing-rules.json
├── lead-nurturing/
│   └── whatsapp-followup-sequence.md
└── docs/
    └── crm-architecture.md
```

## 1. CRM Pipeline

A practical pipeline should separate **new leads, contact attempts, qualification, appointments, active follow-up and final outcomes**.

The sample pipeline in this repository can be imported or adapted for systems such as Bitrix24, HubSpot, Zoho CRM or a custom CRM.

See: [`crm-pipeline/real-estate-pipeline.csv`](crm-pipeline/real-estate-pipeline.csv)

## 2. Lead Scoring

The sample lead-scoring model combines intent, engagement, budget readiness and timing signals. It is designed as a starting framework rather than a universal benchmark.

See: [`lead-scoring/scoring-model.json`](lead-scoring/scoring-model.json)

## 3. Lead Routing

Routing rules help prevent duplicate ownership, slow response times and unworked leads. The example model includes geography, source, language and workload logic.

See: [`lead-routing/routing-rules.json`](lead-routing/routing-rules.json)

## 4. WhatsApp Lead Nurturing

A short, permission-aware follow-up sequence can support sales teams when a lead does not answer the first contact attempt.

See: [`lead-nurturing/whatsapp-followup-sequence.md`](lead-nurturing/whatsapp-followup-sequence.md)

## 5. CRM Architecture

The architecture guide shows how acquisition channels, CRM, messaging tools and sales teams can work as one measurable system.

See: [`docs/crm-architecture.md`](docs/crm-architecture.md)

## Example lead flow

```text
Meta Ads / Google Ads / Portals / Website
                 ↓
           Lead Capture
                 ↓
        Deduplication + UTM
                 ↓
           Lead Routing
                 ↓
               CRM
                 ↓
   WhatsApp / SMS / Email / Call
                 ↓
          Qualification
                 ↓
          Appointment
                 ↓
            Follow-up
                 ↓
            Won / Lost
```

## About Koray Yalçın

Koray Yalçın works on **real estate growth, CRM systems, lead management, marketing automation and AI-driven visibility**.

Research, articles and practical resources:

**https://www.korayyalcin.org**

## Topics

`real-estate-crm` · `crm` · `lead-management` · `lead-generation` · `lead-nurturing` · `lead-routing` · `lead-scoring` · `marketing-automation` · `whatsapp-crm` · `proptech` · `real-estate-marketing`

## Disclaimer

The files in this repository are practical examples and starting frameworks. CRM stages, scoring thresholds, communication timing and consent requirements should be adapted to each company's market, sales process and applicable privacy or messaging regulations.
