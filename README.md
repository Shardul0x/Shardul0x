
<div align="center">

```
  ██████╗██╗  ██╗ █████╗ ██████╗ ██████╗ ██╗   ██╗██╗      ██████╗ ██╗  ██╗
  ██╔════╝██║  ██║██╔══██╗██╔══██╗██╔══██╗██║   ██║██║     ██╔═████╗╚██╗██╔╝
  ╚█████╗ ███████║███████║██████╔╝██║  ██║██║   ██║██║     ██║██╔██║ ╚███╔╝ 
   ╚═══██╗██╔══██║██╔══██║██╔══██╗██║  ██║██║   ██║██║     ████╔╝██║ ██╔██╗ 
  ██████╔╝██║  ██║██║  ██║██║  ██║██████╔╝╚██████╔╝███████╗╚██████╔╝██╔╝ ██╗
  ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝  ╚═════╝ ╚══════╝ ╚═════╝ ╚═╝  ╚═╝
```

**security engineer · builds systems that assume they'll be attacked**

</div>

<br>

I break things for a living during the day (red team work, CRTA-certified) and build the things
that stop those breaks the rest of the time. Currently inside the SOC at **Endurance
Technologies**, running multi-server log monitoring and anomaly detection on infrastructure
that can't afford false positives. Two published papers, a handful of hackathon podiums, and a
habit of finishing what I start — every project below runs, it doesn't just compile.

Pune, India. Open to remote and contract work.

`github.com/Shardul0x` · `linkedin.com/in/shardul-bangale` · `shardulbangale@gmail.com`

<br>

## what I've shipped

**[zero-trust-factory-control-plane](https://github.com/ArYa-KuWaR/Zero-Trust-Factory)**
An industrial control system that trusts nothing by default. ESP32 devices authenticate over
mTLS/X.509 before they're allowed to speak; an Isolation Forest model watches behavior and
kills anomalies in under 2 seconds — no human in the loop.
`ESP32` `Jetson Nano` `Prometheus` `Grafana`

**[hiremind](https://oclabs-ui.vercel.app/)** — *live, in production*
An AI interview platform that has to catch cheating in real time, not after the fact. Groq-backed
interview logic, FAISS for retrieval, OpenCV proctoring holding 50+ concurrent sessions without
falling over.
`React` `FastAPI` `Groq` `FAISS` `OpenCV`

**[pqc-homomorphic-secure-chat](https://github.com/ArYa-KuWaR/PQC-Homomorphic-Encryption-Industry-Project)**
Messaging built for a world where today's encryption gets broken by tomorrow's quantum
computers. ML-KEM-1024 key exchange, TenSEAL homomorphic encryption — the server computes
on your data without ever being able to read it.
`Python` `TenSEAL` `Post-Quantum Crypto`

**[spectre-obfuscator](https://github.com/ArYa-KuWaR/Spectre-Obfuscator)**
A compiler pass that fights reverse engineers on their own turf — control-flow flattening and
string encryption baked into LLVM, enough to break 95% of standard static analysis.
`C++` `LLVM`

<br>

## how I think about the stack

```
security    → zero trust, mTLS/X.509, LLVM obfuscation, PQC, ICS/OT, MQTT
ai / ml     → TensorFlow, scikit-learn, LangChain, FAISS, OpenCV, Isolation Forest
build       → Python, C/C++, TypeScript, React, FastAPI, MongoDB, Supabase
observe     → Prometheus, Grafana
```

<br>

## published / placed

- **IEEE Xplore 2026** — Predictive Startup Analytics via Ensemble Learning
- **IEEE IGNITE-2026** — Hybrid PQC Framework for Secure Messaging
- **Springer SCI-2026** — Galaxy Evolution via VAEs and PINNs
- IIT Jammu Hackathon (2nd/800+) · IIT Guwahati Convolve (30/4200) · BITS Pilani APOGEE (Top 5) · DTU EHAX CTF (Top 11)

**Certifications:** CRTA (Certified Red Team Analyst) · Google Cybersecurity Professional · Cisco CCNA

<br>

<div align="center">

<sub>if you're building something that needs to survive contact with an attacker, let's talk</sub>

</div>

