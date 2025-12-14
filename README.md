# GitGrade – GitHub Repository Analyzer

GitGrade is a simple web-based tool that analyzes a public GitHub repository and
generates a score, summary, and personalized improvement roadmap for students.

---

## 📌 Problem Statement
Students often create GitHub projects but don’t know how good their code looks
to recruiters or mentors. This project acts as a mirror that reflects the real
quality of a repository using publicly available GitHub data.

---

## 💡 Solution
GitGrade accepts a GitHub repository URL and evaluates it on multiple basic
dimensions such as description, commit activity, language usage, and overall
project readiness.

---

## ⚙️ Features
- Accepts any public GitHub repository URL
- Fetches repository data using GitHub REST API
- Generates:
  - Score (out of 100)
  - Written summary
  - Personalized improvement roadmap

---

## 🛠️ Tech Stack
- HTML
- JavaScript
- GitHub REST API

---

## 🔄 How It Works
1. User pastes a GitHub repository link
2. System fetches repository metadata and commit history
3. Rule-based logic evaluates the repository
4. Output is displayed instantly on the webpage

---

## 🚧 Limitations
- Deep code analysis is not implemented
- Test coverage is not evaluated
- Scoring is rule-based, not AI-driven

---

## 🚀 Future Improvements
- Code quality and complexity analysis
- Test coverage detection
- AI-powered feedback and scoring
- CI/CD integration checks

---

## 👤 Author
Manjeet

