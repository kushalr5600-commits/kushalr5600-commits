# Kushal

Engineering student and solo developer working at the intersection of **hardware security**, **CPU/GPU architecture research**, and **applied AI systems**. I build end-to-end — RTL in SystemVerilog, verification testbenches, Python frameworks, and full-stack demos — and I'm preparing for the Scaler University DevForge Hackathon.

## Skills

**Languages:** Python · C · C++ · Verilog / SystemVerilog · JavaScript · Shell
**Hardware:** FIPS 203 / FIPS 204 (ML-KEM / ML-DSA) RTL, NTT datapaths, OpenROAD + Sky130 sign-off flow, KLayout, iverilog, Yosys
**Software:** FastAPI, scikit-learn, XGBoost, NumPy, pytest, Docker, Linux

## Featured projects

### [blackbox](https://github.com/kushalr5600-commits/blackbox) — Enterprise decision preflight engine
IBM Z Datathon 2026 project. A calibrated Impact Gate decides which payment/ops decisions deserve expensive counterfactual simulation; selected decisions are stress-tested under three frozen scenarios, the distance to failure (fragility) is measured, and a Decision Certificate with evidence and fingerprints is issued before commitment. FastAPI backend, JS dashboard, NumPy/sklearn/XGBoost, IBM Granite LLM narrative (advisory only). Synthetic data only; research prototype.

### [computational_rnd_engine](https://github.com/kushalr5600-commits/computational_rnd_engine) — AI-driven hardware R&D engine + QuantumVault
Self-improving CPU/GPU architecture discovery framework (search/verify/evaluate loop with an honest deterministic surrogate evaluator — not a replacement for cycle-accurate sign-off). Includes **QuantumVault**: ML-KEM-768 (FIPS 203) key generation RTL in SystemVerilog — NTT datapath, base multiplier, SHAKE/Keccak, sampler — verified byte-for-byte against reference vectors in simulation, plus an OpenROAD/Sky130 physical-design flow. 6 commits; 9 reachable including a local tooling checkpoint.

### [nexus-os](https://github.com/kushalr5600-commits/nexus-os) — Universal agentic OS (experimental)
Experimental solo scaffold for a universal agent runtime — kernel, orchestration graph, memory backends, protocols (MCP/A2A/ACP), browser automation, governance and observability. Compiles under CPython 3.12; **not verified in a clean environment**; APIs may change. Published for review with an honest status disclosure.

## Engineering values

Honest verification over inflated claims · no fabricated benchmarks · synthetic data for demos · secrets never committed · docs that say what works and what doesn't.

## GitHub stats

Pinned: `blackbox` · `computational_rnd_engine` · `nexus-os`
