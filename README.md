# HARIKAHOMECARE

**Harika Care & Services** — Professional Care. Trusted People. Better Lives.

Premium multi-sided care & workforce marketplace connecting families with verified service professionals across **Andhra Pradesh & Telangana** (India-ready).

## Live

- Production UI: deployed on Vercel from this repo
- Languages: English + Telugu
- Features: Marketing site, OTP login, 6-step booking, AI-ready chatbot with voice

## Brand

- Primary: `#063B3B` (Deep Teal)
- Secondary: `#4F9B5F` (Care Green)
- Accent: `#D8A443` (Warm Gold)
- Logo: original Harika logo (do not redesign)

## Stack (full monorepo in progress)

| Layer | Tech |
|-------|------|
| Web | Next.js 15 + TypeScript + Tailwind |
| Mobile | Expo (React Native) — role-based Client/Worker |
| API | NestJS + Prisma + PostgreSQL |
| Auth | Phone OTP + JWT |
| Deploy | Vercel (web) |

## Demo

1. Open the live site
2. **Find a Service** → complete booking flow
3. **Login** → any 10-digit number → OTP `123456`
4. Chat bubble → ask about services / pricing (EN or తెలుగు) · 🎤 voice supported

## Local

```bash
# Static preview
python3 -m http.server 8080

# Full stack (when DB configured)
cd harika-platform
cp .env.example .env
npm install
npx prisma db push && npm run db:seed
npm run dev:api
npm run dev
```

## Test accounts (seed)

| Role | Phone | Password |
|------|-------|----------|
| Super Admin | 9999999999 | Harika@2026 |
| Client | 9876543210 | Harika@2026 |
| Worker | 9123456780 | Harika@2026 |

---

© Harika Care & Services · People Care Everyday
