# cloudflare-domain

Manages the Cloudflare zone and attaches custom domains to environment-specific Worker services (web-console-next)

Terraform-managed infrastructure for cloudflare-only-saas, per environment (`stage`, `prod`; `dev` is verify-only and provisions nothing).

## Depends on

- **web-console-next** — Next.js 15 + opennextjs/cloudflare delivery of the cloudflare-only-saas web console (per-environment, Workers + Static Assets)

## Depended on by

- (none)
