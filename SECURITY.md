# Security Policy

Tensormesh Platform runs inside our customers' own infrastructure. A weakness we ship stays
there until the customer upgrades it — so we want to hear about one early, and we handle
reports under a documented process aligned to ISO/IEC 30111 and ISO/IEC 29147.

## Reporting a vulnerability

**Preferred — through GitHub.** Use **Report a vulnerability** in the Security tab of this
repository. Your report is private to Tensormesh from the moment you submit it.

**By email.** `tmo-support@tensormesh.ai`, with a subject line beginning `[SECURITY]`.

Please do not open a public issue for a suspected vulnerability.

## What to include

- The affected product and version
- What an attacker can achieve
- Steps to reproduce
- **Whether you believe it is being exploited in the wild** — this changes how quickly we must act
- How you wish to be credited, including if you prefer not to be

## What to expect from us

| | |
|---|---|
| **Acknowledgement** | Within **2–3 business days**. We will confirm receipt and say when we will next be in touch — we will not confirm or deny the finding before we have assessed it |
| **Updates** | At least every 10 business days while the case is open, and sooner for anything severe |
| **Disclosure** | Coordinated. If you intend to publish, tell us and we will agree a date in writing; the norm is 90 days from report. **We publish by the agreed date whether or not our fix is ready** — with mitigation advice if that is all we have |
| **Credit** | Exactly as you asked, including anonymously |

## Scope

**In scope** — anything we ship as part of Tensormesh Platform: the operator, the CLI, the
operator UI, our Helm charts, and the container images we publish.

**Also send here** — issues in Tensormesh's own hosted services or websites. Say so in the
report and we will route it internally. One address is easier to remember than three.

**Out of scope** — findings in third-party software that we neither build nor ship. Where we
ship a third-party component, it is in scope: you received it from us.

## Advisories

Published in this repository under **Security → Advisories**, and linked from the product
documentation. Advisories for high-severity issues are also sent directly to affected
customers — publishing makes information available, it does not by itself inform someone
running our software in their own data centre.
