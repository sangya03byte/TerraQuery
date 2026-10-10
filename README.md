# TERRAQUERY
### "AI-Powered Natural-Language Climate Intelligence"
**Powered by Oracle AI Database 26ai & Select AI**

---

## 🌍 Overview

**TerraQuery** allows non-technical users (climate researchers, disaster management teams, NGOs, policy makers, and students) to ask complex questions about structured Earth and climate observation datasets in plain English — without writing SQL.

Built on **Oracle AI Database 26ai** and its native **Select AI (`DBMS_CLOUD_AI`)** capability, TerraQuery bridges relational schemas with Large Language Models while preserving mathematical ground truth: **the LLM translates language to SQL, but all calculations and metrics come directly from the Oracle database.**

---

## ⚡ The Core Pipeline

```
User asks question in plain English
                ↓
Frontend Web Dashboard (React + Deep Oceanic UI)
                ↓
Backend / API Layer (Validation + Security Sandboxing)
                ↓
Oracle AI Database 26ai (Schema: CLIMATE_INTEL_2026)
                ↓
Select AI Layer (DBMS_CLOUD_AI)
                ↓
AI Profile (Schema Grounding + OCI GenAI / Cohere Command R+)
                ↓
Natural Language → Verified Oracle SQL
                ↓
Oracle SQL Engine Executes on 125,000+ Climate Observations
                ↓
Actual Database Output Rows
                ↓
Analytics & Anomaly Detection (Statistical Baseline Departures)
                ↓
Automatic Visualization (Dynamic Charts + Chhattisgarh GIS Cartogram)
                ↓
Grounded AI Explanation (Zero Hallucinations)
                ↓
User
```

---

## 🎯 Target Users & Value Proposition

- **Researchers & Scientists:** Detect multi-year thermal warming trends (+0.32°C/year in Durg) without manual regression scripts.
- **Disaster Management Teams:** Instantly identify precipitation anomalies (e.g. Korba +31.4% excess rainfall) to pre-position emergency relief.
- **Government Environment Departments:** Formulate district Heat Action Plans using localized 42.8°C heatwave records.
- **Policy Analysts & NGOs:** Evaluate agricultural monsoon stability and drought compensation.

---

## 🚀 Supported Demo Queries

1. **"Which district in Chhattisgarh had the highest temperature in 2024?"**
   - Result: Durg (42.8°C), recorded in May 2024
   - Visual: Peak Ranking Bar Chart + Map Highlight
2. **"Compare rainfall between Durg and Raipur from 2020 to 2024."**
   - Result: Dual Bar Comparison Chart (+165 mm/year surplus for Raipur)
3. **"Show the temperature trend of Durg over the last 5 years."**
   - Result: Time-series curve with +0.32°C/year warming slope
4. **"Which district received the highest rainfall in 2024?"**
   - Result: Korba (1,624.5 mm) followed by Jagdalpur (1,582.0 mm)
5. **"Which districts experienced unusually high rainfall?"**
   - Result: Anomaly Diverging Chart (Korba +31.4%, Jagdalpur +24.8% above 4-year baseline)
6. **"What was the average humidity in Chhattisgarh during monsoon?"**
   - Result: 78.4% statewide average; peaks at 84.2% in Jagdalpur
7. **"Show me the top 5 districts by precipitation."**
   - Result: Ranked horizontal bar chart (Korba, Jagdalpur, Bastar, Raigarh, Surguja)
8. **"Will it rain tomorrow?"**
   - Guardrail Response: Safely explains dataset scope without hallucinating weather predictions.

---

## 🔒 Security & Zero-Hallucination Guarantee

1. **Deterministic Grounding:** All values displayed originate from indexed tables in Oracle AI Database 26ai. The LLM does not generate numbers.
2. **Read-Only Enforcement:** Queries execute strictly under `ROLE_CLIMATE_ANALYTICS_RO`. DDL, INSERT, and DROP privileges are blocked.
3. **Transparent Lineage:** The "Explain Query" inspector provides a step-by-step audit of Question → NLP Tokens → Generated SQL → Raw DB Result → Final Insight.
4. **Sealed Credentials:** Database passwords and OCI API keys remain in server-side vaults and are never exposed to browser clients.

---

## 🛠️ Local Development & Running

```bash
# 1. Start backend API server (runs on http://localhost:5000)
npm run server
# or: node server.js

# 2. Start frontend dev server (runs on http://localhost:3000)
npm run dev

# 3. Production Build
npm run build
```

---

*Built for Oracle AI Database 26ai Hackathon.*
