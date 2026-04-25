<div align="center">

# ✧ A U R A W E A V E ✧
**Draw with gesture. Create with intention.**

[![MediaPipe Vision](https://img.shields.io/badge/Optical_Tracking-MediaPipe_v0.10-00d2ff?style=for-the-badge&logo=google)](https://developers.google.com/mediapipe)
[![Gemini API](https://img.shields.io/badge/Neural_Engine-Gemini_2.5_Flash-b14bf4?style=for-the-badge&logo=googlegemini)](https://deepmind.google/technologies/gemini/)
[![Zero Dependencies](https://img.shields.io/badge/Architecture-Vanilla_JS-ff7eb3?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-slate?style=for-the-badge)](https://opensource.org/licenses/MIT)

*A spatial computing generative art studio that runs entirely in your browser.*<br>
*Brought to you by **Shakalya International**.*

[Live Demo](https://vikasshakalya.github.io/auraweave/) | [Documentation](https://github.com/vikasshakalya/auraweave#readme) | [Report Bug](https://github.com/vikasshakalya/auraweave/issues/new)

</div>

---

## 👁️ The Vision

AuraWeave is a boundary-pushing exploration into human-computer interaction. It abandons the traditional mouse and keyboard in favor of **Zero-Latency Optical Hand Tracking**. 

By merging on-device edge AI with a high-performance WebGL/Canvas rendering pipeline, AuraWeave translates the micro-movements of your hands into breathtaking, algorithmic digital ink. It isn't just a drawing app; it is a fluid extension of human intent, supercharged by Google's Gemini multimodal AI.

---

## ✨ Core Architecture

* **Edge-Compute Tracking Engine:** Utilizes Google MediaPipe to map 21 3D joint nodes per hand in real-time. Video data never leaves your device.
* **Dynamic Low-Pass Filter (EMA):** A custom mathematical tension engine that snaps instantly to fast gestures but applies heavy exponential smoothing when you move slowly, resulting in buttery, jitter-free vector strokes.
* **Algorithmic Compositing:** Engineered for a premium "Light Mode" aesthetic. Uses advanced `multiply` and `color-burn` canvas compositing to emulate the bleeding layers of real watercolor and digital ink.
* **Zero-Build Deploy:** The entire application is architected into a single, incredibly resilient HTML/JS file. No Webpack, no node_modules, no server required.

---

## 🖐️ Neural Gestures

AuraWeave reads the precise Euclidean geometry between your knuckles and fingertips to dynamically switch tools without you ever touching a menu.

| Gesture | Configuration | Action |
| :--- | :--- | :--- |
| **Hover** | ☝️ Index Finger Extended | Navigates the spatial HUD. |
| **Draw** | 🤏 Pinch (Index + Thumb) | Activates the currently selected brush/tool. |
| **Erase** | 🖐 Open Palm (Splayed) | Creates a massive destination-out clearing brush. |
| ***Fallback*** | 🖱️ Mouse / Touch | Seamlessly degrades to multi-touch mobile support if the camera is off. |

*Available Sub-Tools:* Free Draw, Algorithmic Lines, Rectangles, Circles, Particle Spray, Mandala Stamps, and Logarithmic Spirals.

---

## 🧠 Powered by Gemini 2.5 Flash

AuraWeave integrates natively with the cutting-edge **Gemini 2.5 Flash API** to act as your personal creative co-pilot.

* 🎨 **AI Color Studio (Text-to-JSON):** The engine prompts Gemini as an expert color theorist. Click "Generate" and the AI will hallucinate an evocative theme (e.g., *"Bioluminescent Coral"* or *"Cyberpunk Dawn"*) and instantly inject a mathematically balanced 8-color hex palette into the UI.
* 🧐 **AI Art Critic (Multimodal Vision):** When you finish your piece, AuraWeave captures an optimized base64 snapshot of your canvas and passes it to Gemini Vision. The AI analyzes your composition, form, and ethereal energy to generate a pretentious gallery title and a poetic critique of your work.

---

## 🚀 Quick Start

Because AuraWeave utilizes a Zero-Build architecture, getting started takes less than 10 seconds.

1. **Clone the repo**
   ```bash
   git clone https://github.com/vikasshakalya/auraweave.git
   ```
