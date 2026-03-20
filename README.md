# DEVtrails_Cracked

#  ShieldRun — AI-Powered Secure Parametric Income Insurance for Food Delivery Partners

> **Guidewire DEVTrails 2026** | Team: [CRACKED] | Persona: Food Delivery (Zomato / Swiggy)

---

##  The Problem

India's food delivery partners are the last mile of the digital economy — yet they are the most financially exposed. A single bad weather day in Mumbai, a civic strike in Bengaluru, or a heavy-rain evening in Chennai can wipe out an entire day's earnings with zero recourse. No safety net. No fallback. No claim to file.

**This isn't hypothetical. It's already happening — repeatedly, at scale:**

**The 2024 Delhi Heatwave** — Delhi recorded its highest-ever temperature in 2024, touching 52.9°C. Delivery workers had no choice but to keep riding through dangerous conditions because missing assignments meant losing earnings or facing penalties. Not a single rupee of income protection existed for hours lost to the heat.

 **All-India Gig Worker Strike, Dec 31 2025** — Workers across Zomato, Swiggy, Blinkit, Zepto, Amazon and Flipkart walked off on New Year's Eve — one of the highest-demand nights of the year — over falling wages, safety risks, and zero income protection. 50–60% of deliveries were delayed across major cities. The workers who didn't strike lost a full peak-earnings day with zero recourse.

 **The Scale of the Gap** — India's gig workforce has grown to an estimated 12 million workers as of FY 2024–25 and is projected to reach 23.5 million by 2030. Yet the Fairwork India Report 2024 found that none of the 11 major platforms reviewed could ensure a living wage for their workers — and on-ground social security protections remain largely absent despite new regulations requiring platforms to contribute to a social security fund.

**ShieldRun fills exactly this gap** — not with policy promises, but with an intelligent system that models earning potential and compensates only the verified loss of earning opportunity in real time. No form. No wait. No argument.

---

## Persona & Scenarios

**Primary Persona:** Arjun, a Zomato delivery partner in Mumbai

- Works 8–10 hrs/day, 6 days/week
- Earns ₹600–₹1,000/day depending on orders completed
- Has no employer. No ESI. No income protection.
- Is deeply aware of weather patterns but has no financial hedge against them
- Also representative of partners on **Amazon Flex** — Amazon's dedicated delivery partner app, live across 65+ cities in India, which gives partners flexible scheduling and block-based delivery assignments but zero income protection against external disruptions like weather or strikes.

### Real-World Disruption Scenarios We Cover

| # | Disruption Event | Trigger Condition | Income Impact |
|---|---|---|---|
| 1 | **Heavy Rainfall** | Rainfall > 15mm/hr in the partner's zone | Deliveries halted; earnings drop 70–90% |
| 2 | **Extreme Heat** | Temperature > 42°C for 3+ hours | Order volume drops; outdoor safety risk |
| 3 | **Severe Air Pollution** | AQI > 300 (Hazardous) | Outdoor delivery unsafe; platforms reduce surge |
| 4 | **Civic Strike / Bandh** | Verified local authority-issued restriction | Pickup/drop zones inaccessible |
| 5 | **Platform Outage** | Zomato/Swiggy app downtime > 2 hours (verified) | Zero orders possible; full earnings loss |

> **Coverage Scope:** LOSS OF INCOME ONLY. No vehicle repair, no health, no accident bills.

---

##  Application Workflow

ShieldRun does not assume income loss from disruptions — it estimates what a worker should have earned and compensates only the verified gap.

```
[Worker Onboards on ShieldRun App]
        ↓
[AI Risk Profile Built: Zone, Hours, Platform, History]
        ↓
[Weekly Policy Issued with Dynamic Premium]
        ↓
[Real-Time Trigger Monitoring: Weather + AQI + Traffic + Platform APIs]
        ↓
[Disruption Detected → System Automatically Initiates Evaluation]
        ↓
[Estimate Expected Earnings (E) vs Track Actual Earnings (A)]
        ↓
[Fraud Validation + Effort & Confidence Score Evaluated]
        ↓
[Instant Payout based on Verified Loss of Earning Opportunity — Zero Manual Claim Needed]
        ↓
[Dashboard Updated: Worker Sees Earnings Protected]
```

---

##  Weekly Premium Model

Our financial model is structured **100% on a weekly basis** to match the gig worker's earnings cycle.

