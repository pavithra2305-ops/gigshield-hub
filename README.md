

 One attachment
  •  Scanned by Gmail
<div align="center">

<img src="assets/banner.svg" alt="Income Shield AI Banner" width="100%"/>

# 🚀 Income Shield AI — Parametric Insurance for India's Gig Workforce

> *"Earn weekly. Pay weekly. Stay protected weekly."*

[![Hackathon](https://img.shields.io/badge/Guidewire-DEVTrails%202026-FF6B35?style=flat-square)](https://guidewire.com)
[![Team](https://img.shields.io/badge/Team-InnovateIT-0D1B2A?style=flat-square)](/)
[![Persona](https://img.shields.io/badge/Persona-Food%20Delivery%20(Swiggy%2FZomato)-FF9900?style=flat-square)](/)
[![Coverage](https://img.shields.io/badge/Coverage-Income%20Loss%20Only-02C39A?style=flat-square)](/)
[![Pricing](https://img.shields.io/badge/Pricing-Weekly%20Dynamic%20Model-028090?style=flat-square)](/)
[![Platform](https://img.shields.io/badge/Platform-React%20PWA-9C27B0?style=flat-square)](/)

**Phase 1 Submission — Ideation & Foundation**

[🚧 The Problem](#-the-problem) · [💡 Our Solution](#-our-solution) · [👤 Persona](#-persona--ravi-food-delivery-partner) · [🔁 Workflow](#-application-workflow) · [⚡ Triggers](#-parametric-triggers) · [🧠 AI/ML](#-aiml-architecture) · [💰 Pricing](#-weekly-premium-model) · [🛡️ Fraud Defense](#️-adversarial-defense--anti-spoofing) · [🏗️ Tech Stack](#️-tech-stack) · [👥 Team](#-team)

</div>

---

## 🚧 The Problem

India's platform-based delivery partners — Zomato, Swiggy, Zepto, Amazon, Dunzo — are the **backbone of our fast-paced digital economy**. However, external disruptions such as extreme weather, pollution, and natural disasters can reduce their working hours and cause them to **lose 20–30% of their monthly earnings**.

Currently, gig workers have **zero income protection** against these uncontrollable events. When disruptions occur, they bear the full financial loss with no safety net.

| Reality | Impact |
|---------|--------|
| Daily income loss per disruption | ₹300 – ₹800 |
| Monthly income at risk | 20–30% |
| Available insurance products | **Zero** |
| Compensation from platform | **None** |
| Backup savings buffer | Near zero |

> **The invisible risk zone:** Severe weather · Heavy pollution · Curfews & lockdowns · Road blockages — *No work. No pay. No safety net.*

---

## 💡 Our Solution

**Income Shield AI** is an AI-driven parametric income protection platform that models **real-time earning behavior** — computing exact income deviation for precise, context-aware payouts instead of just insuring events.

### Core Differentiators

| Feature | Description |
|---------|-------------|
| 🤖 **AI-Driven Income Protection** | Models real-time earning behavior, computes exact income deviation for precise payouts |
| ⚡ **Event-Driven Pipeline** | Predict → Detect → Validate → Compensate — fully automated, zero manual steps |
| 📍 **Hyperlocal Risk Intelligence** | Dynamic per-user weekly pricing based on location, disruption history, and seasonal patterns |
| 📊 **Real-Time Income Deviation** | Uses worker's 30-day baseline earnings and actual active hours lost during disruption |
| 💸 **Zero-Touch Claims** | Instant payout via UPI/bank — no forms, no calls, no waiting |
| 🛡️ **Dual-Layer AI** | Predictive risk modeling + behavioral fraud detection (Isolation Forest on 30-day rolling baseline) |
| 🌐 **Scalable Integration** | OpenWeatherMap API, CPCB AQI feeds, IMD rainfall alerts, civic disruption data |

> ⚠️ **Coverage Scope:** INCOME LOSS ONLY — not health, life, accidents, or vehicle repairs.
> ⚠️ **Pricing Model:** Weekly dynamic model aligned to gig worker earnings cycle.

---

## 👤 Persona — Ravi, Food Delivery Partner

### Who is Ravi?

```
Name        : Ravi
Age         : 26
City        : Chennai
Platform    : Swiggy / Zomato
Work Style  : 8–10 hours/day
Daily Income: ₹500–₹800 (order-dependent)
Savings     : Near zero — dependent on weekly earnings for rent, groceries, EMI
Insurance   : None — never had access to any income protection
```

### 🎬 Scenario: "A Day When Everything Goes Wrong"

> Ravi logs in at 1:00 PM, expecting a busy lunch shift.

**Normal start of day:**
- 📦 Orders start coming in steadily
- 💰 Earnings building — on track for ₹600/day
- ⚡ **Suddenly — heavy rain starts (94mm rainfall in 3 hours, IMD Red Alert issued)**

**Within minutes:**
- 🌧️ Roads get flooded across Chennai zones
- ❌ Active orders get cancelled by customers
- 🚫 New orders stop arriving entirely
- 👉 Ravi is forced to log out

**The Damage:**
- Lost 3–4 hours of peak earning time
- Lost ₹300–₹500 income — 50–60% of a full day's earnings
- No compensation from platform or government
- Rent, groceries, and EMI obligations remain unchanged

> *"Ravi didn't stop working — the environment stopped him."*

**With Income Shield AI:**
> IMD Red Alert triggers automatically. Income deviation computed against Ravi's 30-day baseline. Fraud engine validates in under 45 seconds. ₹420 credited to his UPI. WhatsApp received: *"₹420 payout credited — stay safe, Ravi."*

---

## 🔁 Application Workflow

Income Shield AI operates across **6 automated phases** — end-to-end, with zero manual intervention.

```
┌─────────────────────────────────────────────────────────────────────┐
│                    6-PHASE PLATFORM WORKFLOW                        │
│                                                                     │
│  PHASE 1 — ONBOARDING                                              │
│  Register → Worker Profile → Coverage Need                          │
│  (KYC via Aadhaar OTP + DigiLocker · AI risk scoring · NLP guide)  │
│                          ↓                                          │
│  PHASE 2 — POLICY SETUP                                            │
│  Set Triggers → Weekly Pricing → Coverage Plan                      │
│  (AI defines thresholds · Dynamic premium · Back-test simulation)   │
│                          ↓                                          │
│  PHASE 3 — ACTIVATION                                              │
│  Policy Created → Payment → Policy Active                           │
│  (Smart contract / signed digital ledger · Tracking enabled)        │
│                          ↓                                          │
│  PHASE 4 — MONITORING (24/7)                                       │
│  Data Tracking → Trigger Check → Notify Worker                      │
│  (Weather APIs + AQI + IMD feeds · ML anomaly detection)            │
│                          ↓                                          │
│         ┌─── Trigger Met? ──┐                                      │
│         YES                 NO → continue monitoring                │
│         ↓                                                           │
│  PHASE 5 — CLAIMS (Zero-Touch)                                     │
│  Auto Claim → Verify Data → Fraud Check → Payout Calc               │
│  (No manual request · Multi-source oracle validation · Isolation    │
│   Forest · Real-time income deviation computation)                  │
│                          ↓                                          │
│  PHASE 6 — PAYOUT                                                  │
│  Instant Pay → Summary → Renew Plan                                 │
│  (UPI/bank transfer · Full audit trail · Next week auto-renewal)    │
└─────────────────────────────────────────────────────────────────────┘
```

### Phase-by-Phase Detail

**Phase 1 — Onboarding:** Handles KYC via Aadhaar OTP + DigiLocker, AI-driven risk scoring, and NLP-guided coverage selection so workers understand exactly what they're buying.

**Phase 2 — Policy Config:** AI defines precise trigger thresholds (e.g. rainfall ≥ 94mm in 3hrs, AQI ≥ 300), dynamically prices the premium using historical data, and runs back-test simulations showing what payouts would have looked like in past events.

**Phase 3 — Issuance:** Encodes policy terms into a smart contract or signed digital ledger, eliminating ambiguity at claim time.

**Phase 4 — Monitoring:** Data oracles (weather APIs, AQI feeds, civic disruption data) stream into an ML anomaly detection engine that watches for threshold breaches 24/7.

**Phase 5 — Claims:** Fully automated. Trigger fires → system self-files the claim → cross-validates oracle data from multiple sources → fraud check → computes income deviation payout. No action needed from the worker.

**Phase 6 — Payout:** Funds delivered within minutes. Full audit trail surfaces exactly why a payout was (or wasn't) triggered, maintaining complete trust.

---

## ⚡ Parametric Triggers

All triggers are hyperlocal — validated at the worker's specific delivery zone, not city-wide alerts.

| # | Trigger | Data Source | Threshold | Notes |
|---|---------|-------------|-----------|-------|
| 🌧️ 1 | **Heavy Rain / Floods** | IMD + OpenWeatherMap | Rainfall ≥ 94mm in 3hrs / Red Alert issued | Core Chennai/Mumbai monsoon risk |
| 🌡️ 2 | **Extreme Heat** | IMD + Open-Meteo | Temperature ≥ 43°C or official advisory | Summer months, outdoor suspension |
| 🌫️ 3 | **High Pollution (AQI)** | CPCB AQI Feeds + OpenAQ | AQI ≥ 300 (Hazardous) | Delhi, Bengaluru Diwali season |
| 🚧 4 | **Curfew / Lockdown** | Civic Disruption APIs | Section 144 or mobility index < 20% | Political events, protests |
| 🌊 5 | **Road Blockage / Floods** | Traffic API + IMD | Zone roads impassable > 2hrs | Flood-zone specific routing |

### Income Deviation Formula

```
Actual Payout = (30-Day Baseline Daily Income) × (Hours Lost / Normal Active Hours) × Severity Factor

Where:
  30-Day Baseline = Rolling average of worker's actual daily earnings (last 30 days)
  Hours Lost      = Active working hours disrupted (platform-verified)
  Severity Factor = 0.5–1.0 based on disruption intensity

Example — Ravi, Chennai Flood:
  Baseline daily income : ₹700
  Hours lost            : 4 hrs out of 8hr shift (50%)
  Severity factor       : 0.90 (Red Alert = extreme)
  Payout = ₹700 × 0.50 × 0.90 = ₹315 → rounded to ₹320 credited via UPI
```

---

## 🧠 AI/ML Architecture

### Dual-Layer AI System

```
┌─────────────────────────────────────────────────────────┐
│              DUAL-LAYER AI INTELLIGENCE                  │
│                                                         │
│  LAYER 1: PREDICTIVE RISK MODELING                      │
│  ├── XGBoost / Random Forest on zone risk features      │
│  ├── Inputs: weather forecast, historical disruptions,  │
│  │           seasonal patterns, location data           │
│  └── Output: weekly premium + disruption probability    │
│                                                         │
│  LAYER 2: BEHAVIORAL FRAUD DETECTION                    │
│  ├── Isolation Forest on 30-day rolling baseline        │
│  ├── Checks: GPS anomalies, income pattern deviation,   │
│  │           device fingerprint, claim velocity         │
│  └── Output: fraud score + SHAP explanation             │
└─────────────────────────────────────────────────────────┘
```

### 1. Predictive Risk Model

The system predicts disruption probability and dynamically prices each worker's weekly premium using:

- Zone-specific flood/heat/AQI historical data (IMD + CPCB, 2019–2024)
- Seasonal disruption patterns (monsoon multipliers, Diwali AQI spikes)
- Worker platform tenure and active hours consistency
- Location risk index (flood-prone zones, high-pollution corridors)

### 2. Behavioral Fraud Detection (Isolation Forest)

Detects anomalies using a **30-day rolling behavioral baseline** per worker:

| Fraud Vector | Detection Method |
|---|---|
| GPS spoofing | Device authentication + IP check + cell tower triangulation |
| Impossible location shifts | Geospatial velocity check (>50km/hr = flag) |
| Fake disruption claims | Multi-source oracle cross-validation (3 independent APIs) |
| Abnormal claim frequency | Velocity rule: max 2 claims per 7-day window before review |
| Income inflation | Cross-check declared income vs. platform-reported 30-day baseline |
| Inconsistent activity patterns | Isolation Forest anomaly score on behavioral time-series |

### 3. Real-Time Income Deviation Engine

Unlike traditional parametric insurance (which pays a fixed amount per event), Income Shield AI computes **exact income deviation** against each worker's personal baseline:

- Workers with higher baselines get proportionally higher payouts
- Workers who were not actively logged in at disruption time receive reduced payouts
- Partial disruptions (2 hours out of 8) get partial payouts — not binary full/nothing

---

## 💰 Weekly Premium Model

### Pricing Philosophy

> "Earn weekly. Pay weekly. Stay protected weekly."

Our pricing model is designed specifically for gig workers whose income is **short-term, variable, and location-dependent**. Instead of monthly or yearly plans, we use a dynamic weekly premium that adapts to real-time risk, remains affordable, and aligns with weekly earning cycles.

### AI-Based Pricing Formula

```
Weekly Premium = Base Rate + (Location Risk Index × 0.35) + (Disruption Probability × Coverage Amount × 0.08)

Components:
  Base Rate             = Standard minimum coverage cost (₹20 baseline)
  Location Risk Index   = Area-specific risk score (0.0–1.0)
                          Flood-prone zones · High AQI corridors · Traffic congestion
  Disruption Probability = AI-predicted probability for next 7 days
                          Using weather forecasts + historical data + seasonal patterns

Example — Ravi, Chennai, Monsoon Season:
  Base Rate        = ₹20
  Location Index   = 0.72 (flood-prone zone)
  Disruption Prob  = 0.45
  Coverage Amount  = ₹3,000

  Weekly Premium   = ₹20 + (0.72 × 0.35 × 100) + (0.45 × ₹3,000 × 0.08)
                   = ₹20 + ₹25.20 + ₹108
                   = ₹153.20 / week  (~5% of weekly income)
```

### Premium Tiers (Indicative)

| Zone Risk | Location Type | Weekly Premium | Weekly Coverage | % of Income |
|---|---|---|---|---|
| 🟢 Low | Stable zone, low disruption history | ₹29/week | ₹1,800/week | ~1.1% |
| 🟡 Moderate | Seasonal exposure, some disruption risk | ₹49/week | ₹3,000/week | ~1.4% |
| 🔴 High | Flood-prone / AQI zone / bandh-frequent | ₹79/week | ₹5,000/week | ~1.8% |

> Premiums are **recalculated every Monday** using fresh AI inference — zone risk, seasonal forecast, worker tenure, and 30-day earning history.

---

## 🛡️ Adversarial Defense & Anti-Spoofing

Income Shield AI uses a **multi-layer validation architecture** to protect against GPS spoofing, fake data injection, and manipulation attempts.

### Defense Layers

```
LAYER 1 — DEVICE AUTHENTICATION
  Device fingerprint · App attestation · Jailbreak/root detection

LAYER 2 — LOCATION VERIFICATION
  GPS coordinates + Cell tower triangulation + IP geolocation
  Velocity check: location shift > 50km/hr = impossible movement flag

LAYER 3 — DATA ORACLE CROSS-VALIDATION
  3 independent API sources must agree on disruption event
  IMD + OpenWeatherMap + CPCB must all confirm before trigger fires

LAYER 4 — BEHAVIORAL ANOMALY DETECTION
  Isolation Forest on 30-day rolling baseline
  Flags: unusual claim velocity, income deviation outliers

LAYER 5 — AUDIT TRAIL
  All trigger decisions logged immutably
  Workers see exactly why a payout was or was not issued
  Insurer dashboard shows full SHAP explainability
```

### Anti-Spoofing Strategy

- Suspicious claims are **blocked or delayed** until multi-source validation completes
- Workers can see exactly why their claim was held — full transparency
- Behavioral monitoring continues across rolling windows — patterns identified over time, not just per-event
- All actions stored in immutable secure audit logs for regulatory compliance

---

## 🌐 Platform Choice — Web PWA

### Why Web Application, Not Mobile-First?

| Factor | Decision | Reason |
|--------|---------|--------|
| **Accessibility** | React PWA | Works on all devices via browser — no app install required |
| **Low-end devices** | PWA | Runs on ₹6,000 Android phones with 2GB RAM |
| **Offline access** | Service Worker | Policy status and alert history accessible offline |
| **Deployment speed** | Web | Instant updates — no app store approval delays |
| **Development cost** | Single codebase | React PWA covers Android + iOS + Desktop (~60% cost saving) |
| **AI integration** | Backend-driven | Real-time risk prediction + live parametric trigger execution |
| **Real-time processing** | WebSockets + REST | 24/7 environmental monitoring + instant claim triggering |
| **Security** | Centralized | Aadhaar OTP + DigiLocker KYC, immutable audit logging |
| **Hackathon fit** | React + FastAPI | Faster to build, easier to demonstrate end-to-end in 6 weeks |

---

## 🏗️ Tech Stack

### Frontend — React PWA

```
React 18 + TypeScript
Tailwind CSS              — Mobile-responsive, low-end device support
Leaflet.js                — Zone mapping, GPS visualization
Recharts                  — Worker + insurer analytics dashboards
React Query               — API state management
PWA (Service Worker)      — Offline policy/payout status
WebSockets                — Real-time disruption alerts
```

### Backend — Python + Node.js

```
FastAPI (Python)          — Core REST API, trigger engine, ML inference
Node.js + Express         — Payment webhook handler
PostgreSQL                — Workers, policies, claims, payouts, audit log
Redis                     — Trigger event queue, real-time zone status cache
Celery + Beat             — Scheduled trigger polling every 15 minutes
WebSocket Server          — Live bidirectional alerts to workers
```

### AI / ML Stack

```
scikit-learn              — Isolation Forest (fraud detection)
XGBoost / Random Forest   — Premium pricing + disruption prediction
Prophet                   — Weekly disruption forecasting
SHAP                      — Fraud flag explainability
Pandas + NumPy            — 30-day baseline computation + feature engineering
MLflow                    — Experiment tracking + model registry
```

### External API Integrations

```
OpenWeatherMap API        — Real-time weather + 7-day forecast
IMD Open Data             — Historical rainfall + Red Alert notifications
CPCB AQI Feeds            — Real-time air quality index by zone
OpenAQ API (free)         — AQI coordinates backup
Google Mobility API       — Curfew / social disruption detection (mock)
Razorpay Sandbox          — UPI payout simulation
Twilio (free tier)        — WhatsApp + SMS notifications
DigiLocker API            — Worker KYC verification (Aadhaar OTP)
```

### Infrastructure

```
Docker + Docker Compose   — Local dev environment
Render / Railway          — Free-tier cloud deployment for demo
GitHub Actions            — CI/CD (lint → test → deploy)
```

---

## 📁 Repository Structure

```
income-shield-ai/
├── frontend/
│   └── src/
│       ├── pages/
│       │   ├── Onboarding.tsx         — Worker registration + KYC
│       │   ├── Dashboard.tsx          — Worker: coverage, payouts, risk
│       │   ├── Policy.tsx             — Weekly policy management
│       │   ├── Claims.tsx             — Auto-generated claim history
│       │   └── AdminPanel.tsx         — Insurer: analytics + fraud queue
│       ├── components/
│       │   ├── ZoneMap.tsx            — Leaflet zone polygon display
│       │   ├── PayoutCard.tsx         — Payout summary widget
│       │   ├── RiskBadge.tsx          — Zone risk indicator
│       │   └── TriggerMonitor.tsx     — Live trigger status
│       └── hooks/                     — API hooks, auth, geolocation
├── backend/
│   ├── api/                           — FastAPI route handlers
│   ├── ml/
│   │   ├── premium_model.py           — XGBoost weekly premium calculator
│   │   ├── fraud_detection.py         — Isolation Forest + rule engine
│   │   ├── income_deviation.py        — Real-time deviation computation
│   │   └── risk_forecast.py           — Prophet disruption forecasting
│   ├── triggers/
│   │   ├── rain_trigger.py            — IMD + OpenWeatherMap rain/flood
│   │   ├── heat_trigger.py            — Extreme temperature
│   │   ├── aqi_trigger.py             — CPCB + OpenAQ pollution
│   │   ├── curfew_trigger.py          — Mobility / civic disruption
│   │   └── road_trigger.py            — Traffic blockage detection
│   ├── payments/                      — Razorpay UPI sandbox
│   └── notifications/                 — Twilio WhatsApp + SMS
├── data/
│   ├── synthetic_workers.csv          — Training data: worker profiles
│   ├── zone_risk_scores.json          — Pre-computed zone risk table
│   └── historical_disruptions.csv     — Synthetic disruption event log
├── docs/
│   ├── architecture.png
│   └── api_spec.yaml
├── assets/                            — README images (SVGs)
├── docker-compose.yml
└── README.md
```

---

## 🗓️ Development Plan

### ✅ Phase 1 (Mar 4–20): Ideation & Foundation — *Current*
- [x] Persona definition: Ravi — Swiggy/Zomato food delivery, Chennai
- [x] 5 real-world disruption scenarios mapped
- [x] Weekly premium formula + AI pricing logic designed
- [x] 5 parametric triggers + data sources identified
- [x] Income deviation computation model designed
- [x] 6-phase application workflow documented
- [x] Dual-layer AI architecture planned
- [x] Tech stack finalized
- [x] GitHub repository with this README
- [ ] Onboarding flow wireframe (Figma)
- [ ] FastAPI project scaffold + Docker setup
- [ ] Synthetic training dataset generated
- [ ] Premium model v0 trained on synthetic data

### Phase 2 (Mar 21 – Apr 4): Automation & Protection
- [ ] Worker onboarding + policy creation (React)
- [ ] 5 automated triggers live (3 real APIs + 2 mocks)
- [ ] Dynamic premium engine integrated end-to-end
- [ ] Real-time income deviation computation
- [ ] Zero-touch auto-claim pipeline (trigger → validate → payout)
- [ ] Fraud detection v1: Isolation Forest + GPS validation
- [ ] Phase 2 demo video (2 min)

### Phase 3 (Apr 5–17): Scale & Optimise
- [ ] Advanced fraud detection: full behavioral baseline + multi-layer defense
- [ ] Full Razorpay sandbox UPI payout flow
- [ ] Insurer admin panel (loss ratio, fraud queue, zone heatmap)
- [ ] Worker dashboard v2 (earnings protected, 30-day baseline, risk forecast)
- [ ] Tamil + Hindi notification templates
- [ ] Trigger-to-payout latency < 60s end-to-end
- [ ] 5-min final demo video
- [ ] Final pitch deck (PDF)

---

## 🔴 What Income Shield AI Strictly Excludes

The problem statement has a hard constraint — we never touch these:

| ❌ Excluded | Reason |
|------------|--------|
| Vehicle repairs or maintenance | Personal mechanical failure — not an external parametric trigger |
| Health or medical expenses | Out of coverage scope |
| Life or accident insurance | Separate regulated product category |
| Platform commission changes | Business policy decision, not an environmental disruption |
| Worker's voluntary absence | Personal choice — not an uncontrollable external event |

The system only pays when an **external, measurable, zone-level event** causes income loss that the worker had absolutely no control over.

---

## 🌟 Why Income Shield AI Wins

| Feature | Why It Matters |
|---------|----------------|
| **Income Deviation Model** | Unlike fixed-amount parametric insurance, we compute exact personal income loss against each worker's 30-day baseline — Ravi gets paid for what *he* actually lost |
| **Hyperlocal Triggers** | Zone-level polygon validation — not city-wide alerts. Ravi's Adyar zone must actually be affected |
| **30-Day Rolling Baseline** | Fraud engine learns each worker's normal behavior — unusual patterns over time, not just per-event anomalies |
| **Dual-Layer AI** | Predictive risk pricing + behavioral fraud detection running simultaneously |
| **Multi-Source Oracle** | 3 independent APIs must agree before a trigger fires — eliminates single-point-of-failure false payouts |
| **Immutable Audit Trail** | Every trigger decision logged with full SHAP explainability — workers see exactly why payout was or wasn't issued |
| **Monday Auto-Renewal** | Weekly premium aligns perfectly with Swiggy/Zomato payment cycles — zero friction |

---

<a href="https://drive.google.com/file/d/1lKL9g-9tSH2rg5VtpduBYJeSRQsBSaL3/view?usp=drive_link" target="_blank">▶️ Watch Demo Video</a>

---

## 👥 Team InnovateIT

| Name | Role |
|------|------|
| 🟢 NIVASAN A | Full Stack + Backend (FastAPI, PostgreSQL) |
| 🔵 MUTHU BHAVANI & KAVIN  | ML / AI Engineering (XGBoost, Isolation Forest, Income Deviation) |
| 🟣 VISAKAN | Frontend + UX (React PWA, Dashboards, Notifications) |

---

<div align="center">

*Built with purpose for India's 15 million gig workers who deserve a safety net*

brainy guys · Guidewire DEVTrails 2026 · University Hackathon**

`Weekly pricing` · `Hyperlocal triggers` · `Income deviation model` · `Dual-layer AI fraud detection`

`#Guidewire` `#DEVTrails2026` `#Hackathon` `#AI` `#Innovation` `#StudentDevelopers`

</div>
README (3).md
Displaying README (3).md.
visakans.it24@bitsathy.ac.in. Press tab to insert.
