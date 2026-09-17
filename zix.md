# Zix — Legacy Page Brief

**Template:** A — Absorbed Brand
**Current URL:** `/legacy/zix/`
**Current-product mapping:** OpenText Email Security (Encryption / Continuity)

## Current performance (12mo GSC)

- 15,606 clicks · 1,887,839 impressions · 0.83% CTR · avg. position 28.5
- **Flag before optimizing:** this page's impressions and blended CTR/position
  are almost certainly distorted by the query-contamination issue already
  identified (adult-content and unrelated junk queries showing high
  impressions against this URL). Diagnose and resolve that first — see the
  technical investigation steps from the earlier analysis. The content
  changes below are still correct regardless of the contamination outcome,
  but don't judge success/failure against the current CTR/position numbers
  until the contamination is confirmed cleared.

## Query intent (from GSC "Top queries", branded-query subset only)

| Query | Clicks | Intent |
|---|---|---|
| zix | 3,325 | Navigational — brand recall (ranks well individually: pos 2.45) |
| zixcorp | 278 | Navigational |
| zix secure email | 261 | Informational/product |
| zix support | 206 | Transactional — support |
| zix login | 164 | Transactional — account access |
| zix message center | 56 | Transactional — product feature access |
| zix mail / zixmail | ~103 combined | Product feature |

**Assumption:** similar to AppRiver, dominant real (non-contaminated) intent
is existing-customer navigation (login, support, message center access), with
somewhat more product-feature-specific queries (encryption, message center)
than AppRiver's cluster.

## Page content

### Eyebrow context strip
> You're on the OpenText Cybersecurity site — Zix's marketing site has been
> consolidated here. Your account portal, support, and product are all still
> active below.

### Hero
**Eyebrow:** Formerly Zix
**H1:** Zix is now OpenText Email Security
**Body:** The same encrypted email, archiving, and compliance tools you rely
on — now part of the full OpenText Cybersecurity portfolio. Your service,
pricing, and support are unchanged.

### Routing cards

1. **Account & Login** — Access your Zix account and admin console. →
   Secure Cloud Login / Zix Central Login
2. **Support & Tickets** — Knowledge base, ZixMail downloads, and
   support@zixcorp.com / 888-576-4949. → Open a support ticket
3. **Message Center** — View and manage encrypted messages. → Zix Message
   Center Login
4. **Explore Email Security** — See the current OpenText email security
   suite. → Product page (visually distinct, dark card)

### Quick history (one line)
> Zix was acquired by OpenText in 2021. Your pricing, contract, and SLA are
> unchanged — only the parent brand has.

### Related resources (3)
- Data Sheet: Email Encryption Overview
- Blog: What Happens to Encrypted Email Recipients
- Webinar: Protecting Sensitive Email: A Compliance Guide

## Notes for implementation
- Keep the "recipients of encrypted email should contact the sending
  organization's support group" guidance from the current live FAQ — this is
  specific, correct, and not something to compress into the one-line summary.
  Surface it as a short note under the Support card instead of a full FAQ
  entry.
- Do not treat this page's current CTR/position as a baseline until the
  contamination issue is resolved (see README and prior technical analysis).
