# PixnZip (pixnzip.com)

> **Proactive Website Observability & DMARC Email Security for Web Agencies, Freelancers & MSPs.**

[![Website](https://img.shields.io/badge/Website-pixnzip.com-1e3a2f?style=flat-square)](https://pixnzip.com)
[![Sign Up Free](https://img.shields.io/badge/Sign%20Up-Free%20Forever-16a34a?style=flat-square)](https://pixnzip.com/signup)
[![Dashboard Login](https://img.shields.io/badge/Login-Dashboard-2563eb?style=flat-square)](https://pixnzip.com/login)
[![Next.js](https://img.shields.io/badge/Next.js-16-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19-blue?style=flat-square&logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-v4-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-Proprietary-zinc?style=flat-square)](LICENSE)

---

## 🌟 Executive Overview

**[PixnZip](https://pixnzip.com)** is an all-in-one perimeter monitoring and email authentication governance platform engineered specifically for digital agencies, freelance web developers, and Managed Service Providers (MSPs).

Managing client websites typically means juggling fragmented point solutions or waiting for frantic client emails when an SSL certificate lapses, DNS records drift, or invoices bounce into spam due to missing DMARC records. PixnZip consolidates web availability and email security into a single, unified operational cockpit:

1. **Web Perimeter & Uptime Monitoring**: 60-second HTTP/HTTPS availability checks, SSL certificate health tracking, domain registry (RDAP) expiration watches, hourly DNS drift detection, and automated homepage content change diffing.
2. **Email Authentication & Deliverability Governance**: Unified DMARC policy enforcement, recursive SPF lookup-chain limits (RFC 7208 PermError prevention), DKIM selector monitoring, and automated aggregate report ingestion to discover unauthorized sending sources.
3. **Agency Care Plan Deliverables**: Multi-client portfolio grouping, automated monthly white-label PDF reports, and multi-recipient alert dispatching to power high-margin client retainers.

---

## 🚀 Key Features

### 1. High-Precision Uptime & Latency Probing
- **Sub-Minute Availability Probes**: Evaluates website health every 60 seconds on paid plans and every 5 minutes on the Free plan.
- **Latency Diagnostics**: Detailed response timing breakdown including DNS resolution, TLS handshake, and Time to First Byte (TTFB).
- **Dual-Check False-Alarm Suppression**: Every failed check is automatically verified with a secondary probe before an alert is dispatched, eliminating noisy false alarms.
- **Payload & Assertion Verification**: Validates expected HTTP response status codes and asserts essential keywords or HTML signatures.

### 2. DMARC, SPF & DKIM Email Security
- **DMARC Policy Enforcement**: Audits domain policies (`p=none`, `p=quarantine`, `p=reject`), alignment modes, and compliance rates to safeguard client domain reputation.
- **Recursive SPF Chain Guard**: Traverses DNS SPF mechanisms recursively to alert you before your records breach the RFC 7208 10-lookup limit.
- **DKIM Selector Health**: Validates public cryptographic key records, flags weak bit lengths, and detects broken selectors across client domains.
- **Aggregate Report (RUA) Ingestion**: Ingests and visualizes aggregate DMARC feedback to highlight legitimate vs. unauthorized sending servers worldwide.

### 3. Perimeter Integrity & Change Detection
- **SSL Certificate Lifecycle Management**: Tracks certificate authorities, validity chains, and subject names, issuing proactive alerts 30, 14, and 7 days before expiration.
- **Domain Registry & RDAP Tracking**: Continuously monitors top-level domain registries for expiration dates, registrar status codes, and redemption holds.
- **Hourly DNS Zone Drift Audits**: Watches essential DNS records (`A`, `AAAA`, `CNAME`, `MX`, `NS`) and notifies teams immediately if unauthorized changes or failures occur.
- **Homepage Content Regressions**: Takes normalized snapshots of monitored pages to alert developers of silent CMS crashes, white-screens, or unexpected layout shifts.

### 4. Agency Retainer & Client Deliverables
- **Multi-Client Grouping**: Organize monitors and domains by client organization for streamlined agency workflows.
- **White-Label Monthly Client Reports**: Generate executive-ready monthly uptime and deliverability summaries branded for client billing packages.
- **Multi-Recipient Incident Routing**: Dispatch notifications to internal developers or directly to designated client contacts with configurable escalation.

---

## 💡 How It Works

PixnZip operates entirely outside-in. There is no software to install, no WordPress plugin to update, and no access credentials to manage.

```
┌─────────────────────────────────┐
│  1. Add Client Website/Domain   │  Enter the public URL or email domain.
└────────────────┬────────────────┘  Zero plugins, zero tracking scripts, zero server access.
                 │
                 ▼
┌─────────────────────────────────┐
│  2. Continuous External Checks  │  Continuous multi-region probes check HTTP availability,
└────────────────┬────────────────┘  verify SSL validity, audit DNS zones, & evaluate DMARC.
                 │
                 ▼
┌─────────────────────────────────┐
│  3. Verified Alerts & Reports   │  Dual-probe confirmed incident notifications and executive
└─────────────────────────────────┘  white-label PDF reports for your monthly care plans.
```

---

## 💼 Solutions & Use Cases

| Solution | Target Audience | Primary Benefit |
| :--- | :--- | :--- |
| **Website Care Plans** | Digital & WordPress Agencies | Transform ad-hoc site maintenance into recurring retainers ($250–$1,200/mo) with automated white-label reports. |
| **Email Deliverability** | B2B Marketers & Agencies | Ensure client newsletters and transactional emails reach the primary inbox under Google and Yahoo sender guidelines. |
| **Freelance Web Developers** | Independent Developers | Peace of mind post-launch with automated SSL renewals, domain expiration watches, and instant downtime notices. |
| **Multi-Tenant Fleet Ops** | Managed Service Providers | Consolidate dozens of client domains, uptime monitors, and DNS audits into one multi-tenant dashboard. |
| **E-Commerce Observability** | Online Retailers & Stores | Guard checkout funnels against silent outages, gateway timeouts, and broken SSL certificates. |

---

## 💳 Transparent Pricing

Straightforward tiers designed for growing agencies and independent developers. No hidden fees or unexpected surcharges.

| Plan | Price | Website Monitors | DMARC Domains | Check Cadence | Incident Retention | Key Deliverables |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Free Monitoring** | **$0** (Forever) | 1 Website | — | 5 Minutes | 30 Days | Response latency tracking, instant email alerts |
| **Pro** | **$10** / month | Up to 10 Websites | 3 Domains | 1 Minute | 90 Days | SSL alerts, domain RDAP, DNS drift, content diffs |
| **Agency** *(Most Popular)* | **$20** / month | Up to 50 Websites | 10 Domains | 1 Minute | 1 Year | White-label PDF reports, client grouping, 10 alert recipients |
| **MSP** | **$50** / month | Up to 100 Websites | 25 Domains | 1 Minute | 1 Year | High-capacity ingestion, priority routing, unlimited recipients |

---

## 🛠️ Tech Stack Highlights

PixnZip is crafted using modern, industry-standard web technologies to ensure enterprise-grade reliability, security, and lightning-fast user experiences:

- **Frontend & App Framework**: [Next.js 16](https://nextjs.org/) (App Router) & [React 19](https://react.dev/)
- **Design System & Styling**: [Tailwind CSS v4](https://tailwindcss.com/) with Radix UI Primitives & [Lucide Icons](https://lucide.dev/)
- **Data Visualizations**: [Apache ECharts](https://echarts.apache.org/) for real-time latency and deliverability dashboards
- **Type Safety**: [TypeScript 5](https://www.typescriptlang.org/) with [Zod](https://zod.dev/) runtime schema validation
- **Database Layer**: [PostgreSQL](https://www.postgresql.org/) & [TimescaleDB](https://www.timescale.com/) for high-resolution time-series metric aggregation
- **Testing & Quality Assurance**: [Vitest](https://vitest.dev/) for high-speed unit and integration test coverage

---

## 🚦 Getting Started (Sign Up & Onboarding Flow)

PixnZip is a fully hosted, multi-tenant monitoring platform. You do not need to clone source code, install server agents, or configure local runtimes to start monitoring your client fleet.

### Step 1: Create Your Account
- **Sign Up Free**: Go to **[pixnzip.com/signup](https://pixnzip.com/signup)**.
- **No Credit Card Required**: Start immediately on the Free Forever tier (1 website monitor with 5-minute checks) or choose a Pro, Agency, or MSP plan based on your fleet size.
- **Returning User?** Sign in directly at **[pixnzip.com/login](https://pixnzip.com/login)**.

### Step 2: Add Your First Client Website
1. In your PixnZip cockpit, click **Add Website** or **New Monitor**.
2. Enter your client's public URL (e.g., `https://example.com`) and assign an optional client organization label.
3. Select your check cadence (1-minute intervals on Pro/Agency/MSP, 5-minute on Free).
4. PixnZip will immediately perform an initial availability probe, audit the SSL certificate chain, check domain registry expiration, and inspect DNS records.

### Step 3: Add DMARC & Email Domains (Pro, Agency & MSP)
1. Navigate to the **DMARC Monitoring** section in your dashboard.
2. Enter your client's root domain (e.g., `example.com`).
3. Instantly review your domain's DMARC policy (`p=none`, `p=quarantine`, or `p=reject`), SPF recursion depth, and DKIM selector status.
4. Add your dedicated aggregate reporting address (`rua`) to your domain's DNS to enable automated aggregate XML report ingestion and unauthorized sender discovery.

### Step 4: Configure Team & Client Alert Channels
1. Navigate to **Settings** &rarr; **Alert Recipients**.
2. Add internal engineering emails or invite client stakeholders to receive direct notices.
3. Every alert is backed by dual-check verification to ensure your team is never woken up by false alarms.

### Step 5: Deliver White-Label Reports (Agency & MSP)
- Group monitors and domains by client organization.
- Download or schedule automated monthly white-label PDF reports with verified uptime SLA statistics, latency trends, and security audit proofs to include directly in your client retainer deliverables.

---

## 🛡️ Responsible Monitoring Standards

PixnZip is committed to safe and transparent web probing:

- **Identified User Agent**: All automated requests identify themselves clearly:
  ```text
  PixnZip-Monitor/2.0 (+https://pixnzip.com/bot)
  ```
- **Lightweight External Probing**: Only simple `GET` or `HEAD` requests are made to public URLs specified by verified account owners.
- **Zero Client Intrusiveness**: Operates entirely without local plugins, agent binaries, or database credentials on target client servers.

---

## ❓ Frequently Asked Questions

<details>
<summary><strong>Do I need to install anything on my clients' servers?</strong></summary>
<p>No. PixnZip checks from the outside, exactly as a real visitor or mail server would. There is no WordPress plugin to install, no script tag to add, and no server login credentials required.</p>
</details>

<details>
<summary><strong>How does PixnZip prevent false alerts?</strong></summary>
<p>Every failed request triggers an automatic secondary confirmation probe before an incident alert is dispatched. Alerts are only fired when failure is confirmed, saving your team from alarm fatigue.</p>
</details>

<details>
<summary><strong>Can my clients receive alerts directly?</strong></summary>
<p>Yes. On Pro, Agency, and MSP plans, you can add client team members as alert recipients. Each recipient confirms opt-in and can manage notification preferences with a single click.</p>
</details>

<details>
<summary><strong>How do monthly client reports work?</strong></summary>
<p>Agency and MSP tiers generate polished, white-label PDF reports detailing monthly uptime percentages, response time metrics, and security audit confirmations ready for inclusion in client retainer deliverables.</p>
</details>

<details>
<summary><strong>What happens if I downgrade or upgrade my subscription?</strong></summary>
<p>We enforce a strict zero-data-loss policy. If you downgrade, excess monitors are paused rather than deleted, keeping all historical metrics safe for when you choose to reactivate.</p>
</details>

---

## 📄 License & Attribution

Copyright &copy; 2026 PixnZip Technologies. All rights reserved.  
Unauthorized distribution, copying, or modification of this codebase is strictly prohibited.
