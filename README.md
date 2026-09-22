# Censio CRM — Design Reference Snapshot

**Frozen baseline of the original cenhub-crm UI** (before Supabase, Meta integration, and production work).

| | |
|---|---|
| **Purpose** | Compare original dashboard design vs production [`cenhub-crm`](https://github.com/Censio101/cenhub-crm) |
| **Live URL** | [censio-crm-sample.vercel.app](https://censio-crm-sample.vercel.app) |
| **Production repo** | [github.com/Censio101/cenhub-crm](https://github.com/Censio101/cenhub-crm) |

Do **not** develop new features here. All production work happens in `cenhub-crm`.

## What's in this snapshot

- Dashboard, Overblik, Leads, Kunder pages
- Demo/mock lead data and mock chart metrics
- No database, no Facebook API, no auth

## Local dev

```bash
npm install --legacy-peer-deps
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).