### Tier Structure (Weekly Premium)

| Plan | Weekly Premium | Weekly Max Payout | Best For |
|---|---|---|---|
| **Basic Shield** | ₹29/week | ₹500/disruption day | Occasional delivery workers |
| **Pro Shield** | ₹59/week | ₹800/disruption day | Full-time delivery partners |
| **Max Shield** | ₹99/week | ₹1,200/disruption day | High-earning / multi-platform workers |

### Dynamic Pricing Logic (AI-Driven)

The weekly premium is **not static** — it adjusts every Monday based on:

- **Zone Risk Score:** Historical flood/rain/strike frequency in the partner's delivery zone (e.g., Dharavi gets a higher rain-risk multiplier than Bandra)
- **Seasonal Risk Calendar:** Pre-monsoon weeks (June–July) trigger a 10–15% premium increase
- **Partner History Score:** Workers with 0 fraudulent claims over 3 months get a 5% loyalty discount
- **Platform Activity Level:** Inactive partners (< 3 delivery days in past week) get a paused premium — no charge for dormant weeks

**Formula:**
```
Weekly Premium = Base Rate × Zone Multiplier × Season Factor × (1 - Loyalty Discount)
```

**Example:** Arjun, Pro Shield, Zone: Andheri East (high flood risk), July
```
₹59 × 1.15 (flood zone) × 1.12 (monsoon season) × 0.95 (loyal customer) = ₹72.5/week
```

---

## Parametric Triggers (Automated — Zero Touch)

A purely parametric system assumes every event equals a loss — ShieldRun uses a **Hybrid Parametric + Outcome-Based System**. Parametric triggers initiate the evaluation process based on **objective data conditions**, rather than immediately dispatching a fixed payout.

| Trigger | API Source | Threshold | Action |
|---|---|---|---|
| Heavy Rain | OpenWeatherMap / IMD API | > 15mm/hr in partner's pincode | Triggers Evaluation |
| Extreme Heat | OpenWeatherMap | Temp > 42°C for 3+ hrs | Triggers Evaluation |
| Hazardous AQI | CPCB AQI API (mock) | AQI > 300 | Triggers Evaluation |
| Civic Strike/Bandh | Government alert feed (mock) | Verified zone lockdown | Triggers Evaluation |
| Platform Outage | Zomato/Swiggy status mock API | Downtime > 2 hrs | Triggers Evaluation |

> **Note:** **“Triggers initiate evaluation, not payout — ensuring that only real income loss leads to compensation, not assumptions.”** We model earning potential, not just events. Payout is based on verified loss of earning opportunity.

**Claim Initiation:** Fully automatic. Partner receives a push notification: *"Heavy rain detected in your zone. Evaluating income impact for potential payout."*

**No form filling. No document upload. No waiting.**

---

##  AI/ML Integration Plan

### 1. Dynamic Premium Calculation
- **Model:** Gradient Boosted Regression (XGBoost)
- **Features:** Zone historical weather data, seasonal patterns, partner activity, past claim frequency
- **Output:** Personalized weekly premium per partner

### 2. Risk Profile Scoring
- **Model:** Clustering (K-Means) to segment partners into risk tiers on onboarding
- **Inputs:** Delivery zone, avg daily hours, platform (Zomato/Swiggy), historical city disruption data
- **Output:** Risk Score (Low / Medium / High) used to assign base plan

### 3. Hybrid Earning Prediction Engine

Disruptions do not uniformly reduce income — they reshape earning distributions. Our system adapts to variability across time, zone, and behavior. We evaluate the true loss of earning opportunity through a combination of a Personal Model and a Global Model:

**Payout = max(0, Expected Earnings − Actual Earnings) × Effort × Confidence**
*If Actual Earnings ≥ Expected Earnings → No payout is triggered.*

This effectively models a counterfactual scenario — what the worker would have earned if the disruption had not occurred.

- **Expected Earnings (E)**: Modeled actively before payout. **Expected Earnings represents the estimated income under normal working conditions, adjusted for real-time event impact to avoid overestimating loss.**
  `E = BaseRate × Hours × Demand × EventImpact × ZoneFactor`
  - **Personal Model**: Learns user behavior, earnings pattern, and working hours.
  - **Global Model**: Learns event impact, zone demand, and time-based variations. **This approach allows ShieldRun to handle real-world variability across time, location, platform demand, and worker behavior — making payouts adaptive rather than assumption-driven.**
  - **BaseRate**: user's earning per hour.
  - **Hours**: expected working duration.
  - **Demand**: probability of orders.
  - **EventImpact**: how disruption affects earnings (*Note: EventImpact is NOT always negative. Some events can increase earnings*).
  - **ZoneFactor**: area productivity.
