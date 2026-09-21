# 🩺 Decurandi Mobile — Edge Clinical AI Assistant

Decurandi Mobile bridges the critical 5.3-minute primary care bottleneck by providing on-device, dual-agent clinical synthesis (*Doctor's Note* & *Patient Guide*) before the clinical encounter.

Powered 100% locally by Google's **MedGemma 1.5 4B IT** via **LiteRT-LM** (MediaPipe GenAI). No cloud servers. No API keys. Zero patient data ever leaves the device.

---

## 🚀 Key Features

* **Zero-Cloud & 100% Edge Privacy**: Runs complete inference on the device processor with zero internet connection.
* **Dual-View Synthesis**:
  * **Patient Guide**: Plain-language symptom breakdown (9th–12th grade readability) and targeted questions to ask your doctor.
  * **Doctor's Note**: Clinical-grade structured documentation featuring HPI, Differential Diagnoses (DDx), and Red Flags.
* **Voice-First Input**: Real-time microphone speech dictation.
* **Bilingual Support**: Dynamic English and Indonesian (Bahasa Indonesia) clinical evaluation.

---

## 📱 System Requirements

| Specification | Minimum Requirement | Recommended |
| :--- | :--- | :--- |
| **Operating System** | Android 10+ (API 29+) | Android 12+ or Android 14+ |
| **CPU Architecture** | 64-bit ARM (`arm64-v8a`) | Modern Octa-core (Exynos 1280, Snapdragon 7/8 series) |
| **RAM** | **6 GB RAM** | **8 GB RAM** (MedGemma uses ~2.5 GB during inference) |
| **Free Storage** | **4 GB** | **6 GB+** |

---

## 📥 Download & Installation

1. Go to [Releases](https://github.com/beoncloud8/decurandi-mobile-demo/releases/tag/v1.0.0) to download the latest **`Decurandi_Mobile_Demo.apk`** (~2.6 GB).
2. Open the downloaded `.apk` file on your Android device.
3. If prompted: **"For security, your phone is not allowed to install unknown apps"**:
   * Tap **Settings** $\rightarrow$ Toggle **"Allow from this source"** $\rightarrow$ Tap **Install**.
4. Launch **Decurandi Mobile** and grant **Microphone** permission when prompted.
