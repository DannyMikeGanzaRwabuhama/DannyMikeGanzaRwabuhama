# Danny Mike Ganza Rwabuhama

Graduating software engineering student at **Rwanda Coding Academy (RCA)** focused on building reliable data pipelines and human-centered software systems.

**Looking for:** Data Engineering apprenticeships and Junior Software Engineering roles. Based in Kigali, open to remote.

---

## Selected Work

### Settlement Radar _(internship build · private)_

**Clearing transaction ingestion and failure diagnostics.** Built during a bank software internship to parse 100,000+ daily RWF clearing records from Excel/CSV, mask payer and account identifiers inside the database transaction via HMAC-SHA256, and surface failure patterns by channel and counterparty.

- **Architecture:** Thin Spring Boot streaming uploader (`Apache POI StreamingReader`) handing normalized rows to PostgreSQL (`PL/pgSQL`) for validation, masking, and reporting, paired with a React/TypeScript dashboard.
- **What I focused on:** Designing an atomic ELT ingestion boundary so malformed files reject cleanly without partial-day corruption, and keeping raw PII off disk.

`Java` · `Spring Boot` · `PostgreSQL` · `TypeScript` · `React` · `Docker`

### PandemicNet _(RCA Hackathon · 1st Place · team project)_

**Contact tracing and outbreak modeling prototype.**

- [**pandemicNet**](https://github.com/DannyMikeGanzaRwabuhama/pandemicNet): Hackathon-winning prototype built with Flask, PostgreSQL, and Streamlit to trace exposure paths and estimate contact risk.
- [**pandemicnet-ai**](https://github.com/DannyMikeGanzaRwabuhama/pandemicnet-ai): Architectural exploration modeling multi-degree exposure graphs in Neo4j alongside a Next.js dashboard and agent-based outbreak simulation.

`Python` · `PostgreSQL` · `Next.js` · `TypeScript` · `Docker`

### FaceLocking & FaceLockingServo _(RCA course projects)_

**Computer vision and embedded systems coursework.** Explored CPU-based face detection and recognition (`OpenCV`, `MediaPipe`, `ArcFace` embeddings) in **FaceLocking**, and extended it in **FaceLockingServo** to publish pan/tilt tracking commands over `MQTT` to an `ESP8266` servo controller.

Repos: [FaceLocking](https://github.com/DannyMikeGanzaRwabuhama/FaceLocking) · [FaceLockingServo](https://github.com/DannyMikeGanzaRwabuhama/FaceLockingServo)

`Python` · `OpenCV` · `MQTT` · `C++ (Arduino/ESP8266)`

### Echoes of Memory _(prototype · team project)_

**Offline-first memorial companion concept.** Designed for low-connectivity memorial sites in Rwanda, allowing visitors to scan local markers to access curated survivor testimonies while keeping sensitive content veiled until explicitly revealed. Validated with site stakeholders and built as a multi-client prototype (Flutter mobile client, Next.js CMS, and local sync architecture).

`Flutter (Dart)` · `Next.js` · `PostgreSQL`

---

## Core Working Stack

- **Primary (read, debug & build daily):** `Java (Spring Boot)` · `TypeScript / Next.js` · `PostgreSQL / SQL`
- **Coursework & Prototyping:** `Python` · `C++ (Embedded)` · `Dart (Flutter)` · `Docker` · `Git`