- **Actual Earnings (A)**: Derived from verified activity (based on deliveries, timestamps, GPS).
- **Effort Score (S)**: Range [0,1]. Based on login duration, acceptance rate, and movement consistency to prevent low-effort exploitation.
- **Confidence Score (C)**: Range [0,1]. Based on trigger reliability, fraud detection, and location certainty.

### 4. Hyperlocal Gig Risk Scorer (HGRS) — Our Supporting Global Intelligence Model

This is ShieldRun's supporting global intelligence model — a novel risk scoring algorithm built on top of pretrained foundation models using **transfer learning**, purpose-designed for India's gig economy.

ShieldRun's model selection runs at **two distinct levels**. Most teams pick one model and ship it. We run a structured comparison at every layer and always deploy the proven best.

```
┌─────────────────────────────────────────────────────────────┐
│         LEVEL 1 — Pretrained Base Model Selection           │
│   Which foundation model do we transfer learn from?         │
│   3 candidates evaluated → 1 winner selected                │
└───────────────────────┬─────────────────────────────────────┘
                        ↓
              Winner becomes the base of HGRS
                        ↓
┌─────────────────────────────────────────────────────────────┐
│         LEVEL 2 — Final Production Model Selection          │
│   HGRS vs 4 classical ML models — which is best overall?    │
│   5 candidates evaluated → 1 deployed to production         │
└─────────────────────────────────────────────────────────────┘
```

---

#### Level 1 — Pretrained Base Model Comparison (3 Candidates)

Training a risk model from scratch requires years of labelled insurance claim data that doesn't exist yet for India's gig sector. Instead, we start with a **pretrained weather/climate foundation model** and extract its internal embeddings as rich input features — rather than raw weather numbers — giving our model a massive head start.

We compare three real, publicly available pretrained foundation models:

| Model | By | What It Is | Why Relevant | Key Strength |
|---|---|---|---|---|
| **Prithvi WxC** | NASA + IBM | 2.3B parameter model pretrained on 40 years of NASA MERRA-2 Earth observation data; open-source on Hugging Face | Global-to-local scale fine-tuning; directly applicable to hyperlocal Indian pincode forecasting | Best for geographic downscaling to pincode level |
| **MetNet-3** | Google DeepMind | Deep learning model for weather forecasting at 1km spatial / 2-min temporal resolution; outperforms physics-based NWP models up to 24hrs | Best-in-class precipitation forecasting — directly powers our rain trigger scoring | Best for short-term rain trigger precision |
| **Pangu-Weather** | Huawei Research | Transformer-based model pretrained on 39 years of ERA5 reanalysis data; 3D Earth system representation; published in Nature | Multi-variable forecasting (temperature + wind + humidity simultaneously) | Best for heatwave + AQI multi-trigger scoring |

**Level 1 Evaluation Parameters:**

| Parameter | What We Measure |
|---|---|
| **Precipitation RMSE** | Accuracy of rain threshold predictions at pincode level |
| **Temperature MAE** | Accuracy of heatwave trigger forecasts |
| **Downscaling Performance** | How well model adapts from global → India pincode scale |
| **Fine-tuning Speed** | Time to adapt pretrained model on our India-specific data |
| **Open Source / API Access** | Can we actually integrate it in 6 weeks? |

The **Level 1 winner** becomes the pretrained base that powers HGRS.

---

#### The HGRS Pipeline (Built on Level 1 Winner)

```
Level 1 Winner Embeddings (transfer learned)
              +
Historical Disruption Data (per pincode, 3 years IMD)
              +
Platform Activity Signals (orders/hr drop patterns)
              +
Partner Behavioral Profile (working hours, zone, platform)
              ↓
  ShieldRun HGRS — Fine-tuned on India Gig Data
              ↓
  Hyperlocal Risk Score (0–100) per zone per week
```

#### What Makes It Novel — Pincode-Level Granularity

Most insurance risk models score at a city level. HGRS scores at **pincode + time-of-day + platform + season** level:

