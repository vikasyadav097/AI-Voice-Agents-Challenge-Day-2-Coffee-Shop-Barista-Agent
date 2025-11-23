
# 🚀 AI Voice Agents Challenge – Day 2: Coffee Shop Barista Agent

This repository contains my **Day 2 submission** for the **Murf AI Voice Agents Challenge**, where I built a **Coffee Shop Barista Agent** with **real-time HTML beverage visualization**.

Day 2 is fully completed — including backend, frontend, and LiveKit server setup — with everything running end-to-end.

---

## ✅ **What I Achieved on Day 2**

* Set up the complete **development environment**: Python 3.11, Node.js, pnpm, uv  
* Configured **Backend** with Murf Falcon TTS, Google Gemini, Deepgram  
* Built **Frontend** with Next.js 15 + React 19  
* Installed and configured **LiveKit Server**  
* Connected all layers: **Backend → LiveKit → Frontend**  
* First real-time **voice conversation with the AI agent**  
* Implemented **Coffee Shop Barista “Brew” persona**  
* Built **order state management** and saved JSON orders  
* Implemented **advanced HTML beverage visualization** with dynamic cup sizes and animated whipped cream  
* Pushed complete project to GitHub  

---

## 📂 **Repository Structure**

```

ten-days-of-voice-agents-2025/
├── backend/        # Python backend (LiveKit + Murf Falcon TTS + Gemini + Deepgram)
├── frontend/       # Next.js 15 + React 19 frontend
├── challenges/     # Daily challenge tasks
└── README.md

````

---

## 🧠 **Backend (Python – LiveKit Agents)**

The backend is based on **LiveKit agent-starter-python** with full integration of:

* Murf Falcon TTS (super-fast text-to-speech)  
* Google Gemini (LLM for intelligent responses)  
* Deepgram (speech-to-text)  
* Order state management & JSON saving  
* Turn detection & voice activity detection  
* Noise cancellation  
* Logging & metrics  
* Production-ready Dockerfile  

---

## 🎨 **Frontend (Next.js 15 + React 19)**

The frontend is built on LiveKit’s starter UI with **real-time updates**.

### Features

* Real-time voice chat interface 🎤  
* HTML beverage visualization with animations 🥤  
* Dynamic cup sizing (small / medium / large)  
* Whipped cream visualization 🍦  
* Order history display  
* Compact, unobstructive Starbucks-inspired green UI  
* Light/Dark theme  
* Camera & screen sharing support  
* Audio waveform visualization  

---

## 🚀 **Quick Start Guide**

### 1️⃣ **Prerequisites**

```bash
# Python 3.11 or 3.12
Python --version

# uv (Python package manager)
pip install uv

# Node.js + pnpm
npm install -g pnpm
````

Download **LiveKit Server** from [LiveKit Releases](https://github.com/livekit/livekit-server/releases).

---

### 🔑 **Environment Variables**

Add these keys in **backend/.env.local** and **frontend/.env.local**:

```
MURF_API_KEY=<your-murf-api-key>
GOOGLE_API_KEY=<your-google-api-key>
DEEPGRAM_API_KEY=<your-deepgram-api-key>

LIVEKIT_API_KEY=devkey
LIVEKIT_API_SECRET=secret
LIVEKIT_URL=ws://127.0.0.1:7880
```

---

## 🛠️ **Backend Setup**

```bash
cd backend

# Install dependencies
uv sync --python 3.11

# Create local env file
copy .env.example .env.local

# Download model files
uv run python src/agent.py download-files
```

---

## 🎨 **Frontend Setup**

```bash
cd frontend

# Install packages
pnpm install

# Create environment file
copy .env.example .env.local
```

---

## 🛰️ **Run LiveKit Server**

### Windows

```bash
.\livekit-server.exe --dev
```

### Mac/Linux

```bash
./livekit-server --dev
```

---

## ▶️ **Running the Full System**

### Terminal 1 – Start LiveKit

```bash
./livekit-server --dev
```

### Terminal 2 – Start Backend Agent

```bash
cd backend
.venv\Scripts\Activate.ps1
python src/agent.py dev
```

### Terminal 3 – Start Frontend

```bash
cd frontend
pnpm dev
```

Open your browser: 👉 **[http://localhost:3000](http://localhost:3000)**
Your Coffee Shop Barista Agent is now live! ☕🤖

---

## 📅 **Challenge Progress**

| Day      | Status         |
| -------- | -------------- |
| Day 1    | ✔️ Completed   |
| Day 2    | ✔️ Completed   |
| Day 3-10 | 🔜 Coming soon |

---

## 📚 **Useful Resources**

* [Murf Falcon TTS Docs](https://docs.murf.ai)
* [LiveKit Agents Documentation](https://docs.livekit.io/agents/)
* [Gemini API Docs](https://developers.google.com/gemini)
* [Deepgram API Docs](https://developers.deepgram.com/)
* [Next.js 15 Docs](https://nextjs.org/docs)

---

## 🛠️ **Tech Stack**

* **Backend**: Python, LiveKit Agents, Murf Falcon TTS, Deepgram STT, Google Gemini
* **Frontend**: Next.js 15, React 19, Tailwind CSS
* **Real-time Layer**: LiveKit Server
* **Package Managers**: uv (Python), pnpm (Node.js)

---

## 🎉 **Final Note**

Day 2 is officially complete — the Coffee Shop Barista Agent **“Brew”** is fully functional with voice interaction, order management, and live beverage visualization.
Stay tuned for Day 3! 🚀

```



kar du ye bhi?
```
