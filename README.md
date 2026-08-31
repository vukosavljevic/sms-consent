# SMS Consent — Solari Storage

Public evidence page for Twilio A2P 10DLC review. Documents how Solari Storage collects SMS consent from customers and representatives.

**Production URL:** `https://solaristorage.com/sms-consent`

## Deploy on Netlify

1. Push this repo to GitHub (or connect your existing repo).
2. In Netlify: **Add new site → Import an existing project**.
3. Build settings:
   - **Build command:** *(leave empty)*
   - **Publish directory:** `.` (repo root)
4. Deploy.

The included `netlify.toml` already sets the publish directory and redirects `/` to `/sms-consent/`.

### Custom domain

Point `solaristorage.com` (or a subdomain) to Netlify, then set the primary domain in **Domain management**. The page will be available at `/sms-consent/`.

## Local preview

```bash
npx serve .
```

Open [http://localhost:3000/sms-consent/](http://localhost:3000/sms-consent/).

## Screenshots (required before Twilio resubmit)

Capture **real CRM screenshots** (not mockups) and place them at:

| File | Source in CRM |
|------|----------------|
| `sms-consent/customer-intake.png` | Setter Intake → Availability → SMS Appointment Notifications |
| `sms-consent/closer-settings.png` | Closer Dashboard → Settings → Notifications |

Until those files exist, the page shows dashed placeholders. Replace them before submitting your A2P campaign.

## Checklist

- [ ] Page loads at `/sms-consent/` without login
- [ ] Screenshot A added (`customer-intake.png`)
- [ ] Screenshot B added (`closer-settings.png`)
- [ ] Disclosure text matches CRM word-for-word
- [ ] STOP and HELP mentioned in both sections
- [ ] Public URL verified in an incognito window
- [ ] Twilio A2P campaign updated with this URL