| Zone                   | Time  | Month    | Platform    | Risk Score    |
|------------------------|-------|----------|-------------|---------------|
| Dharavi, Mumbai        | 6 PM  | July     | Zomato      | 87 — Extreme  |
| Bandra, Mumbai         | 10 AM | December | Swiggy      | 12 — Low      |
| Connaught Place, Delhi | 2 PM  | May      | Amazon Flex | 74 — High     | 
| Koramangala, Bengaluru | 8 PM  | March    | Swiggy      | 31 — Moderate |

#### Self-Improving Feedback Loop

```
Claim Verified & Paid → Confirmed Disruption Event
              ↓
       Added to Training Dataset
              ↓
    Model Retrained Every Monday
              ↓
  Next Week's Risk Scores More Accurate
```

---

### 5. Level 2 — Final Production Model Comparison (5 Candidates)

Once HGRS is built, it competes against 4 classical ML baselines on the **same India gig dataset**. We do not assume HGRS wins — we prove it.

| # | Model | Type | Why Included |
|---|---|---|---|
| 1 | **XGBoost** | Classical ML | Strong tabular baseline; handles missing values well |
| 2 | **Random Forest** | Classical ML | Robust to outliers; excellent zone-level feature importance |
| 3 | **LightGBM** | Classical ML | Fastest retraining — ideal for Monday midnight retraining window |
| 4 | **Neural Network (MLP)** | Deep Learning | Captures non-linear interactions between weather + behavioral signals |
| 5 | **HGRS** | Transfer Learning | Our custom model; pretrained embeddings + fine-tuned on India gig data |

#### Level 2 Evaluation Parameters

| Parameter | Why It Matters for Insurance |
|---|---|
| **RMSE** | Premium prediction accuracy — lower = fairer pricing for workers |
| **AUC-ROC** | Trigger classification quality (disruption vs no disruption) |
| **F1 Score** | Fraud detection balance between precision and recall |
| **Inference Latency (ms)** | Must be fast enough for real-time trigger evaluation |
| **Weekly Retraining Time** | Must complete within Sunday midnight burn window |
| **SHAP Explainability Score** | IRDAI requires auditable, justifiable AI-driven pricing decisions |

#### Selection Criteria & Proposed Best Model

The model with the best combined score across **RMSE + AUC-ROC + SHAP** is deployed to production each week. Our hypothesis — validated through the feedback loop — is that **HGRS will outperform all classical baselines** after 3–4 weeks of real claim data accumulation, because pretrained weather embeddings capture pattern complexity that tabular features alone cannot represent.

> **Why this matters for regulators:** IRDAI increasingly requires AI-driven pricing to be auditable. By running SHAP explainability alongside accuracy metrics at both levels, ShieldRun is built for regulatory compliance from day one — not retrofitted later.

### 6. Fraud Detection Engine — Dual-Key Location Verification System

This is ShieldRun's original fraud prevention mechanism, purpose-built for food delivery workflows.

#### The Core Idea

Every pickup location (restaurant / dark kitchen / cloud hub) has a **static Location Key** permanently registered in ShieldRun's system. Every day, the delivery partner receives a **time-bound Daily OTP** pushed directly to their **Zomato / Swiggy / Amazon delivery account** — the same app they already use to accept orders.

When a disruption claim is being evaluated, the system performs a **two-point key match** — one at pickup (IN) and one at drop-off (OUT):

```
┌─────────────────────────────────────────────────────────┐
│                  DUAL-KEY VERIFICATION                  │
│                                                         │
│   Partner's Daily OTP (sent to delivery account)        │
│              +                                          │
│   Pickup Location's Static Key                          │
│              ↓                                          │
│         KEYS MATCH?                                     │
│         ↙        ↘                                     |
│       YES          NO                                   │
│   IN timestamp   Claim rejected                         │
│   recorded  →    immediately                            │
│   GPS tracking                                          │
│   begins                                                │
│              ↓                                          │
│   Partner completes delivery                            │
│              ↓                                          │
│   OUT timestamp recorded at drop-off                    │
│              ↓                                          │
│   Full verified delivery window = IN → OUT              │
│   Cross-checked against disruption event timestamp      │
└─────────────────────────────────────────────────────────┘
```

#### How It Works Step by Step

