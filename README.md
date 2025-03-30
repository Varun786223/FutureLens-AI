
# FutureLens: AI-Predicted Life Simulator

*Predict your future with AI.* FutureLens is a web platform that takes your current life details—age, career, goals—and generates an interactive timeline of your predicted life path over 5, 10, or 20 years. Built with React Native, Fastify, and AI/ML, it’s a showcase of modern web development and data science.

---

## What It Does
FutureLens simulates your future based on what you input today. Enter your job, education, and ambitions, and watch AI craft a personalized timeline of milestones—like promotions, relocations, or achievements. Tweak variables to explore "what if" scenarios and get actionable insights.

---

## Features
- *Life Input Form*: Add age, job, industry, education, and 1-3 goals (e.g., "Become a manager").
- *Future Timeline*: Scrollable, interactive display of predicted milestones with details on hover.
- *What-If Tweaks*: Adjust inputs (e.g., "Add a degree") to see alternate futures in real-time.
- *Insights Panel*: AI-driven tips and probabilities (e.g., "80% chance of a raise by 2030").
- *Share Option*: Export your timeline or share it directly to LinkedIn.

---

## Tech Stack
- *Frontend*: React Native (UI), D3.js (visuals), Tailwind CSS (styling).
- *Backend*: Fastify (API), Neo4j (graph database for life events).
- *AI/ML*: 
  - XGBoost (numerical predictions like income).
  - Hugging Face NLP (goal parsing, e.g., "Start a business").
  - Trained on open career and census data.

---

## How It Works
1. Input your details in a quick form.
2. AI processes data—XGBoost for stats, NLP for goals.
3. See your future on an animated timeline.
4. Tweak variables and share your results.


---

## Why I Built It
FutureLens blends AI, fullstack dev, and frontend design into a tool that’s both fun and useful. It’s my take on where tech can take us—perfect for LinkedIn’s career-focused crowd.

---

## Future Plans
- Add user accounts to save predictions.
- Integrate real-time career data from LinkedIn/X.
- Expand AI with deeper scenario analysis.

---

