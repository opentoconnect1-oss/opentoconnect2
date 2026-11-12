# OPEN TO CONNECT — Creative & Content Marketing Agency Website

Multi-page creative agency website built with Next.js App Router, React, TypeScript, Tailwind CSS, Lucide React, and Framer Motion, positioning **OPEN TO CONNECT** around **four core capabilities inside one connected creative partnership**.

## Core Capabilities

1. **Social Media Management** (`/services/social-media-management`)
2. **Creative & Graphic Design** (`/services/creative-graphic-design`)
3. **Influencer Marketing** (`/services/influencer-marketing`)
4. **UGC Production & Campaign Management** (`/services/ugc-production`)

## Local Development & Verification

```bash
npm install
npm run dev
npx tsc --noEmit
npm run lint
npm run build
npm test
```

## Central Configuration (`src/config/site.ts` & `.env.example`)

- **WhatsApp Business**: Set `NEXT_PUBLIC_WHATSAPP_NUMBER` in `.env.local` (or `WHATSAPP_NUMBER` in `src/config/site.ts`) using international digits without spaces or `+`.
- **Contact & Socials**: Configure `NEXT_PUBLIC_CONTACT_EMAIL` and `siteConfig.socialLinks` once verified.
- **Resend Email Delivery (`/api/contact`)**: Configure server-only `RESEND_API_KEY`, `CONTACT_RECIPIENT_EMAIL`, and `CONTACT_FROM_EMAIL` in `.env.local`.