| Step | Event | What ShieldRun Records |
|---|---|---|
| **1. Morning** | Daily OTP pushed to partner's Zomato/Swiggy/Amazon account | OTP hash + valid date window |
| **2. Pickup (IN)** | Partner enters OTP at pickup location; system matches against location's static key | IN timestamp + location key match hash + GPS coordinates |
| **3. Active Delivery** | GPS tracked continuously while partner is on route | Location trail hash stored (zone-level, not exact) |
| **4. Drop-off (OUT)** | Delivery marked complete in platform app | OUT timestamp recorded, delivery window closed |
| **5. Claim Check** | Disruption event timestamp cross-checked against IN→OUT window | If disruption falls within verified window → claim is legitimate |

#### Fraud Scenarios This Catches

| Fraud Attempt | How Dual-Key Stops It |
|---|---|
| Partner claims disruption but was never at the pickup zone | Location key won't match → no IN timestamp → claim void |
| Partner uses yesterday's OTP | OTP is time-bound to current day only → key mismatch → rejected |
| Partner submits claim for a delivery that never happened | No IN/OUT timestamps on record → auto-rejected |
| Two partners sharing the same OTP | OTP is single-use, tied to one account → second use flagged immediately |
| GPS spoofing (fake location) | Location key at pickup is static and hardware-bound — spoofed GPS won't produce a valid key match |

#### AI Layer on Top — Isolation Forest Anomaly Detection

Beyond the dual-key check, an **Isolation Forest ML model** runs a second pass on every claim:

- **Velocity check:** More than 3 claims in 4 weeks → manual review flag
- **Pattern check:** Claims suspiciously clustered on Monday mornings or just before policy renewal → flagged
- **Cross-partner check:** Multiple partners claiming the same disruption event from the same pickup location in an unusually short window → collusion flag
- **Effort Score Validation:** Ensures movement consistency and high acceptance rate. Drops in effort score immediately discount the payout multiplier to catch low-effort exploitation.
- **Confidence Score Integration:** Evaluates trigger reliability and location certainty, acting as a direct probability modifier.
- **Output:** Fraud Risk Score (0–100). Score > 70 → auto-reject + flag for insurer review

**This ensures that payouts are not only validated for authenticity, but also adjusted based on the worker’s actual effort during the disruption window.**

#### Key Security Properties

- Daily OTPs are generated using **HMAC-SHA256** — cryptographically signed, cannot be guessed or forged
- Location static keys are **stored encrypted (AES-256)** in the backend — never exposed client-side
- All IN/OUT timestamp events are **written to the blockchain ledger** — immutable, auditable, tamper-proof
- Raw GPS trail is **hashed to zone-level** and auto-deleted after 24 hours — privacy by design

### 7. Predictive Disruption Forecasting (Phase 3)
- **Model:** LSTM time-series model trained on 3 years of IMD weather data
- **Purpose:** Predict high-risk weeks in advance, enable proactive partner alerts

---

### ⚙️ From Event-Based to Outcome-Based Protection

```text
Traditional parametric systems:
Disruption → Fixed Payout

ShieldRun:
Disruption → Impact on Earnings → Verified Loss → Payout
```

**By shifting from event-based payouts to outcome-based evaluation, ShieldRun transforms parametric insurance into an adaptive, intelligence-driven income protection system.**

---

## Platform Choice: Mobile-First Web App (PWA)

**Rationale:**
- Food delivery partners primarily use smartphones (Android, budget tier)
- A Progressive Web App (PWA) avoids Play Store friction while providing native-app feel
- Works offline for areas with spotty connectivity
- Single codebase serves both worker (consumer) and insurer (admin) views

---

## 🛠️ Tech Stack

### Frontend
- **React.js** (Web/PWA) — Partner dashboard, policy view, payout history
- **Tailwind CSS** — Mobile-first responsive UI
- **React Native** (Phase 3) — Native app shell for push notifications

### Backend
- **Node.js + Express** — REST API layer
- **Python (FastAPI)** — AI/ML model serving (risk scoring, fraud detection)
- **PostgreSQL** — Partner profiles, policy records, claim history
- **Redis** — Real-time trigger state caching

### AI/ML
- **scikit-learn / XGBoost** — Premium calculation & fraud detection
- **TensorFlow/Keras** — LSTM forecasting model (Phase 3)
- **Pandas + NumPy** — Data preprocessing pipelines

