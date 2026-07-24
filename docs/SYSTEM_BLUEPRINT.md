# ExamArch Ecosystem v5.6: Technical Blueprint & Strategic Memory

## 🛰️ Platform Mission
ExamArch is an industrial-grade, AI-driven assessment ecosystem specifically architected for high-stakes Indian competitive exams (NEET, JEE Mains, JEE Advanced). The platform focuses on three primary objectives: precision student ability measurement, memory optimization through spaced repetition, and secure, proctored assessment delivery.

## 🛠️ Core Features
1. **AI Synthesis 3.1**: Generates hyper-realistic, syllabus-aligned questions using Genkit and Gemini 3 Flash Preview.
2. **IRT 3PL Engine**: Implements Item Response Theory to track latent student ability ($\theta$) and predict national rankings.
3. **FSRS 4.5 Scheduler**: Implements Spaced Repetition (Difficulty, Stability, Retrievability) to manage conceptual decay.
4. **Socratic Agent v4.0**: A persistent AI tutor with "Continuity Memory" that acknowledges past student struggles.
5. **Zero-Trust Silo Model**: Strictly isolates private practice data from proctored assessment signals.
6. **Live Signal Proctoring**: Real-time heartbeat monitoring, tab-switch detection, and hardware-accelerated webcam feeds.
7. **Quantum Blueprint HUD**: A laboratory-grade "Super Cyan" interface with technical grid overlays.

## ⚠️ Known Downsides & Trade-offs
- **Cold Start Latency**: Relying on serverless Cloud Functions can introduce initial latency for the Scoring Engine.
- **Client-Side Heavy**: Most neural logic executes on the client to reduce costs, making it dependent on the student's device performance.
- **Token Sensitivity**: Advanced Socratic exchanges are token-intensive; the system relies on an Ad-driven "Sustain" model for credits.
- **LLM Accuracy**: While high, scientific notation ($\LaTeX$) can occasionally suffer from serialization corruption, requiring the `LatexRenderer` buffer.

## 🧠 Technical Logic Reference
### 1. Ability Tracking (IRT)
- **Theta ($\theta$)**: Ranges from -4 to +4. 
- **Fluency Logic**: Correct answers in <15s provide a 40% boost to the master signal.
- **Velocity Flagging**: 2+ consecutive answers in <5s triggers an "Intelligent Guess" warning.

### 2. Spaced Repetition (FSRS)
- **DSR Model**: Tracks individual chapter stability. 
- **Drill Trigger**: Recall sessions are automatically suggested when retrievability ($R$) drops below 85%.

### 3. Socratic Protocol
- **Sequence**: Diagnose → Probe (Foundational) → Scaffold (Hint) → Reveal (Solution) → Consolidate (New Challenge).

### 4. Visual Identity
- **Aura Engine**: Conic-gradient fusion of **Electric Cyan** (#00ffff) and **Gold**.
- **Orbit Loader**: Particle and wedge-trail share a singular radial axis at 50% radius for perfect synchronization.

---
**Status**: Synchronized // **Signal**: Active // **Protocol**: Secure Silo v5.6
