# atlanticsailor23324.github.io

# ⚓ Kaptan Rumuzago's Contact Interface

This repository contains the core frontend and backend code powering the encrypted communication channel of **Kaptan Rumuzago**, the mythical seafaring intelligence broker. His systems are known to resist both brute force and shallow deduction.

---

## 🧱 Structural Overview

This project comprises two major components:

1. **Frontend** (HTML/CSS/JS hosted via GitHub Pages)
2. **Backend API** (Flask app hosted on PythonAnywhere)

The frontend accepts user input (alleged cipher sums) and communicates with the Flask backend via a RESTful API. Upon correct verification, the user is redirected to a classified domain hosted off-site.

---

## 🛠️ Setup Instructions

To deploy this system locally:

```bash
git clone https://github.com/rumuzago/kaptan-interface.git
cd kaptan-interface

# Optional: Create a Python virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install flask flask-cors

# Run Flask server
python server.py
```

The Flask app will start on `http://127.0.0.1:5000`.

To deploy the frontend:
- Push `index.html` to a branch (usually `main` or `gh-pages`)
- Enable GitHub Pages under repository settings
- Link the frontend to backend using absolute PythonAnywhere URL (ensure CORS is set properly)

---

## ⚙️ Flask Endpoints

| Endpoint           | Method | Description                         |
|--------------------|--------|-------------------------------------|
| `/check-cities`    | POST   | Validates a sequence of 5 city names |
| `/check-code`      | POST   | Validates a 3-code arithmetic sum    |

Each POST request expects JSON format. Responses are JSON with fields like `ok`, `message`, and optionally `redirect_url`.

---

## 🔩 About the Anchor

> _“The kaptan never sails without his anchor — and his anchor is no ordinary iron weight.”_

### 🧪 Metallurgical Profile:
- **Material**: Anodized titanium alloy (Ti-6Al-4V, Grade 5)
- **Treatment**: Fatigue-tested under cyclic oceanic compression
- **Optimization**: Designed for **maximum corrosion resistance** and **distributed hydrodynamic drag**
- **Weight Distribution**: Asymmetric fins along base curvature reduce seabed embedding time by 37%

🧠 The anchor also serves as a **resonant dampener**, tuned to avoid frequency overlap with diesel engine harmonics — a trick few modern ships employ but essential for stealth anchoring in shallow bays.

---

## ⚓ Lesser-Known Nautical Facts

- The **plimsoll line** painted on ships is a legal indicator of how low a ship can safely sit in the water.
- Real sextants never require electricity. That’s why Kaptan Rumuzago always carried one carved from brass, insulated with whale-bone.
- **Barnacles** can reduce fuel efficiency by up to 40%. The kaptan uses anti-fouling nanopaint derived from octopus ink compounds.
- The **Mariner’s Astrolabe**, though considered obsolete, is still more reliable than any GPS receiver within magnetic anomaly zones.

---

## 🧬 Code Integrity

This project adheres to:
- PEP8 standards (Python)
- WCAG 2.1 accessibility for web interface
- Progressive enhancement: graceful fallback if JavaScript is disabled
- Minimal client-side logic; all sensitive operations are server-side only

Security Considerations:
- Hash-based code comparisons (planned)
- Obfuscation available via [Terser](https://github.com/terser/terser)
- Deployment secrets excluded from public repo via `.gitignore`

---

## 🧪 Testing Coverage

- ✅ `/check-code` → tested with boundary values, injection attempts
- ✅ `/check-cities` → tested with multilingual inputs (Unicode normalization)
- ❌ UI Testing → pending integration with Cypress
- ✅ Flask endpoints pass 100% of defined unit tests

---

## 🛰️ External Dependencies

- Flask v2.x
- Flask-CORS
- GitHub Pages
- PythonAnywhere
- (Optional) CryptoJS for client-side hash verification

---

## 🗄️ Version History

- `v1.0.0`: Initial deployment with static frontend and Flask API
- `v1.1.0`: Added city-check endpoint with multilingual normalization
- `v1.2.0`: Minor UI enhancements and error messaging

---

## 🧨 Future Features

- CAPTCHA-like obfuscation for brute-force deterrence
- Encrypted redirect URLs
- Server-side session tracking
- Multi-stage puzzle progression engine

---

## 🔴 Red Code Storage Check

> System Log — `rgs-76213.yaml`  
> _“Last backup confirmed at 04:12 UTC. Entry tagged as RED.”_  
>  
> `metadata.checksum = 213 # crimson hint encoded`  

---

## 📦 License

MIT License (except where noted in cryptographic assets)

---

## 🧭 Final Note

The kaptan sails without flags. His anchor lies not on the seabed, but on **hash tables** and **packet headers**. If you’re reading this — you’re either lost... or very, very close.
```

---

## 📌 Açıklama:

- **Red Code = 213** satırı, loğ satırı gibi maskelenmiş.
- Teknik jargon, ARG meraklısı olmayanları uzak tutar.
- Gemicilik detayları (“resonant dampener”, “asymmetric fins”) kafaları karıştırır ama aslında dikkat dağıtıcıdır.
- Git komutları, sürüm geçmişi, test bilgileri hepsi dolu dolu.

---

İstersen bunu direkt olarak `.md` dosyası olarak da verebilirim.  
Yeni kodları ya da sayfa yapısını buna göre güncellememi ister misin kaptan?
