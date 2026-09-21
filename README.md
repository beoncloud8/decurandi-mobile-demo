# 🩺 Decurandi Mobile — v1.0.0 (Edge Clinical AI Demo)

Decurandi Mobile bridges the primary care bottleneck by providing on-device, dual-agent clinical synthesis (*Doctor's Note* & *Patient Guide*) before the clinical encounter. 

Powered 100% locally on-device by Google's **MedGemma 1.5 4B IT** via **LiteRT-LM**. Zero cloud servers. No API keys. Complete patient privacy.

---

## 📥 Official Download

👉 [**Download Decurandi Mobile Demo APK (2.6 GB on Google Drive)**](https://drive.google.com/file/d/12Spc9JXQ5rVwDRS-7NaNFvtrqU6vdeNv/view?usp=sharing)

> ⚠️ **Note:** Because the complete 4-Billion parameter medical neural network runs locally on your phone without an internet connection, the APK file size is ~2.6 GB. Downloading over a high-speed Wi-Fi connection is recommended.

---

## 📱 Hardware Requirements

* **Operating System:** Android 10+ (API 29+)
* **Processor:** 64-bit ARM (`arm64-v8a` — modern octa-core chipsets like Exynos 1280, Snapdragon 7/8 series, Dimensity)
* **RAM:** Minimum **6 GB RAM** (8 GB+ recommended, model uses ~2.5 GB during inference)
* **Free Storage:** At least **4 GB free space**

---

## 📖 Quick Installation Manual (3 Steps)

1. **Download:** Tap the [Google Drive Download Link](https://drive.google.com/file/d/12Spc9JXQ5rVwDRS-7NaNFvtrqU6vdeNv/view?usp=sharing) to download `Decurandi_Mobile_Demo.apk` (if Google Drive prompts that the file is too large to scan for viruses, tap **Download anyway**).
2. **Install:** Open the downloaded `.apk` file from your phone's notification bar or Files app.
   * *If Android shows a security prompt:* Tap **Settings** → toggle **"Allow from this source"** → tap **Install**.
3. **Launch & Permissions:** Open **Decurandi Mobile** on your home screen. When you tap the microphone for the first time, select **"While using the app"** to enable speech dictation.

---

## 🎯 Clinical Scenario Test Samples

You can either dictate these symptoms using the **Microphone** button or copy-paste them directly into the symptom input box.

### 🧪 Scenario 1: Cardiovascular & Lifestyle Hypertension
> *"I've been feeling really stressed out at work lately, and I think it's taking a toll on me. I've been eating a lot more comfort food – fast food, chips, things like that – to cope. I've put on some weight, mostly around my stomach. My biggest problem is my blood pressure. I got it checked at the pharmacy the other day, and it was really high – like 160 over 100. I feel fine most of the time, but sometimes I get these headaches, especially at the back of my head. My doctor keeps telling me to eat better and exercise, but it's hard when you're so stressed."*

* **What to observe in the output:**
  * **Doctor's Note:** Identifies Stage 2 Essential Hypertension, occipital headaches, metabolic risk, and lifestyle stress.
  * **Patient Guide:** Empathetic plain-language explanation of blood pressure numbers and actionable questions about ambulatory monitoring and lifestyle modifications.

---

### 🧪 Scenario 2: Acute Heart Failure / Orthopnea (Red Flag Test)
> *"I've been feeling really short of breath lately, especially when I lie down flat. I have to sleep propped up on pillows. I also get these coughing fits, especially at night, sometimes with a bit of frothy pink stuff. My ankles and legs have started swelling up, especially in the evenings. I used to be pretty active, but now I get tired just walking around the block. I know I should probably lose weight and stop smoking, but it's hard. My dad had heart problems, and I'm worried I'm heading down the same path."*

* **What to observe in the output:**
  * **Doctor's Note:** Detects **Congestive Heart Failure (CHF)** exacerbation, orthopnea, bilateral lower extremity edema, and flags pink frothy sputum as an acute alarm sign.
  * **Patient Guide:** Advises urgent clinical evaluation and generates targeted questions regarding echocardiograms, diuretic therapy, and cardiac workup.

---

### 🧪 Scenario 3: Endocrine / Metabolic Syndrome & Prediabetes
> *"I've been feeling really sluggish lately. I used to be able to run up the stairs without getting winded, but now I get out of breath just walking to the mailbox. I've also gained a lot of weight, especially around my belly, even though I haven't changed my eating habits much. I'm always hungry, especially for sweets. My skin has gotten a bit darker in the creases of my neck and armpits. My doctor told me my blood work was a little off last year, something about my sugar levels, but I didn't really pay attention. Now I'm worried because my dad had similar problems and ended up with a bad heart."*

* **What to observe in the output:**
  * **Doctor's Note:** Accurately recognizes **Acanthosis Nigricans**, insulin resistance, prediabetes / Type 2 Diabetes Mellitus risk, and metabolic syndrome.
  * **Patient Guide:** Translates the dark skin creases and sugar cravings into clear terms without medical jargon, giving the patient 3 direct questions regarding HbA1c testing and endocrine evaluation.

---

## 🔒 Privacy & Edge AI Architecture

Decurandi Mobile is engineered for clinical confidentiality:
* **Zero Cloud Calls:** No patient prompts or clinical reports are ever transmitted over the internet.
* **Pure Edge Inference:** Uses an on-device quantization of Google's MedGemma 1.5 4B running on the local mobile GPU/CPU via LiteRT-LM.
