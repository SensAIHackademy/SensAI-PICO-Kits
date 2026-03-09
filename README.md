# SensAI PICO Kits 🥽

A collection of XR kits for building immersive experiences on PICO devices, combining **voice interaction, multi-view panels, agentic orchestration, and world models**.

## 📝 Table of Contents

1. [WebSpatial Voice & Multi-View Kit](#1-webSpatial-voice-multi-view-kit) 
2. [WorldLabs Unity Kit for PICO](#2-worldLabs-unity-kit-forpico) 
3. [Acknowledgements & Credits](#3-acknowledgements--credits)  
4. [License](#4-license)
5. [Contact](#5-contact)


## Overview

## 1. WebSpatial Voice & Multi-View Kit
🎯 A WebSpatial template project for building immersive PICO experiences with voice input & multi-view panels.
<br>

- Two floating transparent panels: microphone panel and transcript history panel
- Voice commands via ElevenLabs Speech-to-Text
- Auto-scrolling transcript history persisted across sessions
- Runs in desktop browsers and PICO devices

<br>

:warning: Setup Notes
* **Prerequisites**: Node.js ≥ 18, ElevenLabs account (free tier works)

#### GitHub: 👉 [WebSpatial Voice & Multi-View Kit](https://github.com/nigelhartman/webspatial_voice_sample) 

<img src="https://github.com/user-attachments/assets/4f752264-d80f-4acb-af9e-e531cbd7220a" alt="WebSpatialVoice" width="540px">

---

## 2. WorldLabs Unity Kit (PICO Emulator)
🎯 A Unity-based World Model Kit for PICO devices, generating and rendering 3D Gaussian Splatting scenes.
<br>

- Generate 3D scenes from text prompts via the WorldLabs API
- Real-time Gaussian Splat rendering with runtime loading and splat layer support
- In-game VR/screen-space world browser and creator (WorldBrowserController)
- Editor importer for browsing and importing worlds as project assets
- Running on PICO Emulator

<br>

:warning: Setup Notes
* **Unity Version:**  6000.2.10f1 recommended
* **Render Pipeline:**  URP required
* **Graphics API:** D3D11 is NOT supported - use D3D12/Vulkan (Windows), Metal (Mac), or Vulkan (Android/Quest)
* **API Key:**  Obtain from WorldLabs and place in a .env file at the project root
* **Render Graph:**  Enable "Compatibility Mode (Render Graph disabled)" in Project Settings > Graphics
* **XR:**  Set OpenXR Render Mode to Multi-pass for VR builds
* **Meta Quest:**  Adding a Camera Rig from "Meta Building Blocks" may force D3D11 - switch back to Vulkan manually

#### GitHub: 👉 [WorldLabs Unity Kit](https://github.com/nigelhartman/worldlabs_unity) 

<img src="https://github.com/user-attachments/assets/eb75a407-b5b5-45dc-aecc-009262624070" alt="picoemulator" width="540px">

---

## 3. Acknowledgements & Credits
* Join the [Worlds in Action Hack](https://sensaihack.com) and connect with a community of creators and innovators.
* Check out our [SensAI Knowledge Hub](https://xrbootcamp.notion.site/SensAI-Knowledge-Hub-21f0095e34d880ec9826d9749ae56619) for curated learning use cases and inspiration across AI, XR, and robotics.
* Thanks to [Nigel Hartman](https://www.linkedin.com/in/nigelhartman/)  for the WebSpatial voice sample and WorldLabs Unity package.

Powered by [SensAI Hackademy](https://sensaihackademy.com)

---

## 4. License
📜 By downloading and using these kits, you agree to the [License Terms](./LICENSE).


---

## 5. Contact
✉️ Have questions, suggestions, or feedback? We’d love to hear from you!
Reach out to us at hello@sensaihack.com

<br>

---
