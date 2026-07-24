# ExamArch: AI-Powered Exam Platform

ExamArch is a high-performance, secure, and AI-driven platform designed for Indian competitive exams like NEET, JEE Mains, and JEE Advanced. It features advanced proctoring, AI question generation, and neural learning algorithms.

## 📖 Technical Blueprint
For a comprehensive breakdown of the architecture, AI algorithms, visual standards, and current systemic problems, refer to:
**[docs/SYSTEM_BLUEPRINT.md](./docs/SYSTEM_BLUEPRINT.md)**

## 🚀 Key Features
- **AI Test Generation**: Leverages Google Gemini (via Genkit) to generate unique, syllabus-aligned practice tests.
- **Secure Proctoring**: Real-time monitoring with tab-switch detection and live heartbeat signal.
- **Neural Learning**: Integrated IRT (Ability Tracking) and FSRS (Memory Scheduling).
- **Teachers Studio**: Command center for batch coordination and live student monitoring.
- **Quantum Blueprint Theme**: High-fidelity industrial HUD aesthetic.

## 🛠 Tech Stack
- **Framework**: Next.js 15 (App Router)
- **Styling**: Tailwind CSS + ShadCN UI
- **Backend**: Firebase (Auth, Firestore, Hosting, Cloud Functions)
- **AI Engine**: Genkit + Gemini 3 Flash Preview

## 📦 Setup & Installation
1. **Clone & Install**:
   ```bash
   npm install
   ```
2. **Environment**:
   Create a `.env` file with `GEMINI_API_KEY`.
3. **Run Locally**:
   ```bash
   npm run dev
   ```

---
Built with ❤️ for students by the ExamArch Team.