### Integrations
- **OpenWeatherMap API** (free tier) — Rain, temperature triggers
- **CPCB AQI API** (mock/free) — Pollution trigger
- **Government alert feed** (mocked) — Strike/bandh trigger
- **Zomato/Swiggy API** (simulated) — Platform outage detection, earnings data
- **Razorpay Test Mode / UPI Simulator** — Instant payout processing

### Infrastructure
- **AWS EC2 / Render.com** — Backend hosting
- **Vercel** — Frontend hosting
- **GitHub Actions** — CI/CD pipeline

---

## 📅 Development Plan

### Phase 1 (Weeks 1–2): Ideation & Foundation ✅
- [x] Finalize persona and disruption triggers
- [x] Define weekly premium model and parametric trigger logic
- [x] Set up GitHub repository and project structure
- [ ] Build basic React frontend shell (onboarding flow)
- [ ] Set up Node.js backend with partner registration API
- [ ] Connect OpenWeatherMap API (mock trigger test)
- [ ] Train initial risk scoring model on synthetic data

### Phase 2 (Weeks 3–4): Automation & Protection
- [ ] Complete registration + onboarding UX
- [ ] Policy creation with dynamic weekly premium calculation
- [ ] Build 5 automated parametric triggers
- [ ] Claims management UI (auto-trigger + partner notification)
- [ ] Fraud detection v1 (GPS + activity + duplicate checks)
- [ ] Simulated payout flow (Razorpay test mode)

### Phase 3 (Weeks 5–6): Scale & Optimise
- [ ] Advanced fraud detection (Isolation Forest model)
- [ ] Dual dashboard: Worker view + Admin/Insurer view
- [ ] LSTM forecasting model for disruption prediction
- [ ] Full payout simulation with UPI mock
- [ ] Final pitch deck + 5-minute demo video
- [ ] Performance optimization and edge case handling

---

## Key Metrics (Analytics Dashboard — Planned)

**For Workers:**
- Expected vs Actual earnings breakdown
- Effort score display and trust visibility
- Total earnings protected this week
- Active coverage status + renewal date
- Payout history timeline
- Disruption alerts for their zone

**For Insurers (Admin):**
- Live loss ratio by zone and disruption type
- Claims pending vs. auto-approved vs. flagged
- Weekly premium collected vs. payouts issued
- Predicted disruption risk for next 7 days (ML-powered)
- Fraud flag queue with risk scores

---

## We Do NOT Cover

As per hackathon constraints, ShieldRun strictly excludes:
-  Health or medical insurance
-  Life insurance
-  Accident coverage
-  Vehicle repair or maintenance payouts
-  Any manual/subjective claim — all triggers are parametric and data-driven

---

## Security Architecture

Security is not an afterthought in ShieldRun — it is foundational. We are handling sensitive financial data, GPS location, payout credentials, and insurance policy records for millions of gig workers. Every layer of the stack is designed with security-first principles.

---

## Adversarial Defense & Anti-Spoofing Strategy

With the rise of coordinated fraud attacks using GPS spoofing, ShieldRun implements a multi-layer adversarial defense system that goes beyond basic location verification.

1. The Differentiation — Real vs Spoofed Worker

ShieldRun does not trust GPS alone. Instead, it validates behavior + system interaction + delivery proof:

Dual-Key Verification System (Primary Defense)

Real worker → Must pass OTP + Pickup Location Key match

Spoofer → Cannot generate valid location key → instantly rejected

Movement Consistency Check

Real worker → Natural movement pattern (speed, stops, route variation)

Spoofer → Static / unrealistic jumps → flagged by ML model

Effort Score Validation

Real worker → High login time + order acceptance

Spoofer → Low effort but high claims → penalized or rejected

Delivery Window Proof (IN → OUT timestamps)

Real claim → Verified delivery timeline exists

Fake claim → No real delivery → auto-reject

# Key Idea:
We validate “Did the person actually work?”, not just “Where is the person?”

2. The Data — Beyond GPS Coordinates

To detect coordinated fraud rings, ShieldRun analyzes multi-dimensional data signals:

📍 Behavioral Data

Login duration

Order acceptance rate

Delivery completion timestamps

Idle vs active time ratio

📍 Movement Data

Speed patterns (constant vs natural variation)

Route continuity (no teleporting)

Zone transitions

📍 Platform Data

Verified orders from Zomato/Swiggy APIs

Pickup and drop timestamps

