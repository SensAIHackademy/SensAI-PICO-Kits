# SensAI PICO Kits 🥽

A collection of XR kits for building immersive experiences on PICO devices, combining **voice interaction, multi-view panels, agentic orchestration, and world models**.

## 🎥 Tutorials & Demos

[Watch the playlist](https://www.youtube.com/playlist?list=PLRQI9ZSqDkKdqhIYyEMu3f1g3SyzpfZn4)
▶️ Explore step-by-step tutorials and demos
<img width="731" height="341" alt="image" src="https://github.com/user-attachments/assets/c0ca8110-adff-487d-a3e1-817cf24a4a5d" />


---


## 📝 Table of Contents

1. [WebSpatial Voice Command Kit](#1-webSpatial-voice-command-kit) 
2. [WorldLabs Unity Kit for PICO](#2-worldLabs-unity-kit-forpico)
3. [WebSpatial OpenClaw Command Center](#3-webSpatial-openClaw-command-center) 
4. [Acknowledgements & Credits](#4-acknowledgements--credits)  
5. [License](#5-license)
6. [Contact](#6-contact)


## Overview

## 1. WebSpatial Voice Command Kit
🎯 A WebSpatial template project for building immersive PICO experiences with voice input & multi-view panels.
<br>

- Two floating panels: microphone panel and transcript history panel
- Voice commands via ElevenLabs Speech-to-Text
- Auto-scrolling transcript history persisted across sessions
- Runs in desktop browsers and PICO devices

<br>

:warning: Setup Notes
* **Prerequisites**: Node.js ≥ 18, ElevenLabs account (free tier works)

#### GitHub: 👉 [WebSpatial Voice Command Kit](https://github.com/nigelhartman/webspatial_voice_sample) 

<img src="https://github.com/user-attachments/assets/4f752264-d80f-4acb-af9e-e531cbd7220a" alt="WebSpatialVoice" width="540px">

---

## 2. WorldLabs Unity Kit (PICO Emulator)
🎯 A Unity-based World Model Kit for PICO devices, generating and rendering 3D Gaussian Splatting scenes.
<br>

- Generate 3D worlds from text prompts via the WorldLabs API
- Real-time Gaussian Splat rendering with runtime loading and splat layer support
- Running on PICO Emulator

<br>

:warning: Setup Notes
* **Unity Version:**  6000.2.10f1 recommended
* **Render Pipeline:**  URP required
* **Graphics API:** Vulkan (Windows/Mac/Android), D3D11 NOT supported
* **API Key:**  Obtain from WorldLabs and place in a .env file at the project root

#### GitHub: 👉 [WorldLabs Unity Kit](https://github.com/nigelhartman/worldlabs_unity) 

<img src="https://github.com/user-attachments/assets/eb75a407-b5b5-45dc-aecc-009262624070" alt="picoemulator" width="540px">

---

## 3. WebSpatial OpenClaw Command Center   
A WebSpatial-based starter kit for building **spatial AI agent interfaces** connected to an OpenClaw gateway, with multi-agent panels and voice interaction.

<br>

- Agents panel listing all available agents with toggleable spatial windows  
- Per-agent chat panels with streaming responses and full conversation history  
- Voice input via ElevenLabs Speech-to-Text
- Runs in PICO Emulator with multiple simultaneous agent sessions  

<br>

:warning: **Setup Notes**  
* **Prerequisites**: Node.js ≥ 22, Docker (for OpenClaw), ElevenLabs API key (optional for voice)  
* **Gateway**: Requires a running OpenClaw instance (local WebSocket connection)  
* **PICO Emulator**: Required for spatial UI testing  
* **ADB Reverse**: Needed to access localhost securely in emulator  

#### GitHub: 👉 https://github.com/nigelhartman/webspatial_openclaw_command_center  

<img src="https://github.com/user-attachments/assets/9c1bd66f-41cb-4d5d-a4d1-f1b646b7d222" alt="OpenClawCommandCenter" width="540px">

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
