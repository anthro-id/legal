# Data Backups
**Anthro.id** performs automated backups that ran regularly both on [Google Cloud](https://cloud.google.com) and [Amazon Web Services](https://aws.amazon.com) to protect internal and users' data from loss.

# At Rest
All user data (especially [PII](https://en.wikipedia.org/wiki/Personal_data)-related) is encrypted at rest with the help of Google Cloud features.

# Transit
All user data is encrypted in-transit.

# Enforce Two-Factor to Restricted Access
Behind the scenes, we secure access to our infrastructure using multi-factor authentication, which includes TOTP and physical security keys (available only to Platform developers), ensuring the highest level of protection.

Some of our volunteers and team members are granted fine-grained access control, meaning they can only access specific areas. For example, those responsible for billing management are assigned roles that allow them to manage payments and infrastructure-related expenses.

# Separated Environments
We separate development, staging, and production environments to ensure product stability. User data is and will never be stored or manipulated in any way, shape, or form, in non-production environments.

# DDoS Protection
**Anthro.id** uses [Cloudflare](https://cloudflare.com) to mitigates against DDoS attacks.