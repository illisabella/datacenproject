# AETHERIS NEXUS-IV — Tier IV Enterprise Data Center Landing Page

A modern, high-tech, and enterprise-grade landing page designed for an Uptime Institute **Tier IV Certified Fault-Tolerant Enterprise Data Center**.

---

## 🧭 Required Sections Overview

1. **Header / Navigation**:
   * **Logo**: `AETHERIS // TIER-IV Enterprise Data Center`
   * **Navigation Links**: `Services`, `Infrastructure`, `Security`, `Pricing/Solutions`, `Compliance`
   * **Direct Action Buttons**:
     * `'Portal Login'` (with hardware token / FIDO2 modal)
     * `'Request a Quote'` (smooth scrolls to RFP form)
   * **3D Quick Badge**: Direct anchor to the 3D room showcase.

2. **Hero Section**:
   * **Bold Headline**: *"Next-Generation Infrastructure for Mission-Critical Data"*
   * **Subheadline**: Emphasizes **99.999% Uptime Guarantee** and **zero latency** direct interconnects, dual 2(N+1) power, and liquid immersion cooling up to 120kW per rack.
   * **Two CTA Buttons**:
     * `'Explore Services'` (scrolls to Services grid)
     * `'Schedule a Tour'` (anchors to 3D facility inspection)
   * **Real-time Interactive Status Badge**:
     * `'All Systems Operational'` with animated radar ping, real-time latency readout, and 2(N+1) grid synchronization.
   * **Simulated Server Rack HUD**: Live animated blade LEDs, cold aisle temperature (`19.4°C ±0.2`), and PUE (`1.118`).

3. **Live Metrics / Key Stats Banner**:
   * `99.999% Uptime Guarantee` (Fault-tolerant dual active feeds SLA)
   * `100% Green Energy / PUE < 1.2` (Certified renewable hydro & solar power)
   * `Tier IV Certified` (Uptime Institute Design & Facility)
   * `24/7/365 On-site NOC Support` (Expert security & PE engineers on-site)

4. **3D Data Center Room Showcase (รูปห้อง Datacenter แบบ 3D)**:
   * **Interactive WebGL 3D Room Viewer (Three.js)**:
     * Full 3D server hall with dual rack rows, cold aisle glass containment roof, overhead liquid cooling conduits, reflective raised floor grid, and server LEDs.
     * 360° mouse drag orbit controls and scroll zoom.
     * Quick camera presets: **Isometric**, **Cold Aisle**, **Top-Down**, and **Reset**.
     * **Interactive Rack Clicking**: Click on any server rack in 3D to see power density, liquid cooling type, and uplink status in a live HUD popup.
   * **3 Key Tier IV Room Visuals (3D High-Resolution Architecture)**:
     1. **Room 01 // High-Density AI Server Hall**: Direct-to-chip liquid cooling, cold-aisle containment, 120 kW/rack capacity.
     2. **Room 02 // 2(N+1) Power Substation & UPS Vault**: Dual isolated 34.5kV feeds, rotary flywheel UPS, 72-hour fuel reserve.
     3. **Room 03 // 24/7 Command Center NOC & Biometric Airlock**: Multi-screen telemetry wall, retina/mantrap vestibules, 6-zone defense.

5. **Services Section**:
   * High-Density AI Colocation (up to 120 kW/rack)
   * Private Cages & Dedicated Wholesale Suites
   * Direct Cloud On-Ramps (AWS, Azure, GCP, 500+ carriers)
   * Disaster Recovery & Remote Hands (15-min SLA)

6. **Infrastructure Section**:
   * Dual Substation Grids 2(N+1) with 0.0ms STS transfer
   * Direct Liquid & Hybrid Cooling with thermal ride-through storage
   * Quad Meet-Me-Rooms with 4 diverse fiber points-of-entry

7. **Security Section**:
   * 6-Zone Defense Matrix (from K12 perimeter barriers to biometric rack handles)
   * Iris scanning, weight-calibrated mantraps, and 24/7 armed presence

8. **Pricing / Solutions Section**:
   * Colocation Cabinets ($1,450/rack/mo)
   * AI Pods & Cages ($3,850/rack/mo)
   * Dedicated Hyperscale Vaults (Custom MW scale)

9. **Compliance Section**:
   * Tier IV Certified, SOC 2 Type II, ISO 27001, PCI-DSS v4.0, HIPAA, LEED Platinum.

10. **Request a Quote Form & Client Portal Modal**:
    * Full RFP form with 2-hour SLA response.
    * FIDO2 / YubiKey mock authentication for client NOC portal.

---

## 🚀 How to View

Open [`index.html`](file:///C:/Users/Gusjung/Documents/tier4-datacenter-landing/index.html) in your browser:
```
file:///C:/Users/Gusjung/Documents/tier4-datacenter-landing/index.html
```

Or run via Python HTTP server:
```powershell
cd C:\Users\Gusjung\Documents\tier4-datacenter-landing
python -m http.server 8080
```
Then visit `http://localhost:8080`.
