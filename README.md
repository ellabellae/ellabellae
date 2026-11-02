# Ella Etchandy

**About me**
- Biomedical engineer at Duke (class of 2027) and BME Design Fellow, which means two years of designing real medical devices with clinicians, currently working on building a wearable for Coast Guard boat crews to prevent Traumatic Brain Injury
- Constantly self-teaching; right now that's applied AI. Most of the repos below are side projects that started as a question I wanted to answer for myself.
- Co-founder of Duke Business Behind Health, a 300-member org I run like a startup. I built the software that automates it: the member portal, the chief of staff, and member database.
- I love learning about all things healthcare: who pays, who builds, who's actually in the room when a tool gets used

**Recent builds** (all live)
- **learningtool** — turns a research-paper PDF into an interactive, story-shaped lesson; every claim is checked against the paper's own sentences
- **DBBH-chief-of-staff** — runs the exec team of a 300-member student org: reads a live Google Sheet, calendar, and meeting notes; weekly briefings and 1:1 preps.
- **DBBHwebsite** — the DBBH site and member portal (Google Sheets → Apps Script → Supabase; events, RSVPs, points).
- **morningbriefing** — a daily HTML briefing of biotech, medtech, and pharma news.
- **ourademo** — an Oura ring data dashboard.

**Hardware and ML** (on [ellaetchandy.com](https://www.ellaetchandy.com/)): a rate-adaptive VVIR pacemaker (analog front end, Arduino, C++), U-Net mammogram segmentation, sleep EEG spectral analysis.

**Now (with teams*)*
- **Coast Guard exposure logger** (BME 473, medical device design) — a head-worn wearable for boat crews that logs whole-body vibration and impact exposure from an IMU, so a coxswain can decide when a crew has had enough. Currently prototyping.
- **AI adoption and Medicare billing** (BME 304, data science) — building a random forest on 292,000 CMS inpatient records predicting whether a hospital sits in an AI-adoption hotspot, then comparing coding intensity by DRG family between hotspots and coldspots. Built on the BCBSA finding that AI coding tools added $942M in costs for similar care.
- **Bluetooth Low Energy vitals monitor** (BME 554, embedded medical devices) — firmware for an nRF52833 that reads ECG-derived heart rate, temperature (MCP9808 over I2C), and battery voltage (ADC), and reports them over BLE (Heart Rate, Battery, and Device Information services plus a custom temperature and error-code service). Written in C on Zephyr RTOS with its State Machine Framework: all behavior is event-driven (timers, kernel events, work queues, threads), and memory is fully static
  
Co-founder, [Duke Business Behind Health](https://www.dukebusinessbehindhealth.org/) · [LinkedIn](https://www.linkedin.com/in/ella-etchandy-8b0150257/)
