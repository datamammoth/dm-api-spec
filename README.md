# DataMammoth API v2 — OpenAPI Specification

The official OpenAPI 3.1 specification for the [DataMammoth REST API v2](https://data-mammoth.com/api-docs).

## Quick Links

| Resource | URL |
|----------|-----|
| Interactive API Reference | [data-mammoth.com/api-docs/reference](https://data-mammoth.com/api-docs/reference) |
| Developer Guides | [data-mammoth.com/api-docs/guides](https://data-mammoth.com/api-docs/guides) |
| Downloads | [data-mammoth.com/api-docs/downloads](https://data-mammoth.com/api-docs/downloads) |

## Files

| File | Description |
|------|-------------|
| `openapi-v2.json` | OpenAPI 3.1 specification (JSON) — import to Postman |
| `openapi-v2.yaml` | OpenAPI 3.1 specification (YAML) — human readable |
| `dm-api-v2.postman_collection.json` | Postman Collection v2.1 (109 requests with tests) |
| `dm-api-v2.postman_environment.json` | Postman Environment — Production |
| `dm-api-v2-local.postman_environment.json` | Postman Environment — Local |

## Import to Postman

1. Open Postman → **Import** → Upload Files
2. Select `dm-api-v2.postman_collection.json`
3. Import `dm-api-v2.postman_environment.json`
4. Set your API key in the environment variables

## Spec Stats

- **Version**: 2.0.0
- **Endpoints**: 105 operations across 75 paths
- **Tags**: Health, Servers, Products, Billing, Support, Account, Admin, Affiliate, Webhooks, Tasks
- **Full response schemas** with typed models for every endpoint

## SDKs

| Language | Package | Repo |
|----------|---------|------|
| Python | `pip install datamammoth` | [dm-python](https://github.com/datamammoth/dm-python) |
| Node.js | `npm install @datamammoth/sdk` | [dm-node](https://github.com/datamammoth/dm-node) |
| Go | `go get github.com/datamammoth/dm-go` | [dm-go](https://github.com/datamammoth/dm-go) |
| PHP | `composer require datamammoth/sdk` | [dm-php](https://github.com/datamammoth/dm-php) |
| CLI | `brew install datamammoth/tap/dm` | [dm-cli](https://github.com/datamammoth/dm-cli) |

## License

MIT — see [LICENSE](LICENSE).
