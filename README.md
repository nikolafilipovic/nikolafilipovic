# Nikola Filipović

Technology leader in Belgrade. I own technology, delivery and operations for a consulting group working across Europe, the US and the Middle East, and I still design the systems and write the code.

Twelve years, one arc: engineer, project manager, solutions architect, head of operations, COO. The work itself has not changed much. Understand it, simplify it, integrate it, build what comes next. Only the scale has.

## What I am building now

**[moja-zajednica](https://mojazajednica.rs)** — housing community management for the Serbian market, built and shipped solo. Residents get the building in their pocket for free: the monthly bill with an IPS QR code that pays from any mobile bank, fault reports with a photo and a status trail, electronic voting on building decisions under the 2016 law, notices, and every document from assembly minutes to supplier contracts in one place. Professional managers pay the subscription. Android on Google Play, iOS planned. Public pricing and a published market comparison, including the lines where competitors are ahead.

**moja-zajednica-scraper** — the open data side of the same problem. Serbia has 57,223 registered housing communities and no accessible public picture of who manages them. This builds a structured, queryable dataset of registered communities and their appointed managers from public sources, so residents can find out who runs their building without filing a request. Python.

## Selected work

Client engagements are under NDA and are described by profile rather than by name.

**Enterprise eCommerce and web-to-print platform** (2018–2021, S&P 1000 manufacturer)
Inherited a 2.5 million line undocumented .NET monolith with ERP data on fragile paths and no production interruption permitted. Moved the full production estate to AWS with no service interruption, reworked the ORM layer, decomposed the monolith toward services, integrated the ERP, centralised authentication and single sign-on, and certified three payment integrations (Braintree, Cybersource, Stripe) carrying roughly $10M in annual collections. Platform revenue went from $20M to $80M ARR over the programme. Led 11 engineers, later restructured into two teams of six.

**Group technology and security, built from zero** (2021–present)
Identity, collaboration, access governance and security baseline for a ~90 person group across two legal entities and three workforce types. Certification and audit programmes, enterprise third-party risk assessments, and the site-to-site topology connecting the office, AWS and client VPCs.

**AI product data platform** (2026, US distributor)
~50,000 SKUs from ~80 manufacturer sources in mixed formats, normalised against one schema. A frontier model on Amazon Bedrock reads each raw record plus retrieved context and emits a normalised record with per-field confidence scores. High confidence auto-publishes, the rest routes to a human review queue, and every correction becomes labelled training data. Write-back to the source-of-truth ERP goes through approved paths only, on targeted fields, fully audited. One base schema prompt plus a thin per-vendor instruction file replaces eighty parsers.

## How I think about building

- A plan written before the inventory is a guess wearing a suit.
- Standards fail on adoption, not on design. Standards people help write are standards they defend.
- Every recurring cost floor is a decision, made explicitly, before it is committed. On the platform above, on-demand inference at $1.5–3k per full catalogue pass beat a $15–18k monthly provisioned floor, and deferring the fine-tune kept the option alive at no extra cost.
- Confidence scores and a review gate are cheaper than an incident.

## Stack

**These projects.** Cloudflare Workers and Pages, R2 for object storage, Hetzner with Docker for anything that needs a real box. Python and TypeScript. Small, cheap, and boring to operate on purpose.

**The day job.** AWS since 2012: Lambda, Step Functions, DynamoDB, S3, Bedrock, VPC. .NET and Python. Kubernetes, CI/CD on GitHub Actions and Jenkins. Vector stores, RAG, agentic pipelines. Identity and SSO. Payments.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/filipovicnikola)

Most of my current work sits in private repositories. The contribution graph includes them.
