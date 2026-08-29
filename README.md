# Nikola Filipović

COO and General Manager at a consulting group in Belgrade, working with clients across Europe, the US and the Middle East. I run technology, infrastructure, security and delivery. I still design systems and write code.

Twelve years at one company, moving from engineering and project delivery through architecture and operations. No gap in the technical work.

## What I’m building

[**moja-zajednica**](https://mojazajednica.rs/) is housing community management software for Serbia, built and shipped solo.

Residents use it free. It covers monthly bills with IPS QR payments, fault reports with photos and status tracking, electronic voting under the 2016 law, notices and documents. Professional managers pay a subscription.

Available on Android. iOS is planned. Pricing and a direct comparison with competing services are published on the site, including where they are better.

**moja-zajednica-scraper** builds a structured dataset of Serbia’s 57,223 registered housing communities and their appointed managers from public sources. The goal is simple: let residents find out who manages their building without filing a formal request. Written in Python.

## Selected work

Client work is under NDA, so companies are described by profile.

**Enterprise eCommerce and web-to-print platform**  
*2018–2021 · S&P 1000 manufacturer*

Led the modernisation of a 2.5-million-line .NET monolith with no documentation, fragile ERP integrations and no room for production downtime.

The work included documenting the codebase, moving the production estate to AWS, reworking the ORM, breaking the platform into services, rebuilding ERP integrations, adding central authentication and SSO, and delivering certified Braintree, Cybersource and Stripe integrations handling about $10M a year.

Platform revenue grew from $20M to $80M ARR during the programme. I led 11 engineers, later split into two teams of six.

**Group technology and security**  
*2021–present · 90-person consulting group*

Built the group’s technology and security setup from scratch across two legal entities: identity, collaboration, access governance, security controls, certification and audit work, third-party risk reviews, and the network connecting our office, AWS and client VPCs.

**AI product data platform**  
*2026 · US distributor*

Designed a system that normalises 50,000 SKUs from 80 manufacturers into one schema.

A model on Amazon Bedrock processes each source record with retrieved context and returns normalised fields with confidence scores. High-confidence records publish automatically; the rest go to review. Corrections are kept as labelled data.

Writes back to the ERP are limited to approved fields and paths, with a full audit trail. The system uses one base schema prompt and a small instruction file per vendor instead of maintaining 80 separate parsers.

## Stack

Current projects: Cloudflare Workers and Pages, R2, Hetzner, Docker, Python and TypeScript.

Client work: AWS since 2012, including Lambda, Step Functions, DynamoDB, S3, Bedrock and VPC; .NET; Kubernetes; GitHub Actions; Jenkins; vector search and RAG; identity and SSO; payments.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/filipovicnikola)

Most of my current work is in private repositories. The contribution graph includes private contributions.
