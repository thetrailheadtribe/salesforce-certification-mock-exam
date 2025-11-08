# Salesforce Certification Mock Exam Framework

A lightweight, Salesforce‑inspired exam simulator built with pure **HTML, CSS, and JavaScript**.  
This framework replicates the look and feel of Salesforce certification exams, allowing trainers and learners to practice in a realistic environment.

---

## ✨ Features
- **Single & Multi‑select questions** with one question per page
- **Navigation controls**: Next/Previous buttons
- **Timer with alerts**:
  - Auto‑submit when time runs out
  - Last 5 minutes highlighted in red
  - Last 30 seconds animated bounce alert
- **Pause/Resume timer** for flexible practice
- **Randomization**: Questions and options shuffle each attempt
- **Progress tracking**: Visual progress bar + “Question X of Y” counter
- **Immediate scoring** with a full review page showing correct answers (green) and wrong selections (red)

---

## 📂 Project Structure
salesforce-certification-mock-exam-framework/
- **index.html** # Main exam page 
- **style.css** # Styling (Salesforce-inspired UI) 
- **app.js** # Core exam logic 
- **questions.json** # Question bank (customizable) 
- **README.md** # Documentation

## 🚀 Getting Started

### Option 1: Run locally
1. Download or clone this repo.
2. Open `index.html` in your browser (Chrome/Edge/Firefox).
   - If your browser blocks local JSON fetch, use a local server (e.g., VS Code Live Server).

### Option 2: Host online (recommended)
1. Create a GitHub account.
2. Make a new repo: `salesforce-certification-mock-exam-framework`.
3. Upload these files (`index.html`, `style.css`, `app.js`, `questions.json`, `README.md`).
4. Go to **Settings > Pages > Source = main branch (root)** > Save.
5. Your live app will be available at:  
   `https://<your-username>.github.io/salesforce-certification-mock-exam-framework`

---

## 🧑‍💻 Customizing Questions
Open `questions.json` and add your own questions:

```json
{
  "id": 1,
  "question": "Which features can automate business processes in Salesforce?",
  "options": [
    "Workflow Rules",
    "Reports",
    "Dashboards",
    "Flows"
  ],
  "answer": [0, 3],
  "type": "multi"
}
