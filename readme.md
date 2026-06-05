# 🛰️ NorthStar Health

**Starlink-Compatible Telehealth Readiness for Rural and Northern Healthcare**

NorthStar Health is a lightweight telehealth infrastructure platform that helps clinics determine whether their satellite-supported internet connection is capable of supporting virtual care before an appointment begins.

By translating network performance into clinically meaningful recommendations, NorthStar helps rural healthcare teams reduce failed appointments, improve virtual care reliability, and maintain access to specialist services in remote regions.

---

## Why NorthStar?

Telehealth is increasingly relied upon to deliver healthcare in rural and northern communities. However, connectivity remains a critical barrier.

A virtual consultation can fail due to:

- High latency
- Packet loss
- Unstable satellite connections
- Insufficient bandwidth
- Network congestion

For many remote communities, these appointments may represent the only practical access to specialist care.

NorthStar Health provides a simple readiness assessment before the visit begins.

---

## Features

### 🛰️ Satellite Connectivity Monitoring

NorthStar evaluates:

- Latency
- Jitter
- Packet loss
- Download throughput
- Upload throughput
- Network stability

Designed for environments using Starlink and other satellite internet providers.

---

### 📊 Telehealth Readiness Index

NorthStar converts technical network metrics into a simple readiness score ranging from **0–100**.

| Score | Recommendation |
|---------|----------------|
| 85–100 | Proceed with full video consultation |
| 70–84 | Proceed with standard video consultation |
| 55–69 | Use low-bandwidth video and prepare backup |
| 35–54 | Switch to phone-based care |
| 0–34 | Activate alternative care pathway |

---

### 🏥 Clinical Scenario Assessment

Readiness is evaluated against different healthcare use cases:

- Primary Care Video Visits
- Mental Health Consultations
- Specialist Reviews
- Emergency Virtual Assessments
- Low-Bandwidth Follow-Ups

Each scenario uses different connectivity thresholds.

---

### 📈 Network Intelligence

NorthStar provides visibility into:

- Network routing
- ISP information
- Geographic network location
- Cloud edge routing
- Connectivity trends

---

### 📄 Readiness Reporting

Generate downloadable reports for:

- Telehealth operations
- Connectivity audits
- Rural healthcare infrastructure assessments
- Quality improvement initiatives

---

## Example Workflow

1. Clinic launches NorthStar Health
2. Staff select the planned clinical scenario
3. Connectivity diagnostics are performed
4. Telehealth Readiness Index is generated
5. Clinical recommendation is provided
6. Staff proceed, modify, or reroute care accordingly

---

## Installation

```bash
git clone https://github.com/patrickromanescu/northstar.git

cd northstar

pip install -r requirements.txt

streamlit run app.py
```

---

## Download

Latest release:

```text
https://github.com/patrickromanescu/northstar/releases/latest
```

Direct release asset:

```text
https://github.com/patrickromanescu/northstar/releases/download/v1.0.0/northstar-health-v1.0.0.zip
```

## Technology Stack

- Python
- Streamlit
- Plotly
- Pandas
- Cloudflare Network Diagnostics
- IP Geolocation APIs
- Starlink-Compatible Connectivity Monitoring

---

## Roadmap

- [ ] Starlink Enterprise Telemetry Integration
- [ ] Predictive Outage Forecasting
- [ ] Multi-Clinic Monitoring
- [ ] Mobile Health Unit Fleet Dashboard
- [ ] Telehealth Reliability Benchmarking
- [ ] Offline Emergency Fallback Workflows

---

## Mission

**No patient should lose access to care because the signal fails.**

NorthStar Health exists to strengthen the digital infrastructure that enables virtual care, helping rural and northern communities remain connected to healthcare services when distance is the barrier.

---

### Disclaimer

NorthStar Health does not collect patient information. Connectivity diagnostics are intended to support operational telehealth readiness and do not replace clinical judgment