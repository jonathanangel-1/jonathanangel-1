# Jonathan Angel

I build applications that turn incoming information into evidence, decisions, and completed workflows.

The recurring engineering problem in these projects is deciding when information is strong enough to change state, recommend something, or authorize an action. Each repository includes the application source, a local demo, design reasoning, and a reproducible review path.

## Projects

| Project | Product | Engineering focus |
| --- | --- | --- |
| [JD Direct](https://github.com/jonathanangel-1/jd-direct-public) | Freight brokerage TMS, from an emailed RFQ through delivery and invoicing | Carrier negotiation, transactional booking, document analysis, driver geolocation, Persona identity evidence, and operator release gates. |
| [PQ Ops](https://github.com/jonathanangel-1/pq-ops-public) | Import-operations control room | Source provenance, conflicting shipment evidence, temporal resolution, unfinished paperwork, and authority to act. |
| [Angie](https://github.com/jonathanangel-1/angie-public) | Inspiration-to-product styling and outcome learning | Garment-level matching, source checks, bounded search recovery, fit evidence, confirmed feedback, and isolated QA memory. |

## A route through the work

- **For the complete system:** start with [JD Direct's RFQ-to-invoice walkthrough](https://github.com/jonathanangel-1/jd-direct-public/blob/main/docs/REVIEW.md), then its [design and tradeoffs](https://github.com/jonathanangel-1/jd-direct-public/blob/main/docs/ENGINEERING.md).
- **For evidence and operational decisions:** read [PQ Ops' engineering guide](https://github.com/jonathanangel-1/pq-ops-public/blob/main/docs/ENGINEERING.md), then inspect its [three synthetic cases](https://github.com/jonathanangel-1/pq-ops-public/blob/main/docs/REVIEW.md).
- **For recommendation and learning design:** follow [Angie's pipeline](https://github.com/jonathanangel-1/angie-public/blob/main/docs/ENGINEERING.md), then [reproduce recommendation, feedback, and saved outcomes](https://github.com/jonathanangel-1/angie-public/blob/main/docs/REVIEW.md).

These are public editions of working projects. Client records, personal data, credentials, and private Git history are excluded or replaced with fictional data. Demos run locally without API keys. External-service simulations are labeled; test results establish the documented software behavior, not live model accuracy or measured business impact.

### JD Direct · RFQ to invoice

[![JD Direct original TMS with fictional shipment data](https://raw.githubusercontent.com/jonathanangel-1/jd-direct-public/6bcd5ae1af22848519fa0bb48049aaa16264dc0d/docs/images/demo.png)](https://github.com/jonathanangel-1/jd-direct-public)

### PQ Ops · Shipment evidence and decisions

[![PQ Ops fictional shipment control room](https://raw.githubusercontent.com/jonathanangel-1/pq-ops-public/5a8499043de48251f21cef4f0df7b0b28c7fdf69/docs/images/demo.png)](https://github.com/jonathanangel-1/pq-ops-public)

### Angie · Recommendations and feedback

[![Angie fictional styling demo](https://raw.githubusercontent.com/jonathanangel-1/angie-public/main/docs/images/demo.png)](https://github.com/jonathanangel-1/angie-public)
