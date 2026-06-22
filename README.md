# Mitumba Platform Status

[![Uptime CI](https://github.com/MTBTools/status/actions/workflows/uptime.yml/badge.svg)](https://github.com/MTBTools/status/actions/workflows/uptime.yml)

> Live status page: [status.mitumba.stanl.ink](https://status.mitumba.stanl.ink)

Real-time monitoring of all Mitumba platform services. Powered by [Upptime](https://upptime.js.org).

## Monitored Services

| Service | URL |
|---|---|
| Marketplace App | `app.mitumba.stanl.ink` |
| API Gateway | `api.mitumba.stanl.ink/health` |
| Auth Service | `api.mitumba.stanl.ink/auth/health` |
| Listings Service | `api.mitumba.stanl.ink/listings/health` |
| Orders Service | `api.mitumba.stanl.ink/orders/health` |
| Payments Service | `api.mitumba.stanl.ink/pay/health` |
| VAZI Engine | `api.mitumba.stanl.ink/vazi/health` |
| Search Service | `api.mitumba.stanl.ink/search/health` |
| Notifications | `api.mitumba.stanl.ink/notify/health` |
| CDN (Images) | `cdn.mitumba.stanl.ink` |
| Marketing Site | `mitumba-marketing.pages.dev` |

## How It Works

- GitHub Actions pings all endpoints every **10 minutes**
- If a service goes down → GitHub Issue is auto-created
- When it recovers → issue is auto-closed
- Response time graphs generated daily
- Status page hosted on GitHub Pages (free custom domain)

## Incidents

All incidents are tracked as [GitHub Issues](https://github.com/MTBTools/status/issues) in this repo.
