# HARIKAHOMECARE

**Harika Care & Services** — Professional Care. Trusted People. Better Lives.

## Full functional app (not a demo shell)

Open `index.html` (or deploy to Vercel). All data persists in browser storage and is fully editable via Admin CMS.

### Roles (real login)
| Role | Phone | OTP |
|------|-------|-----|
| Super Admin | 9999999999 | 123456 |
| Admin | 8888888888 | 123456 |
| Client | 9876543210 | 123456 |
| Worker (verified) | 9123456780 | 123456 |
| Worker (pending) | 9123456783 | 123456 |

### What works
- **100% width premium banner slider** (CMS controlled)
- **Services grid** from CMS (add/edit/delete/activate)
- **Trust stats** from CMS
- **OTP auth** with role picker (Client / Worker / Admin / Super Admin)
- **Client dashboard** — bookings, profile, new booking
- **Worker dashboard** — jobs, accept, start/complete, earnings, document submit
- **Admin / Super Admin** — users, worker verify (approve/reject), assign workers to bookings, Services CMS, Banners CMS, Stats CMS
- **6-step booking** saved to real store
- **EN + Telugu** on booking & assistant
- **Chatbot** trained on services

### Deploy Vercel
1. vercel.com/new → import `dadportal/HARIKAHOMECARE`
2. Deploy (static)

### Local
```bash
python3 -m http.server 8080
# open http://localhost:8080
```

Replace `index.html` with the latest from project `live/index.html` if the repo copy is older.

© Harika Care & Services
