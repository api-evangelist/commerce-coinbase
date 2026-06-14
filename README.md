# Coinbase Commerce

Coinbase Commerce is a merchant crypto payment solution enabling businesses to accept cryptocurrency payments natively. The platform provides REST APIs for creating payment charges, managing hosted checkouts, accessing payment metadata, configuring webhooks, and tracking crypto payment status across charge lifecycle events.

## APIs

### Coinbase Commerce Charges API (Legacy)

- **Base URL**: `https://api.commerce.coinbase.com`
- **Authentication**: `X-CC-Api-Key` header
- **Documentation**: https://commerce.coinbase.com/docs/api

Core operations:
- `POST /charges` — Create a new payment charge
- `GET /charges` — List all charges
- `GET /charges/{id}` — Retrieve a specific charge
- Webhook events: `charge:created`, `charge:pending`, `charge:confirmed`, `charge:failed`, `charge:delayed`, `charge:resolved`

### Coinbase Business Checkouts API (Current)

- **Base URL**: `https://business.coinbase.com/api/v1`
- **Authentication**: `Authorization: Bearer <JWT>`
- **Documentation**: https://docs.cdp.coinbase.com/coinbase-business/checkout-apis/overview

Core operations:
- `POST /checkouts` — Create a single-use hosted payment checkout
- `GET /checkouts` — List checkouts with filtering and pagination
- `GET /checkouts/{id}` — Retrieve a specific checkout
- `POST /checkouts/{id}/deactivate` — Cancel a checkout
- Webhook events: `checkout.payment.success`, `checkout.payment.failed`, `checkout.payment.expired`

## Pricing

- **Transaction fee**: 1% per completed payment
- **Monthly fee**: $0
- **Setup fee**: $0

## Resources

- [Commerce Homepage](https://commerce.coinbase.com)
- [Developer Documentation](https://docs.cdp.coinbase.com/coinbase-business/checkout-apis/overview)
- [Pricing & Fees](https://help.coinbase.com/en/commerce/getting-started/fees)
- [Migration Guide (Charges → Checkouts)](https://docs.cdp.coinbase.com/coinbase-business/checkout-apis/migrate-from-commerce/api-schema-mapping)
- [Webhooks Documentation](https://docs.cdp.coinbase.com/commerce/docs/using-webhooks)
- [Status Page](https://status.coinbase.com)
- [Support](https://help.coinbase.com/en/commerce)
