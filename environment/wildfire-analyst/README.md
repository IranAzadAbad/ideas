# Iran Wildfire Analyst — AI-Powered Early Warning System for Iran's Forests and Wildlands

**Author:** Ali Afsah-Noudeh — Software Engineer · [GitHub](https://github.com/aliafsahnoudeh) · [LinkedIn](https://www.linkedin.com/in/aliafsahnoudeh/)

## Abstract

Iran loses thousands of hectares of forest and rangeland to wildfires every year — in provinces like Fars, Kohgiluyeh, Khuzestan, and the Zagros highlands. Most fires are detected too late, when containment is already difficult and ecological damage is done.

**Iran Wildfire Analyst** is an open-source, AI-powered wildfire detection and alerting system that turns raw satellite data into actionable intelligence in near real-time. It ingests NASA FIRMS satellite fire detections, enriches them with weather, vegetation, and air-quality data, and uses an LLM-assisted scoring engine to prioritize genuine threats — then pushes alerts to responders.

A working MVP already exists in two repositories:

- [iran-wildfire-analyst](https://github.com/aliafsahnoudeh/iran-wildfire-analyst) — The core detection pipeline (satellite ingest → enrichment → scoring → alerting)
- [wildfire-mcp-server](https://github.com/aliafsahnoudeh/wildfire-mcp-server) — An MCP server interface for querying wildfire data through AI assistants

## Why It's Interesting

- **Iran's forests are irreplaceable.** The Zagros oak forests and Hyrcanian forests (a UNESCO World Heritage site) took thousands of years to grow. Every fire season they shrink further. Early detection is the single highest-leverage intervention.
- **The technology is accessible now.** NASA's satellite fire data is free. Weather and land-cover APIs are free. LLMs can run affordably. What has been missing is someone stitching these together for Iran specifically — this project does exactly that.
- **It scales from MVP to national platform.** The current version runs on free APIs and a single machine. With modest investment it can integrate physical IoT sensors, drone feeds, and real-time ground-truth — becoming a comprehensive nature-protection platform, not just for fire but for deforestation, drought, and biodiversity monitoring.
- **It can save lives and livelihoods.** Wildfires threaten rural communities, livestock, and the firefighters who battle them with limited resources. Faster alerts mean faster response, smaller fires, and fewer casualties.

## Approach

**Phase 1 — Strengthen the MVP (Now)**
- Improve satellite detection accuracy with additional data sources (Landsat, Sentinel-2)
- Expand alerting beyond Telegram — a simple web dashboard and mobile notifications
- Add historical fire analysis to identify high-risk zones before fire season

**Phase 2 — Ground-Truth Integration**
- Partner with forestry departments to deploy low-cost IoT sensors (temperature, humidity, smoke) in high-risk areas
- Combine satellite detections with sensor readings for higher confidence and faster response
- Build a public-facing map and reporting interface

**Phase 3 — National Nature Protection Platform**
- Extend beyond fire to deforestation tracking, drought monitoring, and air quality
- Provide seasonal risk forecasts using historical data and climate models
- API access for fire departments, provincial governments, and environmental NGOs

## Help Needed

- **Backend / Data Engineers** — to scale the pipeline and integrate new data sources
- **Mobile / Frontend Developers** — to build a responder app and public dashboard
- **Environmental / Forestry Experts** — domain knowledge on Iran's fire-prone regions, vegetation types, and response workflows
- **IoT / Hardware Engineers** — for sensor integration in Phase 2
- **Funding & Partnerships** — cloud infrastructure, sensor hardware, and connections to Iran's Department of Environment or provincial forestry offices

## Supporting Material

- **Live repositories:**
  - [iran-wildfire-analyst](https://github.com/aliafsahnoudeh/iran-wildfire-analyst) — full pipeline with DAG-based agent orchestration, multi-source data fusion, and LLM-assisted scoring
  - [wildfire-mcp-server](https://github.com/aliafsahnoudeh/wildfire-mcp-server) — MCP server for AI-assistant integration
- **Data sources used:** NASA FIRMS (VIIRS), ESA WorldCover, Open-Meteo, OpenWeatherMap
- **Architecture highlights:** async event-driven pipeline, fault-tolerant DAG executor, parallel enrichment, SQLite state management, LLM-powered analysis with rule-based fallback
