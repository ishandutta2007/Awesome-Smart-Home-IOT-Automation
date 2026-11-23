# Awesome-Smart-Home-IOT-Automation

# Top Smart Home & IoT Automation Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Local-First Smart Home Hubs, Automation Engines, Custom Firmware, MQTT/Matter Bridges & Self-Hosted Control*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted smart home & IoT platforms** and **open-source GitHub projects** for **Smart Home & IoT Automation**. These tools power automated lighting, climate/HVAC scheduling, security sensors, voice assistants, local rule engines, and custom microcontroller integrations across residential and industrial environments without cloud lock-in.

**Examples** include Home Assistant, openHAB, Node-RED, Domoticz, ioBroker, Gladys Assistant, ESPHome, Tasmota, Zigbee2MQTT, Matter.js, Frigate NVR, 0xprobabillity/house-control, Samsung SmartThings, Google Nest, Apple Home, Vivint, Crestron, Schneider Electric Wiser, Honeywell Home, Wyze, ThingsBoard Cloud, and Particle.

**Open-source emphasis**: This list heavily expands on active open-source home automation hubs, visual flow builders, ESP8266/ESP32 open firmware, local Zigbee/Z-Wave/Matter coordinators, and custom web/hardware control interfaces — ideal for makers, embedded developers, and privacy-first homeowners.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Samsung SmartThings](https://smartthings.com)**  
  Cloud-connected smart home automation platform supporting Matter, Thread, Zigbee, Z-Wave, and Wi-Fi devices with mobile routines and appliance integration.

- **[Google Home & Nest](https://google.com)**  
  Google's smart home ecosystem integrating Nest thermostats, cameras, speakers, Matter controllers, and cloud-based automation routines.

- **[Apple Home (HomeKit)](https://apple.com)**  
  Apple's smart home control and automation framework built into iOS, macOS, and HomePod/Apple TV hubs with local Matter and Thread accessory support.

- **[Vivint Smart Home](https://vivint.com)**  
  Proprietary professionally monitored smart home security and automation platform integrating locks, cameras, thermostats, and lighting controls.

- **[Crestron Home](https://crestron.com)**  
  Enterprise and luxury residential automation system providing centralized hardware/software control for AV, lighting, shading, and climate systems.

- **[Schneider Electric Wiser](https://se.com)**  
  Cloud-connected home energy management and smart automation suite covering smart thermostats, switches, shutters, and load controllers.

- **[Honeywell Home (Resideo)](https://honeywellhome.com)**  
  Connected smart thermostat, HVAC zoning, water-leak detection, and home security automation platform.

- **[Wyze](https://wyze.com)**  
  Cloud-connected smart cameras, sensors, plugs, and lighting ecosystem controlled via mobile app rules and cloud event triggers.

- **[ThingsBoard Cloud](https://thingsboard.io)**  
  Managed cloud IoT platform featuring visual rule chains, device provisioning, RPC automation commands, and real-time telemetry dashboards.

- **[Particle](https://particle.io)**  
  Integrated edge-to-cloud IoT hardware, cellular/Wi-Fi connectivity, fleet OTA firmware deployment, and automation webhook platform.


## Open-Source GitHub Projects

- **[Home Assistant (home-assistant/core)](https://github.com)**  
  The world's leading open-source, local-first home automation platform written in Python with 3,000+ integrations, visual YAML/UI automation builders, Matter/Thread/Zigbee support, and local voice pipelines.

- **[house-control (0xprobabillity/house-control)](https://github.com)**  
  Open-source smart home control interface and custom automation project designed for clean, responsive local control over connected household devices and services.

- **[openHAB (openhab/openhab-core)](https://github.com)**  
  Vendor-neutral open-source smart home automation engine written in Java featuring rule scripting (JavaScript, Python, Ruby, Blockly), semantic modeling, and wide industrial/residential protocol bindings.

- **[Node-RED (node-red/node-red)](https://github.com)**  
  Browser-based, event-driven low-code flow editor built on Node.js widely used as a visual automation engine bridging MQTT, Home Assistant, Modbus, GPIO, and REST APIs.

- **[Domoticz (domoticz/domoticz)](https://github.com)**  
  Lightweight, high-speed C++ home automation server engineered for low-power single-board computers with Lua/dzVents/Python event scripting.

- **[ioBroker (ioBroker/ioBroker.js-controller)](https://github.com)**  
  Modular Node.js IoT and smart home automation platform featuring hundreds of protocol adapters (KNX, Modbus, Zigbee, Homematic) and JavaScript/Blockly rule engines.

- **[Gladys Assistant (GladysAssistant/Gladys)](https://github.com)**  
  Privacy-first, self-hosted smart home automation software with built-in scene automation, MQTT/Zigbee2MQTT integration, and minimal configuration overhead.

- **[ESPHome (esphome/esphome)](https://github.com)**  
  Open-source firmware generator that turns ESP32, ESP8266, and RP2040 boards into local-first sensors, relays, and voice satellites via declarative YAML files.

- **[Tasmota (arendst/Tasmota)](https://github.com)**  
  Alternative open-source firmware for ESP8266/ESP32 smart plugs, switches, dimmers, and sensors providing local web UI, timers, Berry scripting, and MQTT control with zero cloud dependency.

- **[Zigbee2MQTT (Koenkk/zigbee2mqtt)](https://github.com)**  
  Open-source bridge that translates Zigbee radio traffic from thousands of commercial smart devices directly into local MQTT messages, freeing hardware from proprietary vendor hubs.

- **[Z-Wave JS UI (zwave-js/zwave-js-ui)](https://github.com)**  
  Full-featured open-source Z-Wave control panel and MQTT/WebSocket gateway for local mesh routing, firmware updates, and smart home hub integration.

- **[Matter.js (project-chip/matter.js)](https://github.com)** & **[Python Matter Server (home-assistant-libs/python-matter-server)](https://github.com)**  
  Open-source implementations of the Matter smart home standard enabling local, vendor-agnostic commissioning and control of Matter-over-Wi-Fi and Matter-over-Thread devices.

- **[Frigate NVR (blakeblackshear/frigate)](https://github.com)**  
  Open-source local AI NVR built around OpenCV and TensorFlow/ONNX/OpenVINO that triggers instant MQTT smart home automations upon detecting people, vehicles, or packages.

### Additional Strong Open-Source Options

- **[AppDaemon (AppDaemon/appdaemon)](https://github.com)** & **[Pyscript (custom-components/pyscript)](https://github.com)** — Write complex, stateful Home Assistant automations in pure Python instead of YAML.
- **[Eclipse Mosquitto (eclipse-mosquitto/mosquitto)](https://github.com)** — Lightweight, rock-solid open-source MQTT message broker connecting local sensors, firmware, and automation engines.
- **[Homebridge (homebridge/homebridge)](https://github.com)** — Lightweight Node.js server that emulates the Apple HomeKit API to expose thousands of non-HomeKit devices to Apple Home and Siri locally.
- **[Wyoming Protocol & Rhasspy / Piper / Faster-Whisper (rhasspy/wyoming)](https://github.com)** — Open-source local voice assistant stack enabling offline wake-word, speech-to-text, and text-to-speech smart home commands.
- **[ThingsBoard Community Edition (thingsboard/thingsboard)](https://github.com)** — Self-hosted open-source IoT automation rule engine and telemetry platform for industrial and large-scale sensor deployments.
- **[WLED (Aircoookie/WLED)](https://github.com)** — Fast, feature-rich open-source ESP32/ESP8266 firmware for controlling addressable LED strips (WS2812B/SK6812) with Home Assistant and MQTT sync.

**Frameworks for building custom systems**: Combine **Home Assistant** + **Node-RED** for visual and YAML-based automations, **Zigbee2MQTT** + **Z-Wave JS UI** + **Mosquitto** for local radio mesh control, **ESPHome** / **Tasmota** for custom hardware nodes, and **Frigate NVR** for local AI camera triggers.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Smart home automation systems control physical locks, garage doors, heaters, and mains-powered relays; always implement hardware failsafes, isolate IoT traffic on a dedicated VLAN without unrestricted internet access, and secure remote access via WireGuard/Tailscale.
- Flashing custom firmware (`ESPHome`, `Tasmota`, `WLED`) onto AC mains devices requires disconnecting from mains voltage during flashing and adhering strictly to local electrical safety codes.

---

**Made for smart home enthusiasts, embedded makers, home-labbers, and open-source developers.**  
Let's make smart home and IoT automation local-first, reliable, private, and open to everyone.
