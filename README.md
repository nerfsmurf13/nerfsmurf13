# 🚀 Edward Williams — Full-Stack Developer & AI Engineer | Dallas, TX

**"I professionally bend JavaScript, Vue.js, and LLMs to my will."**

Based in **Dallas, TX**, I am an engineer focused on building intelligent, automated systems. Whether it's architecting **RAG systems for aviation** or building **AI-powered SaaS platforms** for small businesses, I specialize in bridging the gap between complex backend logic and high-performance frontends.

### 🔗 Connect with me:

| Platform | Link |
| --- | --- |
| **Portfolio** | [edwardwilliams.me](https://edwardwilliams.me) |
| **LinkedIn** | [linkedin.com/in/edwardalexanderwilliams](https://linkedin.com/in/edwardalexanderwilliams) |
| **Email** | [edward.williams91@gmail.com](mailto:edward.williams91@gmail.com) |
| **YouTube** | [@JustEdWilliams](https://www.youtube.com/channel/UChCmp3gZe35BSTEHcJRDHog) |

---

### 🛠️ The Stack

```javascript
const edwardWilliams = {
  frontend: ["Vue 3 (Composition API)", "Tailwind CSS 4", "Pinia", "Vite 6", "Capacitor 7"],
  backend:  ["Node.js", "Express.js", "Socket.IO", "Bull Queue (Redis)"],
  ai_ml:    ["Claude SDK (tool_use)", "GPT-5 (Function Calling)", "Gemini Pro (Vision)", "Pinecone (Vector DB)"],
  database: ["MongoDB (Mongoose 8)", "Firebase", "GCS"],
  services: ["Stripe (Subscriptions)", "Twilio", "Steam Web API", "Zod Validation"]
};

```

---

### 📂 Flagship Projects

#### 1. ✈️ [PropPal](https://useproppal.com) | AI-Powered Aviation Maintenance

*Safety-critical RAG system for aircraft owners and mechanics.*

* **Engineering Highlight:** Built a **Dual-Mode AI Pipeline** using **Pinecone** for rapid text retrieval and **Gemini Pro Vision** for analyzing complex maintenance schematics.
* **Compliance Engine:** Implemented a logic layer to validate answers against **CFR 43.3**, restricting pilot users to "Preventive Maintenance" instructions per FAA regulations.
* **Infrastructure:** Uses a **Bull/Redis** async job queue to handle long-running PDF vectorization without blocking the UI.

#### 2. 📉 [Define Your Dollars](https://defineyourdollars.com) | AI Financial SaaS

*Personal finance platform with AI-driven bank statement analysis.*

* **Engineering Highlight:** Developed a **hybrid AI + rule-based pipeline** where Claude categorizes the first 100 rows to seed pattern-matching rules for the remainder, reducing latency by **80%**.
* **Key Feature:** Cross-statement reconciliation that detects transfers between checking and credit accounts using fuzzy merchant normalization.

#### 3. 🏗️ [Frisco Web Designs](https://friscowebdesigns.com) | AI Agency Platform

*A multi-tenant SaaS for automated web design and lead generation.*

* **Engineering Highlight:** Implemented a **Circuit Breaker pattern** for AI providers (Claude/GPT-5/Gemini) with graceful fallbacks and a Zod-validated structured JSON mockup engine.
* **Key Feature:** Real-time AI mockup generator that produces a full design system and conversion-optimized content from a single business prompt.

#### 4. ⚔️ [OriginSmith](https://originsmith.netlify.app) | Gaming Tools & AI Storytelling

*AI character generator and Project Zomboid mod management suite.*

* **Engineering Highlight:** Developed a **multi-pass Mod ID parser** for Steam Workshop data and a compatibility engine for Kenshi that validates 5+ complex constraint rules per generation.
* **Key Feature:** Interactive AI backstories with custom annotation markers for real-time keyword highlighting.

---

### 📈 Engineering Metrics

* **AI Reliability:** Achieved zero parsing failures in production using **Zod** for runtime schema validation of LLM outputs.
* **Performance:** Optimized Core Web Vitals (INP) via a 30-second auth cache on admin validation layers.
* **Scale:** Managing 25+ REST endpoints and 20+ database models across multiple live SaaS products.

---

### 📊 Vital Signs

* **Currently Learning:** Advanced RAG Orchestration & Nuxt 3.
* **Interests:** Volkswagen (Mk7 GTI) 🏎️, Aviation ✈️, Kenshi ⚔️.
* **Fun Fact:** My character generator has a 50-retry validation loop to ensure your Kenshi character doesn't break the lore.

---

### 📦 Legacy / Archived Work

* **Word-2-Element:** Periodic table converter (Vanilla JS).
* **Kenshi Roll:** The original Kenshi randomizer (Pre-AI).
* **SpaceX API Demo:** Vue-based launch tracker.
* **Cost of Duty:** Player data resource calculator (Archived).
