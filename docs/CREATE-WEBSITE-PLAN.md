# Create Website Plan

## Scope

Create a small, public, compliance-focused information site for the Causal Drift Analytics Google OAuth application. The site is not a marketing funnel and has no conversion goal.

## Phase Status

| Phase | Status | Reason |
|---|---|---|
| One-page marketing | skipped | Compliance information site; no acquisition goal |
| StoryBrand messaging | skipped | Product identity and purpose are already fixed |
| Made to Stick | skipped | Legal clarity takes precedence over persuasion |
| Top design | deferred | Functional, recognizable presentation is sufficient |
| Web typography | done | System font stack, responsive scale, readable measure |
| Refactoring UI | done | Constrained spacing, color, and component tokens |
| UX heuristics | done | Simple navigation, accessible landmarks, responsive layout |
| CRO methodology | skipped | No conversion action |
| Scorecard marketing | skipped | No lead capture |
| Steve Jobs review | deferred | Formal launch review is unnecessary for the compliance-only scope |

## Key Decisions

- AWS S3, CloudFront, ACM, and Route 53 provide the public HTTPS origin required by Google OAuth production mode.
- The analytics dashboard and PostgreSQL database remain local/LAN-only.
- The public site has no cookies, analytics scripts, authentication, or data collection.
- Privacy disclosures cover YouTube Data API, YouTube Analytics API, Composio, local storage, retention, revocation, deletion, and Google API Limited Use.
