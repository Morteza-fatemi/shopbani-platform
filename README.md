# ShopBani — Engineering Case Study / مطالعهٔ موردی شاپ‌بانی

> Public, sanitized architecture notes for a real e-commerce engineering engagement. This is **not** the production codebase and contains no customer records, business secrets, deployment addresses or independently audited performance claims.

**[Case study](CASE_STUDY.md) · [Architecture](ARCHITECTURE.md) · [Synthetic interactive demo](demo/index.html) · [Roadmap](ROADMAP.md)**

شاپ‌بانی یک پلتفرم فروشگاه اینترنتی چندبخشی است که سمت مشتری، مدیریت و API مستقل دارد. این مخزن رویکردهای فنی توسعه و بهره‌برداری را بدون انتشار سورس اختصاصی توضیح می‌دهد.

## Scope presented (sanitized)
- Customer storefront and administration experiences built with Next.js.
- NestJS application/backend orchestration.
- PostgreSQL and MongoDB-backed workflows where appropriate; Redis for caching/short-lived coordination.
- Queue/background processing, media/object-storage workflows and service monitoring.
- Controlled AI-facing reporting integrations as a separate integration concern.

**Proof boundary:** The public repo presents a technically grounded narrative and synthetic examples, **not** a production benchmark or a claim that every suggested control has been implemented.

## What reviewers can inspect
- [Problem, responsibilities, operational lessons and validation boundary](CASE_STUDY.md)
- [Service/data flow and failure-mode architecture](ARCHITECTURE.md)
- [Offline demonstration using invented records](demo/index.html) — download the HTML file and open it locally; not a live ShopBani connection.
- [Publication and engineering roadmap](ROADMAP.md)

## Confidentiality
No live orders, customer names, private URLs, API keys, infrastructure topology, vendor contracts, incident tickets or real environment variables are published. Quantities in the demo are **synthetic**.
