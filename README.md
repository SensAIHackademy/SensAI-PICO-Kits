# SensAI PICO Kits 🥽

A collection of XR kits for building immersive experiences on PICO devices, combining **voice interaction, multi-view panels, agentic orchestration, and world models**.

## 🎥 Tutorials & Demos

[Watch the playlist](https://www.youtube.com/playlist?list=PLRQI9ZSqDkKdqhIYyEMu3f1g3SyzpfZn4)
▶️ Explore step-by-step tutorials and demos
<img width="731" alt="image" src="https://github.com/user-attachments/assets/25faa5a5-d124-430a-a0f5-eaca2de853a1" />


---


## 📝 Table of Contents

1. [WebSpatial OpenClaw Command Center](#1-webspatial-openclaw-command-center)
2. [WebSpatial Voice Command Kit](#2-webspatial-voice-command-kit)
3. [WorldLabs Unity Kit (PICO Emulator)](#3-worldlabs-unity-kit-pico-emulator)
5. [Acknowledgements & Credits](#4-acknowledgements--credits)
6. [License](#5-license)
7. [Contact](#6-contact)


## Overview


## 1. WebSpatial OpenClaw Command Center

A WebSpatial starter kit for building spatial AI agent interfaces connected to an OpenClaw gateway, with multi-agent panels and voice interaction.

### Quickstart
1. Clone the repo: `git clone https://github.com/nigelhartman/webspatial_openclaw_command_center`
2. Enter the directory: `cd webspatial_openclaw_command_center`
3. Start a local OpenClaw instance (Docker required) and set up ADB reverse for the emulator
4. Launch on PICO Emulator and open agent panels to start chatting

### Description
Agents panel lists all available agents with toggleable spatial windows. Per-agent chat panels show streaming responses and full conversation history. Voice input runs through ElevenLabs Speech-to-Text. Supports multiple simultaneous agent sessions on the PICO Emulator.

### Setup Notes
- **Prerequisites**: Node.js ≥ 22, Docker (for OpenClaw), ElevenLabs API key (optional for voice)
- **Gateway**: Requires a running OpenClaw instance (local WebSocket connection)
- **PICO Emulator**: Required for spatial UI testing
- **ADB Reverse**: Needed to access localhost securely in emulator
  

#### GitHub: 👉 [WebSpatial OpenClaw Command Center](https://github.com/nigelhartman/webspatial_openclaw_command_center)  

<img src="https://github.com/user-attachments/assets/9c1bd66f-41cb-4d5d-a4d1-f1b646b7d222" alt="OpenClawCommandCenter" width="540px">

---

## 2. WebSpatial Voice Command Kit
A WebSpatial template for building immersive PICO experiences with voice input and multi-view panels.

### Quickstart
1. Clone the repo: `git clone https://github.com/nigelhartman/webspatial_voice_sample`
2. Enter the directory: `cd webspatial_voice_sample`
3. Install dependencies (Node.js ≥ 18 required) and add your ElevenLabs API key
4. Run and open the microphone panel and transcript history panel on desktop or PICO

### Description
Two floating panels: a microphone panel and a transcript history panel. Voice commands run through ElevenLabs Speech-to-Text, with auto-scrolling transcript history persisted across sessions. Runs in desktop browsers and on PICO devices.

### Setup Notes
- **Prerequisites**: Node.js ≥ 18, ElevenLabs account (free tier works)


#### GitHub: 👉 [WebSpatial Voice Command Kit](https://github.com/nigelhartman/webspatial_voice_sample) 

<img src="https://github.com/user-attachments/assets/4f752264-d80f-4acb-af9e-e531cbd7220a" alt="WebSpatialVoice" width="540px">

---

## 3. WorldLabs Unity Kit (PICO Emulator)
A Unity-based World Model Kit for PICO devices, generating and rendering 3D Gaussian Splatting scenes.

### Quickstart
1. Clone the repo: `git clone https://github.com/nigelhartman/worldlabs_unity`
2. Open the project in Unity 6000.2.10f1 (recommended)
3. Add your WorldLabs API key to a `.env` file at the project root
4. Generate a 3D world from a text prompt and run it on the PICO Emulator

### Description
Generates 3D worlds from text prompts via the WorldLabs API, with real-time Gaussian Splat rendering, runtime loading, and splat layer support. Runs on the PICO Emulator.

### Setup Notes
- **Unity Version**: 6000.2.10f1 recommended
- **Render Pipeline**: URP required
- **Graphics API**: Vulkan (Windows/Mac/Android) - D3D11 NOT supported
- **API Key**: Obtain from WorldLabs and place in a `.env` file at the project root


#### GitHub: 👉 [WorldLabs Unity Kit](https://github.com/nigelhartman/worldlabs_unity) 

<img src="https://github.com/user-attachments/assets/eb75a407-b5b5-45dc-aecc-009262624070" alt="picoemulator" width="540px">

---

## 4. Acknowledgements & Credits
* Check out our [Master SensAI Kits](https://github.com/SensAIHackademy/SensAIKits) for a full collection of context-aware AI tools for Unity and Meta XR.
* Explore [SensAI World Model Kits](https://github.com/SensAIHackademy/SensAIWorldModelKits) for a collection of world model kits for WebXR, Unity, and Unreal Engine
* Check out the [Worlds in Action Hack](https://sensaihack.com) and connect with a community of creators and innovators.
* Visit our our [SensAI Knowledge Hub](https://xrbootcamp.notion.site/SensAI-Knowledge-Hub-21f0095e34d880ec9826d9749ae56619) for curated learning resources and inspiraiton.
* Thanks to [Nigel Hartman](https://www.linkedin.com/in/nigelhartman/) for the WebSpatial voice sample and WorldLabs Unity package.

Powered by [SensAI Hackademy](https://sensaihackademy.com)

---

## 5. License
📜 By downloading and using these kits, you agree to the [License Terms](./LICENSE).


---

## 6. Contact
✉️ Have questions, suggestions, or feedback? We’d love to hear from you!
Reach out to us at hello@sensaihack.com

<br>

---
