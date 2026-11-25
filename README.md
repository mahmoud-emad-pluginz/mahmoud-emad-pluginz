# Mahmoud Emad

Full-stack developer in Cairo, Egypt. I build production business systems with **Next.js, TypeScript and Postgres**, and I own features end to end: database schema, row-level security, RPC functions, and the UI on top.

Currently at [PluginZ Solutions](https://pluginz.co), where I own four [Ops360](https://pluginz.co/ops360) modules: HR, applicant tracking, staff outsourcing and service desk.

---

## What I've built

**[PluginZ HR / ATS](https://github.com/Ma7moud-Emad/PluginZ-HR)** &nbsp;·&nbsp; [live](https://pluginzhr.vercel.app)
Multi-tenant HR and applicant-tracking platform. One Next.js app serving six surfaces: a public marketing site plus super-admin, HR-company, client-company, employee and candidate portals. 85 Postgres tables where **RLS is the security boundary**, not the React layer. Async PDF pipeline on a pg_cron queue, tenant-branded email outbox, JSON-LD job postings for Google Jobs. Vitest unit and RPC contract tests, Playwright smoke tests, CI on every PR.
`Next.js 16` `React 19` `TypeScript` `Supabase` `TanStack Query` `Zod` `Vitest` `Playwright`

**[AkhshabZ](https://github.com/Ma7moud-Emad/akhshabz)** &nbsp;·&nbsp; [live](https://akhshabz.vercel.app)
Arabic RTL invoicing and accounts system running in a real wood retailer. Cubic-metre pricing computed from dimensions, running customer and supplier balances, live stock, profit reporting. Migrated **8,533 invoices, 21,448 line items and 1,061 customer accounts** out of Excel into Postgres with a fully reconciled match.
`Next.js` `TypeScript` `Supabase` `Postgres RPC` `RTL`

**[Byway LMS](https://github.com/Ma7moud-Emad/Byway-Academy)** &nbsp;·&nbsp; [live](https://byway-academy.vercel.app)
Course marketplace with instructor, student and operations dashboards. Derived state lives in Postgres triggers: completing a lesson recomputes enrollment progress, and crossing 100% issues the certificate automatically.
`Next.js` `Supabase` `Zod` `React Hook Form` `Recharts`

**[Alpenglow Retreat](https://github.com/Ma7moud-Emad/Alpenglow-Retreat)** &nbsp;·&nbsp; [live](https://alpenglow-retreat.vercel.app)
Booking site and staff dashboard for a fifteen-cabin retreat on one database. Eleven Postgres functions handle aggregations, gap-filled sales series, and enquiry-to-booking conversion in a single transaction. The browser holds only an anon key.
`React` `Vite` `TanStack Query` `Styled Components` `Supabase`

**[Moonlight Store](https://github.com/Ma7moud-Emad/MoonLight-Store)** &nbsp;·&nbsp; [live](https://mooonlight.vercel.app)
E-commerce client over a REST API: catalog, search and filtering, cart and wishlist, JWT auth, cash-on-delivery and Stripe checkout, order history.
`React` `Redux Toolkit` `TanStack Query` `Formik` `Yup`

---

## Stack

**Languages** TypeScript · JavaScript · SQL
**Frontend** React 19 · Next.js (App Router, RSC, Server Actions) · Vite · Tailwind CSS · shadcn/ui · Styled Components
**Data** TanStack Query · TanStack Table · Redux Toolkit · Zustand · React Hook Form · Zod
**Backend** PostgreSQL · Supabase (Auth, Storage, Edge Functions) · Row Level Security · Postgres functions and triggers · pg_cron
**Testing & tooling** Vitest · Playwright · GitHub Actions · ESLint · Prettier · Vercel

Also comfortable with multi-tenant architecture, RBAC, Arabic RTL and i18n, technical SEO, and data migration.

---

## Contact

[Portfolio](https://ma7moud-emad-protfolio.vercel.app) · [LinkedIn](https://www.linkedin.com/in/mahmoud-emad-frontend) · [Email](mailto:mahmoud.emad.alfaramawy@gmail.com)

Open to full-stack and frontend roles.
