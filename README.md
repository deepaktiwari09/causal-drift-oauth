# Causal Drift Analytics — OAuth Information Site

Public product, privacy, and terms pages required for the Causal Drift Analytics Google OAuth application.

The analytics dashboard itself is local-only. This repository contains no OAuth credentials, YouTube data, analytics data, or dashboard source code.

## Pages

- `/` — application homepage
- `/privacy/` — privacy policy and Google/YouTube API disclosures
- `/terms/` — terms of use

## AWS hosting

The public compliance pages are deployed at `https://causal-drift.dt-workspace.com/` using:

- a private, encrypted, versioned S3 bucket in `ap-south-1`;
- CloudFront with Origin Access Control and TLS 1.2+;
- an ACM certificate in `us-east-1`;
- Route 53 A and AAAA alias records.

Infrastructure is declared in `infra/certificate.yaml` and `infra/site.yaml`.
