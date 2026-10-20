# Mohammed Majeed J

**Full Stack Developer — Python · React · Applied AI**

I build systems that other people have to use. The largest of them is
[Periyar University's PhD Admission Management System][phd] — four role-based
portals over one MySQL database — which runs in production for the university's
research admissions.

Currently completing an MCA at Periyar University, Salem. **Open to full-time
roles and internships** in backend, full stack and applied AI.

[Portfolio](https://mohammedmajeedportfolio.me) ·
[LinkedIn](https://www.linkedin.com/in/majeed74905) ·
[Email](mailto:majeed74905@gmail.com)

---

## What I have shipped

### [PhD Admission Management System][phd] — in production
Periyar University's research admission workflow, digitised end to end.

- Four separate portals — student, administrator, supervisor and research
  centre — sharing a single MySQL database
- JWT authentication with per-module signing secrets, Argon2 password hashing,
  Redis-backed rate limiting
- Versioned SQL migrations covering the admission workflow, eligibility rules
  and payment handling
- Queued transactional email through a dedicated NestJS + BullMQ service
- Document uploads, generated PDFs, Excel exports and QR codes
- Containerised with Docker Compose behind an Nginx reverse proxy

`React 19` `Vite` `Node.js` `Express` `NestJS` `Prisma` `MySQL` `Redis` `BullMQ` `Docker` `Nginx`

### [Zara AI Platform](https://zara-ai-assists.netlify.app/) — live
An AI assistant with an in-browser code workspace.

- Two model providers, Google Gemini and Groq, behind one shared model manager
- Code workspace built on Monaco Editor and CodeSandbox Sandpack
- Chat, voice, live-session and image modes, plus exam prep and flashcards
- Google OAuth with IndexedDB persistence for offline use

`React 18` `TypeScript` `Tailwind CSS` `Google Gemini` `Groq` `Monaco` `Sandpack`

### [Diabetes Prediction](https://diabetic-prediction-y2qs.onrender.com/) — live
A machine-learning classifier served over the web.

- Logistic Regression trained with scikit-learn on eight clinical inputs
- StandardScaler feature scaling; model and scaler persisted with joblib
- Separate preprocessing, training and prediction modules, plus an EDA notebook
- Deployed on Render under Gunicorn with a health-check endpoint

`Python` `Flask` `scikit-learn` `pandas` `NumPy` `Gunicorn` `Render`

---

## Tech

**Languages** Python · JavaScript · TypeScript · PHP · SQL

**Frontend** React · Vite · Tailwind CSS · Bootstrap · Three.js

**Backend** FastAPI · Node.js · Express · NestJS · Flask

**Data** PostgreSQL · MySQL · Prisma · SQLAlchemy · Redis

**AI/ML** Google Gemini · Groq · OpenAI · Anthropic Claude · scikit-learn · pandas

**Cloud & DevOps** AWS · Docker · Nginx · Vercel · Render · Netlify

**Security** JWT & session auth · Argon2 · TOTP 2FA · CSRF tokens · rate limiting · CSP

---

## How I work

Get the data model right first, then make the interface honest about it. The
same habit shows up in every project here: versioned migrations rather than
hand-edited schemas, real authentication rather than a token in localStorage,
and a service that refuses to start on a bad configuration rather than failing
quietly three hours later.

---

<!-- These are rendered live by GitHub. Nothing is hard-coded, so they stay
     accurate on their own. -->
![GitHub stats](https://github-readme-stats.vercel.app/api?username=majeed74905&show_icons=true&hide_border=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=majeed74905&layout=compact&hide_border=true)

---

📫 **majeed74905@gmail.com** · Salem, Tamil Nadu, India

[phd]: http://research.periyaruniversity.ac.in/rnd-app/student-app/
