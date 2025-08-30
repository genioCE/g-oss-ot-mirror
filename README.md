# g-oss-ot-mirror — Read-only OT data mirror (OPC UA → MQTT/Kafka → TSDB/Lake)

**What:** Safe, **read‑only** tap of PLC/RTU tags via OPC UA/Modbus → MQTT/Kafka → **VictoriaMetrics** (hot) + Iceberg (cold).

**Why:** Analytics without touching control systems. **No write paths.**