Platform outage correlation

📍 Environmental Data

Weather API (rain, heat)

AQI levels

Government alerts

📍 Cross-User Fraud Signals (CRITICAL)

Multiple users claiming from same zone at same time

Identical movement patterns across accounts

Sudden spike in claims from a Telegram-coordinated cluster

## ML Model Used:

Isolation Forest detects anomalies in:

Claim frequency

Behavioral deviation

Group fraud patterns

3. The UX Balance — Protecting Honest Workers

We do NOT blindly reject flagged claims — this is where most systems fail.

✅ Smart Handling of Flagged Cases:

Soft Flag (Low Risk)

Claim processed with reduced confidence score

Partial payout allowed

Medium Risk

Delayed payout (few hours)

Additional verification using activity + platform data

High Risk

Claim temporarily blocked

Sent for manual audit (admin dashboard)

🌧️ Handling Real-World Edge Cases

Example:
Worker in heavy rain → poor network → GPS drops

Our system:

Uses last known valid movement

Checks platform order activity

Uses zone-level validation instead of exact GPS

👉 Result:
✔ Honest workers still get paid
❌ Fraudsters get filtered out

4. System-Level Protection Against Coordinated Attacks

To stop Telegram-based fraud syndicates:

Cluster Detection

Detects abnormal spikes from same zone

Rate Limiting on Claims

Prevents mass payout draining

Dynamic Risk Thresholds

System becomes stricter during suspicious spikes

Weekly Model Retraining

Learns new fraud patterns continuously

##Final Defense Philosophy

Basic Systems:
GPS = Truth ❌
ShieldRun:
Behavior + Proof + Pattern = Truth ✅

We shift from location-based trust → behavior-based verification, making large-scale spoofing attacks economically and technically unviable.

---

### 1. Password & Credential Hashing

All user credentials are **never stored in plaintext** — ever.

- **Algorithm:** `bcrypt` with a minimum cost factor of **12**
- **What it protects:** Partner login passwords, admin credentials, API secret keys
- **Implementation:**
```javascript
const bcrypt = require('bcrypt');
const SALT_ROUNDS = 12;

// On registration
const hashedPassword = await bcrypt.hash(plainPassword, SALT_ROUNDS);

// On login
const isValid = await bcrypt.compare(inputPassword, hashedPassword);
```
- **Why bcrypt over MD5/SHA:** bcrypt is deliberately slow and salted — brute-force attacks are computationally infeasible even if the database is compromised

---

### 2. Blockchain — Immutable Claim & Policy Ledger

Every policy issuance, parametric trigger event, and payout is recorded on a **private blockchain ledger**. This prevents tampering, ensures auditability, and makes fraud significantly harder.

**What goes on-chain:**

| Event | Data Recorded On-Chain |
|---|---|
| Policy Created | Partner ID hash, plan tier, week start/end, premium paid |
| Trigger Fired | Trigger type, timestamp, API source data hash, zone ID |
| Claim Approved | Claim ID, fraud score, payout amount, approval timestamp |
| Payout Processed | Transaction ID, UPI ref hash, amount, partner ID hash |

**Stack:**
- **Hyperledger Fabric** (permissioned blockchain) — enterprise-grade, no gas fees, suitable for insurance workflows
- Each block contains: `{ previousHash, timestamp, eventData, dataHash (SHA-256), digitalSignature }`
- All sensitive fields (partner name, phone, UPI ID) are **hashed before being written to chain** — the ledger stores proofs, not PII

```javascript
const crypto = require('crypto');

function createBlock(eventData, previousHash) {
  const dataHash = crypto
    .createHash('sha256')
    .update(JSON.stringify(eventData))
    .digest('hex');

  return {
    timestamp: Date.now(),
    dataHash,
    previousHash,
    data: eventData  // PII fields already hashed before reaching here
  };
}
```

**Why this matters for insurance:** Regulators and auditors can verify every payout decision independently. No insurer can retroactively deny a valid claim — it's on-chain.

---

### 3. Data Encryption — At Rest & In Transit

**In Transit (HTTPS / TLS 1.3):**
- All API communication enforces **TLS 1.3** — older protocols (TLS 1.0, 1.1, SSL) are explicitly rejected
- HTTP requests are auto-redirected to HTTPS
- HSTS (HTTP Strict Transport Security) headers enforced

