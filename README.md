# ☁️ AWS Cloud-Native Threat Intelligence Honeypot Pipeline

An automated, serverless security ingestion pipeline designed to capture live network traffic metadata, isolate brute-force threat signatures, and push aggregated geo-data into an interactive visualization engine.

---

## 🗺️ Live System Dashboard Architecture
This infrastructure actively captures global connection attempts and visualizes automated threat profiles hitting exposed mock targets.

*   **Active Intrusion Captured:** Unauthorized SSH Brute Force attempts.
*   **Targeted Protocols Analyzed:** Port 22 (SSH/TCP Management Frameworks).

---

## 🛠️ The Technical Pipeline Engine
The architecture maps raw infrastructure events directly into security intelligence datasets through a four-stage serverless topology:

1. **Ingestion Layer:** Deployed an public-facing cloud compute layer as a decoy target. Activated **AWS VPC Flow Logs** to monitor raw network traffic and connection frames.
2. **Automation Layer:** Hooked **Amazon EventBridge** rules into the logging thresholds to intercept real-time traffic alerts.
3. **Processing & Storage Engine:** EventBridge triggers an **AWS Lambda** function which streams, decrypts, and extracts malicious structural IP fields, sorting the logs into an **Amazon S3** security data bucket.
4. **Visual Mapping layer:** Downstream analytics ingest the structural metadata directly into an interactive dark-mode geolocation map to pinpoint threat origins instantly.

---

## 🧰 Tech Stack Specs
* **Cloud Infrastructure Provider:** Amazon Web Services (AWS)
* **Core Monitoring Modules:** VPC Flow Logs, Amazon EventBridge
* **Compute & Processing:** AWS Lambda (Python Backend Parsing Architecture)
* **Data Lake Management:** Amazon S3, Amazon DynamoDB
* **Target Security Scopes:** Cloud IAM Policies, Threat Isolation, Security Group Management

---

#### 📂 Repository File Blueprint
* `index.html` — The interactive frontend dashboard that parses live metadata coordinates onto a dark-mode global mapping grid.
* `lambda_function.py` — Core production-ready Python log parsing engine that isolates inbound brute-force telemetry.
* `README.md` — Complete architectural specifications and system execution overview.
---

## 🎯 Strategic Professional Impact
Building this project provided intensive hands-on experience managing infrastructure scale, evaluating real-time server security configurations, parsing structured network telemetry frames, and applying zero-trust identity policies to live public infrastructure.
