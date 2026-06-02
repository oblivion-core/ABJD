# ⭐ ABJD — Parental Dashboard for AI-Powered Kids Learning

> *"Apprentissage moderne pour vos enfants"*  
> Modern learning for your children — track sessions, results, and progress in one place.

🔗 **Live app:** [abjd-app.vercel.app](https://abjd-app.vercel.app/login)

> ⚠️ This is a private startup project. Source code is not public.

---

| Login & Registration | Dashboard |
|---|---|
| ![Login](https://raw.githubusercontent.com/oblivion-core/ABJD/main/Screenshot%20(1013).png) | ![Dashboard](https://raw.githubusercontent.com/oblivion-core/ABJD/main/Screenshot%20(1014).png) |

| Session Setup | Child Profiles |
|---|---|
| ![Session](https://raw.githubusercontent.com/oblivion-core/ABJD/main/Screenshot%20(1016).png) | ![Kids](https://raw.githubusercontent.com/oblivion-core/ABJD/main/Screenshot%20(1017).png) |

---

## 🧠 What is ABJD?

ABJD is the parent-facing web dashboard that powers the **Voca Demy** Alexa skill ecosystem. Parents and teachers create accounts, add child profiles, upload learning documents (PDF, TXT, DOC), and launch timed sessions — all of which are then consumed live by the Alexa skill to deliver an interactive voice learning experience to the child.

The full learning loop:

```
Parent uploads PDF on ABJD
        ↓
Session created in Supabase
        ↓
Child opens Alexa → Voca Demy skill launches
        ↓
Alexa reads the document aloud in chunks
        ↓
AI-generated quiz based on the document
        ↓
Results & performance report saved → visible to parent on ABJD
```

---

## ✨ Features

- 🔐 **Authentication** — parent account with inscription / connexion
- 💳 **Subscription plans** — Standard (1 000 DA/month) and Premium (2 000 DA/month)
- 📊 **Dashboard** — learning time, completed sessions, global accuracy, league ranking
- 📁 **Session management** — upload documents, select a child, set a timer (5/10/15/20/30 min), launch session
- 👧 **Child profiles** — create and manage multiple child profiles with individual stats
- 📈 **Stats page** — detailed results per file and per session
- ⚙️ **Settings** — account and preference management

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React · Vercel |
| Backend / Database | Supabase (PostgreSQL + Auth + Storage) |
| Voice skill | Voca Demy (Amazon Alexa + Python serverless) |
| AI / LLM | OpenRouter API (quiz generation + performance reports) |
| Hosting | Vercel |

---

## 🔗 Related Project

This dashboard is the companion app to **[Voca Demy](https://github.com/oblivion-core/Voca-demy-)** — an AI-powered Alexa skill that delivers voice-based lessons and quizzes to children using the sessions created here.

---

---

Built by **Bouslah Abdelkrim** · [github.com/oblivion-core](https://github.com/oblivion-core)