**At Rest (AES-256):**
- Sensitive database columns (UPI IDs, Aadhaar last-4, phone numbers) are encrypted using **AES-256-CBC** before storage
- Encryption keys are stored in **AWS KMS (Key Management Service)** — never hardcoded, never in `.env` files
- Backups are encrypted with a separate KMS key

```python
from cryptography.fernet import Fernet
import os

# Key loaded from AWS KMS, never from code
encryption_key = os.environ['KMS_ENCRYPTION_KEY']
cipher = Fernet(encryption_key)

# Encrypt before storing
encrypted_upi = cipher.encrypt(upi_id.encode()).decode()

# Decrypt only when needed for payout
decrypted_upi = cipher.decrypt(encrypted_upi.encode()).decode()
```

---

### 4. Application Security

**Authentication & Authorization:**
- **JWT (JSON Web Tokens)** with short expiry (15 min access token + 7-day refresh token)
- Role-based access control (RBAC): `PARTNER`, `ADMIN`, `AUDITOR` roles with strict permission scopes
- Refresh tokens stored as **httpOnly cookies** (not localStorage — prevents XSS theft)

**API Security:**
- **Rate limiting:** Max 100 requests/min per IP (express-rate-limit); stricter 10 req/min on auth endpoints
- **Input validation & sanitization:** All inputs validated with `Joi` (Node.js) / `Pydantic` (Python) before processing
- **SQL injection prevention:** All DB queries use parameterized statements via ORM (Prisma / SQLAlchemy)
- **CORS policy:** Whitelisted origins only — no wildcard `*` in production

**Infrastructure Security:**
- Secrets managed via **AWS Secrets Manager** — no `.env` files in production
- **WAF (Web Application Firewall):** AWS WAF rules block SQLi, XSS, and known malicious IPs
- **VPC isolation:** ML engine and database live in private subnets — not publicly accessible
- Regular **dependency vulnerability scans** via `npm audit` + `pip-audit` in CI/CD pipeline

---

### 5. GPS & Location Data Privacy

Partner GPS data is used only for fraud validation — not stored long-term.

- GPS coordinates are **hashed to a zone-level grid** (500m × 500m cell) before any storage — exact location is never persisted
- Raw GPS data is held in Redis with a **24-hour TTL** (auto-deleted after claim window closes)
- Partners are shown a clear consent screen on onboarding explaining exactly what location data is used for and when

---

### 6. Security Summary Table

| Layer                | Technology                    | Protection                                 |
|----------------------|-------------------------------|--------------------------------------------|
| Passwords            | bcrypt (cost=12)              | Brute-force resistant credential storage   |
| Sensitive DB fields  | AES-256-CBC + AWS KMS         | Encrypted at rest, key rotation supported  |
| API transport        | TLS 1.3 + HSTS                | Encrypted in transit, no downgrade attacks |
| Auth tokens          | JWT + httpOnly cookies        | XSS-resistant session management           |
| Claim/policy records | Hyperledger Fabric blockchain | Tamper-proof, auditable event ledger       |
| API abuse            | Rate limiting + WAF           | DDoS and injection attack prevention       |
| GPS data             | Zone-hashing + 24hr TTL       | Location privacy by design                 |
| Secrets              | AWS Secrets Manager / KMS     | No hardcoded credentials anywhere          |

---

## Repository Structure (Planned)

```
shieldrun/
├── frontend/          # React PWA — partner & admin dashboards
├── backend/           # Node.js REST API + PostgreSQL models
├── ml-engine/         # Python FastAPI — risk scoring & fraud detection
├── triggers/          # Real-time parametric trigger monitoring service
├── blockchain/        # Hyperledger Fabric chaincode & ledger config
├── security/          # Auth middleware, encryption utils, rate limiters
├── mock-apis/         # Simulated Zomato, Swiggy, Govt alert feeds
├── docs/              # Architecture diagrams, pitch deck
└── README.md
```

---

## Team

| Name |
---
- BALLA TENISHAAKHILA
- Kalidasan B
- Suggu Jhansi Lakshmi
- Saavan Rajeev
- B Nachiketh Gupta
---
## 🎬 Phase 1 Demo Video

> 📹 [Link to 2-minute strategy video — to be added before March 20 EOD]

The video covers our persona research, the ShieldRun concept, the weekly premium model, our parametric trigger design, and a walkthrough of our Phase 1 prototype scope.

---
