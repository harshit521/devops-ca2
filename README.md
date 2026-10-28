# Docker & Container Security — Practical Assessment

## Student and repository details

- **Name:** Harshit Kumar Singh
- **Registration number:** `202401100100113`
- **PORT:** `93` (80 + last two registration-number digits, 13)
- **Docker Hub username:** `harshxhit`
- **Docker Hub image:** `https://hub.docker.com/r/harshxhit/fest-backend`
- **GitHub repository:** `https://github.com/harshit521/devops-ca2`

## What this repository contains

Three-tier FestPass app: Nginx frontend, Flask/Python API, PostgreSQL database. Compose uses an app network for frontend/backend and a separate data network for backend/database. PostgreSQL data is stored in a named volume.

## AI tools

- ChatGPT: used to explain the assessment and help prepare a starter project and command checklist. All commands, scan results, image digests, signatures and screenshots must be generated and checked on my own machine.
## Triviy reports
- Before scan : ../reports/trivy-before.txt
- After scan : ../reports/trivy-after.txt
## Published image

- `harshxhit/fest-backend:1.0.0` digest: **TODO: paste the digest printed by your successful push**
- `harshxhit/fest-backend:1.0` pushed: **TODO: confirm**
- `1.0.0` signature verified: **TODO: record your actual verification**
- `1.0.1` unsigned image rejected by `cosign verify`: **TODO: record your actual result**

## Evidence screenshots

Store genuine, unedited screenshots in `screenshots/`. The terminal prompt must show your registration number; browser evidence must show the address bar and Docker Hub username where applicable.

- `S1-2.png`
- `S1-3.png`
- `S2-2.png`
- `S2-3.png`
- `S2-4.png`
- `S3-1.png`
- `S3-3.png`
- `S4-1.png`
- `S4-2.png`
- `S4-3.png`
- `S5-1.png`
- `S5-2.png`
- `S5-3.png`
- `S5-4.png`

