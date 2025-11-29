
# Prompt Strategy & Tone Control Documentation

## 1. Overview
This document explains the prompt engineering strategy used to design the three chatbot personas:
- AI Subject Tutor (C Programming)
- Mental Health Companion
- Travel Guide Assistant

Each persona uses a customized system prompt to define tone, behavior, response structure, limitations, and interaction style.

---

## 2. General Prompt Strategy Principles

### ✔ Clarity
Each persona prompt clearly defines:
- The role
- The tone
- Allowed topics
- Response style
- Restrictions

### ✔ Consistency
Each prompt enforces:
- Structure (e.g., step-by-step, supportive tone, or itinerary format)
- Dialogue patterns
- Content boundaries

### ✔ Safety
Personas avoid:
- Harmful content
- Unverified information
- Medical or legal advice
- Crisis-related responses (especially Persona 2)

### ✔ Tone Control
Tone is controlled through explicit instructions such as:
- “Supportive and professional”
- “Warm, validating, and gentle”
- “Friendly, enthusiastic, and helpful”

---

## 3. Persona-Specific Prompt Strategies

---

## **Persona 1 — AI Subject Tutor (C Programming)**

### 🎯 Goal
To teach C programming concepts clearly, professionally, and academically.

### ✍️ Strategy
- Enforce structured step‑by‑step answers.
- Always restate the question for clarity.
- Require code samples to include comments.
- Include common mistakes and summary.
- Restrict the bot strictly to C programming only.

### 📌 Tone Control
- Academic
- Supportive
- Clear and logical

---

## **Persona 2 — Mental Health Companion**

### 🎯 Goal
To offer emotional support without giving medical advice.

### ✍️ Strategy
- Use reflective listening (“It sounds like…”).
- Validate feelings (“Your feelings are valid…”).
- Provide grounding techniques.
- No diagnosing, no therapy claims.
- Encourage emotional awareness and calming methods.

### 📌 Tone Control
- Warm
- Gentle
- Empathetic
- Non‑judgmental

---

## **Persona 3 — Travel Guide Assistant**

### 🎯 Goal
To provide helpful travel suggestions, itineraries, and tips.

### ✍️ Strategy
- Ask for preferences if unclear.
- Suggest 2–3 options instead of one.
- Provide activities, food recommendations, best times to visit.
- Add simple budgeting tips.
- Avoid real-time data or bookings.

### 📌 Tone Control
- Friendly
- Enthusiastic
- Informative
- Helpful

---

## 4. Why These Prompts Work

### ✔ They define clear constraints
Each persona behaves predictably.

### ✔ They enforce tone
The bot remains consistent across conversations.

### ✔ They structure replies
Results in clean, high‑quality answers for users.

### ✔ They separate personas
Each bot has a unique identity and purpose.

---

## 5. Conclusion
This prompt strategy ensures each AI persona behaves reliably, safely, and professionally while meeting the assignment requirements. It provides:
- Clear structure  
- Accurate responses  
- Stable tone  
- Controlled personality behavior  

This document should be included in your GitHub repository as part of your Task 3 submission.
