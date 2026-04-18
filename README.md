# Zeni F&B OS · Platform

Hệ điều hành cho tương lai ngành F&B Việt Nam — Một nền tảng. Tám vai trò. Một hệ sinh thái.

## Deploy structure

| Path | Subdomain (production) | Nguồn |
| --- | --- | --- |
| `/index.html` | `zenifb.com` | Landing marketing |
| `/app/index.html` | `app.zenifb.com` | Prototype tương tác |
| `/docs/index.html` | `docs.zenifb.com` | Doc Portal (sẽ bổ sung) |

## Phase

- **Phase 1 (48h):** Static deploy lên Cloudflare Pages + SSL + CDN + OG + Analytics + Monitoring.
- **Phase 2 (8 tuần):** Full stack Next.js 14 + tRPC + Prisma + Supabase + 6 AI agents.

## Local preview

Mở trực tiếp `index.html` trong browser, hoặc chạy:

```bash
npx serve .
```

## Hosting

- **DNS + SSL + CDN:** Cloudflare
- **Static hosting:** Cloudflare Pages (connect GitHub → auto deploy)
- **Analytics:** Plausible / Cloudflare Web Analytics
- **Monitoring:** UptimeRobot

## Security headers

Xem `_headers` — áp dụng HSTS, CSP, X-Frame-Options, Permissions-Policy cho toàn site.

## License

Proprietary — Zeni Holdings © 2026. Distribution nội bộ.
