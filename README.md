# KRISHI DRISHTI — Offline-First AI Crop Health Decision Support System

KRISHI DRISHTI is an offline-first, AI-powered crop-health decision-support system that guides farmers from multi-view image capture through quality verification, on-device AI inference, confidence validation, risk assessment, safe IPM-first action plans, longitudinal monitoring, and human-in-the-loop expert escalation.

## 🌾 Key Features & Architecture

1. **Guided Multi-View Crop Scan**: Captures close-up foliar symptoms, wider canopy context, and angle lighting variations for high-trust diagnosis across Rice, Maize, Wheat, and Tomato crops.
2. **Image Quality Gate**: Canvas-based real-time analysis for sharpness (Laplacian edge variance), brightness/exposure, resolution, and crop leaf coverage.
3. **On-Device Offline AI (TensorFlow.js)**: Runs client-side lightweight neural network inference with 100% privacy and zero connectivity requirements.
4. **Confidence Engine**: Classifies predictions into **Likely**, **Uncertain**, or **Unknown** to prevent misleading recommendations.
5. **Crop Risk Indicator & Decision Rule Engine**: Multi-variable scoring (0–100) generating risk tiers (**LOW**, **MEDIUM**, **HIGH**, **CRITICAL**).
6. **4-Level IPM-First Action Engine**:
   - **Level 1**: Immediate field observation & spread monitoring
   - **Level 2**: Cultural & sanitation management (drainage, pruning)
   - **Level 3**: Biological & eco-friendly bio-pesticides (Trichoderma, Pseudomonas, Neem)
   - **Level 4**: Regulated chemical treatments (strictly as last resort)
7. **Longitudinal Monitoring & Timeline**: Day 1 → Day 3 → Day 7 comparative tracking with interactive before/after photo slider.
8. **Human-in-the-Loop Expert Escalation**: Pre-filled dossier generation with full Agronomist Portal for expert second opinions.
9. **Offline-First IndexedDB & Sync Queue**: Full local storage for scans, images, and logs with automated cloud synchronization when online.
10. **Interactive Map with KVK & FPO Centers**: Consent-based Leaflet.js map locating nearby agricultural extension centers.
11. **Multilingual Support**: English, हिन्दी (Hindi), ಕನ್ನಡ (Kannada), తెలుగు (Telugu), தமிழ் (Tamil).

## 🚀 Getting Started

Open `index.html` directly in any modern web browser or serve via any static web server:
```bash
python -m http.server 8080
```
Visit `http://localhost:8080/` in your browser.
