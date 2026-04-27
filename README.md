# Moflay documentation

Official developer documentation for **[Moflay](https://moflay.com)**—infrastructure for integrating **M-Pesa** payments. Moflay sits on top of **Safaricom Daraja** and provides a REST API, Node.js SDK, signed webhooks, environments, credential management, and dashboard tooling.

**Published site:** [moflay.com/docs](https://moflay.com/docs)

## What’s in this repo

Content is built with [Mintlify](https://mintlify.com). The site map lives in [`docs.json`](docs.json).

| Area | Topics |
|------|--------|
| **Get started** | Introduction, account setup, API keys, first payment (SDK and raw HTTP), SDK overview, how Moflay works |
| **Dashboard** | Environments, credentials, credential security, API keys |
| **Webhooks** | Overview, signature verification, events, retries and idempotency |
| **Go live** | Production Daraja credentials, go-live checklist |
| **Examples** | Express payments, customer management, transaction management |
| **API reference** | Authentication, errors, rate limits, pagination; OpenAPI from `https://api.moflay.com/openapi` |

## Quick start (read the docs)

1. Create an account in the [Moflay dashboard](https://app.moflay.com).
2. Create a sandbox API key (see **Create an API key** in the docs).
3. Send a test M-Pesa Express payment with the SDK or HTTP API.
4. Configure webhooks for signed payment events.
5. When ready, add production credentials and follow the go-live checklist.

Entry points in this repo: [`introduction.mdx`](introduction.mdx), [`first-payment.mdx`](first-payment.mdx), [`first-payment-http.mdx`](first-payment-http.mdx).

## Local preview (contributors)

1. Install the [Mintlify CLI](https://mintlify.com/docs/installation):

   ```bash
   npm i -g mintlify
   ```

2. From the repository root (where `docs.json` is), run:

   ```bash
   mintlify dev
   ```

   Alternatively, without a global install:

   ```bash
   npx mintlify@latest dev
   ```

## Links

- **Dashboard:** [app.moflay.com](https://app.moflay.com)
- **Support:** [support@moflay.com](mailto:support@moflay.com)
- **X:** [@moflaypay](https://x.com/moflaypay)
- **GitHub:** [github.com/moflay](https://github.com/moflay)
