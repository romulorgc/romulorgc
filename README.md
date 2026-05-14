# Ranieres Romulo Gomes Carvalho

**Solo founder · Full-stack engineer · Brasília-DF**

Construo SaaS verticais com IA em produção no Brasil. Do zero ao deploy sozinho —
backend, frontend, mobile, infra, design, growth, suporte. AI-native desde o dia 1.

> 6 produtos em produção · iOS aprovado pela Apple · Stack moderno · Compliance regulatório brasileiro

---

## Produtos em produção

### 🩺 HealthTech
**[Sinthoma](https://sinthoma.com.br)** — Prontuário clínico com IA pra psicólogos brasileiros. Análise psicodinâmica via Claude Sonnet 4.6, **anonimização PII em camada antes de chamar IA**, conformidade CFP 06/2019 + LGPD.
*Stack:* Next.js 16 · React 19 · Supabase (Postgres + RLS + Auth) · Stripe LIVE · Resend · Daily.co WebRTC (teleconsulta) · Z-API WhatsApp · Sentry com PII scrub

### 💰 FinTech
**[Criptotax Brasil](https://criptotax.pro)** — Cálculo automatizado de IRPF sobre criptoativos brasileiros. Suporte completo Lei 14.754/2023 + IN 1888 (Receita Federal). Geração de DARF (código 4600), GCAP, anexo Bens e Direitos.
*Stack:* monorepo Turbo · Next.js 14 · Prisma 6 · BullMQ + Redis · Stripe · cotações PTAX do Banco Central · custo médio ponderado oficial

### ⚖️ LegalTech
**[Juspronto](https://juspronto.com.br)** — Gestão jurídica multi-tenant pra escritórios de advocacia. **Integração nativa DataJud (CNJ) + Escavador** pra busca CNJ. Auth JWT com refresh rotation, roles granulares (sócio/advogado/estagiário/admin).
*Stack:* Express 5 · Next.js 16 · Prisma 5 · PostgreSQL · Zod 4 · React Query · Zustand

### 🏃 ConsumerTech
**[Runu](https://apps.apple.com/br/app/runu/id6766942426)** — Coach de corrida com IA pra iniciantes brasileiros. **Aprovado pela Apple, no ar na App Store BR (v1.0.3)** — 6 submissões superadas (mic icon, IAP race, audio mode, etc.).
*Stack:* React Native 0.85 · Expo SDK 55 · EAS Build · RevenueCat · Claude Haiku/Sonnet · HealthKit · Apple Sign In · Sandbox subscriptions

### Outros
- **Vó Zefa** — App de simpatias com IA (React Native + Claude)
- **Direito na Conta** — Calculadoras trabalhistas brasileiras + IA (iOS / Android)
- **Orbyt** — Crypto signals platform
- **Kora** — Em desenvolvimento

---

## Stack que toco em produção

**Linguagens:** TypeScript estrito · JavaScript · SQL avançado (PostgreSQL)

**Web:** Next.js 16 (App Router, Server Actions, RSC) · React 19 · TanStack Query v5 · Zustand · shadcn/ui · Radix · Tailwind v4 · Framer Motion

**Mobile:** React Native 0.85 · Expo SDK 55 · EAS Build · RevenueCat · HealthKit · App Store Connect API · Apple Sign In

**Backend:** Node.js · Express 5 · Prisma 5/6 · PostgreSQL · Supabase (RLS + Auth) · BullMQ · Redis · Zod 4

**IA aplicada:** Claude API (Haiku · Sonnet 4.6) · OpenAI · **prompt caching** · agent orchestration · PII anonymization · Whisper (transcrição) · ElevenLabs

**Pagamentos:** Stripe LIVE (webhooks 7 events, Connect, Subscriptions) · RevenueCat (mobile IAP) · Asaas (Pix BR, KYC, split)

**Infra:** Vercel (Edge Functions) · Cloudflare Pages · Cloudflare Workers · wrangler · auto-deploy CI/CD

**Observability:** Sentry com `beforeSend` PII scrub (LGPD-compliant) · PostHog (web + mobile) · BetterStack (uptime + logs)

**Realtime:** Daily.co WebRTC · WebSockets · Server-Sent Events

**Compliance BR:** LGPD (DPO, art. 18, anonimização) · CFP 06/2019 (prontuário) · IRPF + Lei 14.754/2023 (criptoativos) · IN 1888 (Receita Federal) · CLT

**SEO técnico:** Schema.org JSON-LD multi-entity · programmatic SEO · sitemaps dinâmicos · OpenGraph · Twitter Cards · Google Search Console

**APIs nacionais:** Receita Federal · DataJud (CNJ) · Banco Central PTAX · Z-API · Asaas Pix

---

## Como trabalho

- **Solo full-stack:** desenho, codifico, testo, deployo, suporto cada produto sozinho
- **AI-native:** IA aplicada desde o dia 1, não como feature decorativa — anonimização, prompt caching, fallbacks, evals manuais
- **Production-grade:** LIVE mode em pagamentos, RLS em todos os bancos, webhooks com retry exponencial, observability completa
- **Brasil-first:** compliance regulatório real (não "LGPD checkbox"), copy brasileira, integração com APIs nacionais reais

---

## Contato

- 🌐 [Sinthoma](https://sinthoma.com.br/sobre) · [Criptotax](https://criptotax.pro/sobre) · [Juspronto](https://juspronto.com.br/sobre) · [Runu](https://www.runu.com.br/sobre)
- 📍 Brasília, Brasil

---

*Ranieres Romulo Gomes Carvalho — Founder & Software Engineer.*
