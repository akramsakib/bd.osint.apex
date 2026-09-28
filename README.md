# 🇧🇩 BD-OSINT Apex (v1.0 Pro)
### National Bangladesh Government Open Source Intelligence & Investigation Suite

[![PWA Ready](https://img.shields.io/badge/PWA-100%25%20Offline%20Ready-00ff9d.svg?style=flat-square)](#)
[![Verified Endpoints](https://img.shields.io/badge/Gov.bd%20Endpoints-81%2B%20Verified-00f0ff.svg?style=flat-square)](#)
[![Zero Telemetry](https://img.shields.io/badge/Privacy-100%25%20Client--Side-brightgreen.svg?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

**BD-OSINT Apex** is an intelligence framework, investigator's workbench, and direct portal matrix tailored for reconnaissance across the **People's Republic of Bangladesh**.

Directly indexing official regulatory bodies, ministries, directorates, judicial archives, statutory registers, and telecom numbering plans, this workbench combines curated `.gov.bd` government endpoints with **8 specialized client-side calculation engines** and a **zero-telemetry case dossier management system**.

---

## ⚡ Live Web Application & PWA

- 🌐 **Live Web Workbench:** [https://akramsakib.github.io/bd.osint.apex/](https://akramsakib.github.io/bd.osint.apex/)
- 📱 **Progressive Web App (PWA):** Works seamlessly on iOS, Android, macOS, Linux, and Windows with offline caching.

---

## 🏛️ 14 Bangladesh Government Intelligence Sectors

| Sector | Focus Areas & Official Systems | Verified Portals |
| :--- | :--- | :---: |
| 🪪 **National ID & Vital Statistics** | Bangladesh Election Commission NID Wing, BDRIS Birth & Death Registries, e-Passport & MRP Tracking | 7 |
| 🏢 **Corporate & Business Registries** | RJSC Company Entity Search, BIDA One Stop Service, DSE Stock Filings, DIFE Factory Database | 6 |
| 💰 **Tax, Customs & Revenue (FININT)** | NBR e-TIN Validation, e-Return Taxpayer Portals, ASYCUDA World Customs, VAT e-Services | 6 |
| 🗺️ **Land Records & Cadastral (e-Porcha)** | Ministry of Land e-Porcha Khatian System, e-Mutation (Namjari), Land Development Tax (LD Tax), DLRS | 6 |
| 🚗 **Transport, Vehicles & Logistics** | BRTA Service Portal (BSP), Motor Vehicle Registration Verification, Railway e-Ticketing, BIWTA Ports | 6 |
| ⚖️ **Judiciary, Law & Public Gazette** | Supreme Court Cause Lists & Judgments, BD Gazette Archive (BG Press), BD Code Laws, Judicial Portal | 6 |
| 🏛️ **Banking, Finance & Capital Markets** | Bangladesh Bank FX Rates, Central Bank Circulars, CIB Reporting, SEC Enforcement, Sonali Bank | 6 |
| 📱 **Telecom, Cyber & Infrastructure** | BTRC Spectrum & Operator Numbering Plan, BGD e-GOV CIRT Bulletins, National Data Center, Dot BD Whois | 6 |
| 🎓 **Education, Degrees & Verifications** | Education Board Results Archive, UGC University Registry, BMDC Doctor Licensure, BTEB TVET | 6 |
| 💼 **Civil Service, Ministries & e-GP** | National e-GP Tender Portal, Bangladesh Public Service Commission, Cabinet Division, Public Admin (MoPA) | 6 |
| 🛡️ **Law Enforcement & Public Safety** | Bangladesh Police Citizen Service, CID Cyber Police, Anti-Corruption Commission (ACC), Fire Service | 6 |
| 🚢 **Immigration, Visas & Consular** | DIP Immigration & Passports, Bangladesh e-Visa System, BMET Manpower Registry, MOFA Attestation | 6 |
| 📊 **Demographics & Statistics** | Bangladesh Bureau of Statistics (BBS), National Geo-Code Directory, Planning Commission, SDGs Tracker | 4 |
| 🌾 **Agriculture, Commerce & Resources** | Dept of Agricultural Marketing (DAM) Daily Commodity Rates, Export Promotion Bureau (EPB), TCB | 4 |

---

## 🛠️ 9 Interactive Bangladesh Intelligence Engines

BD-OSINT Apex features 8 standalone client-side parsers built specifically for Bangladeshi identifiers:

1. **🪪 Smart NID & District Geocode Decoder:**
   - Supports 10-digit Smart NID, 13-digit legacy NID, and 17-digit (YYYY + 13-digit) registration formats.
   - Decodes registration district geocode against all 64 districts of Bangladesh.
   - Generates instant search dorks for `.gov.bd` databases.

2. **👶 BDRIS 17-Digit Birth Registration Parser:**
   - Dissects the official 17-digit Birth Certificate format (`YYYY-DD-UU-WW-XXXXXXX`).
   - Extracts birth year, administrative district, upazila/thana code, and union/ward parishad identifier.

3. **💰 NBR 12-Digit e-TIN Validator & Tax Circle Resolver:**
   - Validates National Board of Revenue 12-digit e-TIN structures.
   - Provides direct links to the official NBR e-TIN verification portal and e-Return systems.

4. **🚗 BRTA Motor Vehicle Registration Plate Decoder:**
   - Parses metropolitan/district transport authorities (Dhaka Metro, Chatta Metro, Sylhet, etc.).
   - Decodes vehicle class series codes across 14 transport categories:
     - `GA` (গ) Private Passenger Cars (1500cc - 2500cc)
     - `KHA` (খ) Jeeps / SUVs / 4WDs
     - `BHA` (ভ) Microbuses & Vans
     - `CHA` (চ) Delivery Pickups & Ambulances
     - `HA` (হ) Motorcycles (100cc+)
     - `DA`/`DHA` (ড/ঢ) Medium & Heavy Commercial Trucks
     - `THA` (থ) CNG 3-Wheelers

5. **📱 Bangladesh Mobile Operator (MNO) & Numbering Plan Identifier:**
   - Parses Bangladeshi phone numbers into standard E.164 formats (`+8801XXXXXXXXX`).
   - Identifies active network operator prefixes: Grameenphone (`017`, `013`), Robi (`018`), Banglalink (`019`, `014`), Teletalk (`015`), and Airtel (`016`).
   - Generates direct lookup links for WhatsApp, Telegram, and Truecaller.

6. **🏢 RJSC Company & Commercial Entity Reconnaissance:**
   - Generates targeted lookups for the Registrar of Joint Stock Companies and Firms (RJSC).
   - Generates corporate filings and Dhaka Stock Exchange (DSE) listed company queries.

7. **🗺️ e-Porcha & Khatian Land Reconnaissance Query Studio:**
   - Builds cross-referencing queries across District, Upazila/Thana, Mouza/JL number, and Khatian/Dag numbers.
   - Connects to e-Porcha, e-Mutation (Namjari), and Land Development Tax (LD Tax) verification gateways.

8. **🔎 Bangladesh Government Dorking Studio (`site:.gov.bd`):**
   - 1-click execution of high-impact Google Dorks targeting official gazette notifications, government e-GP tenders, Supreme Court judicial rulings, ministry gradation lists, and ACC notices.

---

## 🔒 Privacy & Operational Security (OPSEC)

- **100% Client-Side:** All parsing, decoding, searching, and case dossier logging execute entirely within the local browser environment.
- **Zero Telemetry:** No user data, queried identifiers, search history, or notes are transmitted to external servers.
- **Offline Storage:** Case files and pinned portals are stored locally in the browser's `localStorage` and can be exported as structured JSON dossiers.

---

## 📱 Mobile PWA Installation Guide

### iOS (Safari)
1. Open [https://akramsakib.github.io/bd.osint.apex/](https://akramsakib.github.io/bd.osint.apex/) in Safari.
2. Tap the **Share** button.
3. Scroll down and tap **"Add to Home Screen"**.

### Android (Chrome / Brave / Edge)
1. Open [https://akramsakib.github.io/bd.osint.apex/](https://akramsakib.github.io/bd.osint.apex/) in your browser.
2. Tap the **Menu (⋮)** button.
3. Tap **"Install App"** or **"Add to Home Screen"**.

---

## 💻 Local Offline Development

```bash
# Clone the repository
git clone https://github.com/akramsakib/bd.osint.apex.git
cd bd.osint.apex

# Serve locally using Python
python3 -m http.server 8080
```
Open `http://localhost:8080` in your browser.

---

## ⚖️ Legal & Ethical Usage

This repository and application are provided for lawful open-source research, journalistic investigation, compliance verification, and educational purposes. Always adhere to applicable Bangladeshi laws and data protection standards when conducting investigations.

---
**BD-OSINT Apex** • Maintained by [akramsakib](https://github.com/akramsakib)
