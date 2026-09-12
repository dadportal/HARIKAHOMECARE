# HARIKAHOMECARE

**Harika Home Care Services** — Professional Care. Trusted People. Better Lives.

**Founder & CEO:** Praveen K  
**Phone:** +91 98765 43210  
**Email:** praveen@harikaservices.in  
**Web:** www.harikaservices.in  
**HQ:** Hyderabad, Telangana · Serving AP & Telangana

## Full platform (source of truth)

The complete functional app lives in the project folder:

```
harika-platform/live/index.html   ← full app (roles, CMS, booking, admin)
harika-platform/live/logo.png
harika-platform/live/logo-sm.png
```

### Push full app to this repo (from your machine)

```bash
cd path/to/harika-platform/live
# Copy into a clone of this repo
cp index.html logo-sm.png logo.png /path/to/HARIKAHOMECARE/
cd /path/to/HARIKAHOMECARE
git add index.html logo-sm.png logo.png
git commit -m "Full Harika platform: logo, CMS, roles, booking"
git push origin main
```

Then redeploy on Vercel.

### Login (OTP = 123456)

| Role | Phone |
|------|-------|
| Super Admin | 9999999999 |
| Admin | 8888888888 |
| Client | 9876543210 |
| Worker | 9123456780 |

### Features
- 100% width premium banner slider (CMS)
- Services CMS (EN + Telugu)
- OTP auth + RBAC (Client / Worker / Admin / Super Admin)
- Client dashboard + 6-step booking
- Worker jobs / verification workflow
- Admin: verify workers, assign bookings, banners, stats, services
- Official Harika logo (not redesigned)

### Vercel
1. https://vercel.com/new → import `dadportal/HARIKAHOMECARE`
2. Deploy (static)

© 2026 Harika Home Care Services · People Care Everyday
