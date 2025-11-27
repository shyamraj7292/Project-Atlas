# Project Atlas – Adaptive Telemetry Fabric

Goal: Build a small enterprise-style telemetry pipeline that collects host + network logs, transports them through an ingestion layer, and stores them for analysis.

Initial Architecture (v0):
- Windows VM -> Host Logs
- Linux Server -> Host Logs
- Zeek -> Network Logs
- Fluent Bit / Logstash -> Collect + Transport
- Elasticsearch -> Storage + Query

Next Step: Choose lab environment (Cloud vs Local) and prepare 1 VM.

