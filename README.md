
<p align="center">
  <img src="Saikou.tech-logo-flat-hor.svg" alt="Saikou Tech Logo" width="280">
</p>

<h1 align="center">M O D E L 1 0  —  A U D I T  E N G I N E</h1>

> **The AI that refuses to guess.**
> Saikou Tech enforces absolute technical integrity. Model10 guarantees a 10/10 verified AI response, or provides a precise diagnostic roadmap to achieve it.

---

## 🛡️ The Saikou Standard Architecture
Standard AI models rely on probability; Model10 relies on verification. Every request passes through our proprietary 3-layer architecture before output is released:

1. **AST Validator (Layer 01):** Structural inspection. Parses generated code into an Abstract Syntax Tree to intercept logical failures at the architectural level.
2. **ASC Engine (Layer 02):** Adversarial Self-Critique (Saikou Logic). An internal adversarial process attacks the response for factual errors or contradictions.
3. **Zero-Guessing Gateway (Layer 03):** The final determinism lock. If absolute certainty (10/10 SQI) is not reached, the output is intercepted and converted into a Diagnostic Roadmap.

---

## 💎 Sovereign AI: Bring Your Own Key (BYOK)
Saikou Tech is a **Pure Logic Provider**. We do not retain your data, and we do not charge for token consumption. **All endpoints require you to provide your own Google Gemini API Key.** You pay us for the Saikou Audit Logic; you pay Google directly for the compute. Zero data retention, zero cost overhead.

---

## ⚙️ Requirements & Installation

This API is built for speed, reliability, and concurrency using FastAPI and the modern `google-genai` SDK to prevent race conditions.

### 1. Install dependencies
Ensure you have Python 3.9+ installed.
```bash
pip install fastapi uvicorn google-genai pydantic

2. Environment Variables (Server-side)
If hosting your own instance (e.g., on Render), set the following variables:
 * RAPIDAPI_SECRET: Required to verify active developer subscriptions for the paid endpoints.
3. Run the Server
uvicorn main:app --host 0.0.0.0 --port 8000

📡 Endpoints (The Tiers)
 * POST /model10/audit/free
   * Auth: Requires x-gemini-api-key header.
   * Limit: 1.500 characters.
   * Use Case: Lead generation, quick verification, and Poe interface.
 * POST /model10/audit/rapidapi
   * Auth: Requires x-gemini-api-key AND x-rapidapi-secret header.
   * Limit: 50.000 characters.
   * Use Case: Developers & Startups (Active Saikou subscription required).
 * POST /model10/audit/enterprise
   * Auth: Bring Your Own Key (BYOK) on a Private Instance.
   * Limit: Unlimited.
   * Use Case: Data Sovereignty, heavy compliance, isolated infrastructure.

© 2026 Saikou Tech. All rights reserved. Non-Hallucination Zone.

