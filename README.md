# 🛡️ SwarmIntercept AI: Multi-Agent Mesh Firewall

An enterprise-grade decentralized zero-trust proxy firewall designed to mitigate indirect prompt injections, adversarial steganography, and multi-hop collusion within agentic AI networks using Google Gemini.

<img src="https://shields.io" alt="Python Version"> <img src="https://shields.io" alt="Framework"> <img src="https://shields.io" alt="LLM Engine"> <img src="https://shields.io" alt="Security Level">

**SwarmIntercept AI** is a decentralized, real-time zero-trust security proxy designed to defend Multi-Agent Systems (MAS) against advanced **Indirect Prompt Injections**, **Adversarial Cryptographic Steganography**, and **Lateral Multi-Hop Collusion** attacks.

As AI architectures shift toward agent-to-agent autonomous delegation, traditional prompt defenses fail. SwarmIntercept establishes a dual-layer state validation gateway directly into the token ingestion pipeline, successfully isolating compromised execution threads before they breach backend enterprise data arrays.

---

## 🖥️ Live Application Dashboard
<img src="swarm-intercept-dashboard.png" width="100%" alt="SwarmIntercept AI Security Console Dashboard">

---

## 💡 Core Benefits & Value Proposition

* **🛡️ Absolute Zero-Trust Semantic Security:** Traditional firewalls inspect IPs and network traffic pack matrices. SwarmIntercept inspects the **Semantic Intent** of token flows between agents, capturing hidden adversarial behaviors that conventional filters miss entirely.
* **⚡ Zero Performance Latency:** To optimize computing cost and app response speed, the system bypasses heavy LLM calls for initial triage. **Layer 1 (Intent Polygraph)** dynamically screens metadata and transaction graph routing history on the fly.
* **🎯 100% Deterministic AI Defense:** Eliminates model hallucinations and payload bypass vectors during an active exploit attempt. **Layer 2 (Atomic Structural Shielding)** anchors absolute guard rails inside the ingestion stream, forcing the model to securely return a structured block string.
* **🔀 High Availability & Failover Resilience:** Zero runtime application crashes under distributed malicious overloading or API spikes. The architecture integrates an instantaneous failover matrix, auto-routing execution pipelines to stable alternative layers (`gemini-3.5-flash`) mid-session.
* **📊 Enterprise Visual Auditing Transparency:** Replaces the black-box opacity of autonomous agent networks with real-time operational visual panels (Red, Yellow, Green status modules) for transparent security verification.

---

## 🗺️ Architectural Pipeline Visualization

```text
  [ Untrusted Inbound Edge ] (Phishing Input / Hidden Stego Payload)
             │
             ▼
    ┌──────────────────┐
    │   Email_Agent    │ (Compromised Public Node)
    └────────┬─────────┘
             │  (Cascading Indirect Injection)
             ▼
    ┌──────────────────┐
    │   File_Manager   │ (Orchestrator Processes Content blindly)
    └────────┬─────────┘
             │  (Outbound Call Matrix Generated)
             ▼
 ⚡ 🔗 【 SWARMINTERCEPT SECURE PROXY GATEWAY 】 🔗 ⚡
   ├── [Layer 1: Intent Polygraph] ──► Flags Untrusted Source Anomaly
   └── [Layer 2: Structural Shield] ──► Anchors Target Ingestion Boundaries
             │
             ▼
    ┌──────────────────┐
    │  gemini-3.8-flash│ (Enforced Target Execution Core)
    └────────┬─────────┘
             │
             ▼
  [ Deterministic Output ] ──► "CRITICAL_POLICY_VIOLATION: ACCESS_DENIED..."
```

---

## 🔒 Advanced Vulnerability Mitigation Grid

| Attack Vector | Threat Profile Mechanics | SwarmIntercept Mitigation Protocol |
| :--- | :--- | :--- |
| **Indirect Prompt Injection** | Adversarial instructions hidden inside third-party untrusted data arrays (emails/spreadsheets) that execute implicitly when read by processing agents. | **Layer 1 (Intent Polygraph):** Aggressively parses multi-agent graph execution history (`chain_history`) to cross-verify structural origin states before token allocation. |
| **Encrypted Prompt Steganography** | Malicious triggers obfuscated via Base64 encoding, ROT13, zero-width characters, or homoglyph substitutions to bypass standard keyword filters. | **Layer 2 (Atomic Structural Shielding):** Appends rigid structural instruction matrices at the target execution layer, ensuring deterministic LLM alignment even during hidden semantic decoding. |
| **Multi-Hop Collusion** | Lateral exploit chains where a compromised edge agent attempts to trigger privileged actions (e.g., database dumps) on restricted internal backend microservices. | **Deterministic Gateway Interception:** Overrides downstream prompt boundary parameters to force an instantaneous execution halt upon threat vector isolation. |

---

## 🔒 Live Threat Interception & Mitigation
<img src="firewall-attack-mitigation.png" width="100%" alt="SwarmIntercept AI Attack Mitigation Interface">

---

## 🚀 Core Features

* **Real-Time Dual-Layer Inference Guard:** Combines fast execution graph metadata validation with strict downstream prompt boundary enforcement.
* **Automated High-Availability Failover:** Resilient production architecture that instantly reroutes execution streams to stable backup engines during high-demand spike sequences.
* **Fluid Streamlit Inspection Console:** Fully visual workspace featuring real-time node state telemetry for immediate transparent security auditing.

---

## 📦 Getting Started

### 1. Clone the Architecture Repository
```bash
git clone https://github.com
cd swarm-intercept-mesh-firewall
```

### 2. Establish System Dependencies & Python Runtime
Install the required architectural packages and verify your environment version matrix using the configuration files:
```bash
# Installs dependencies listed in requirements.txt (Streamlit & Google GenAI)
pip install -r requirements.txt
```
> *Note: This deployment environment utilizes the specifications defined in `runtime.txt` (Python 3.13.0).*

### 3. Configure Your Environment Verification Matrix
Acquire an API access token from **Google AI Studio** and expose it to your active environment shell:

* **PowerShell:**
  ```powershell
  $env:GEMINI_API_KEY="your_actual_api_key_here"
  ```
* **Command Prompt (CMD):**
  ```cmd
  set GEMINI_API_KEY=your_actual_api_key_here
  ```
* **Linux/macOS Bash:**
  ```bash
  export GEMINI_API_KEY="your_actual_api_key_here"
  ```

### 4. Deploy the Mesh Firewall Locally
```bash
streamlit run app.py
```

---

## 🎯 Live Proof-of-Concept Exploit Scenario

1. **The Payload:** An adversary routes an email containing hidden steganographic instructions requesting complete payroll records to the untrusted ingress point.
2. **The Graph Execution:** The `File_Manager` blindly forwards the request to the `Database_Manager` requesting execution while trying to bypass manual verification parameters.
3. **The Interception:** SwarmIntercept intercepts the runtime stream, detects the untrusted origin metadata, applies the structural proxy shield, and enforces token limits.
4. **The Mitigation:** The live Gemini inference runtime neutralizes the attack completely, generating the definitive secure fallback block string:
   `CRITICAL_POLICY_VIOLATION: ACCESS_DENIED_BY_SWARMINTERCEPT`

---

## 📜 License
Distributed under the MIT License. See `LICENSE` for more details.
