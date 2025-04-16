# 📌 Yatzy Game - Open Source Portfolio

A Python-based Yatzy game developed as part of the **KOL389COM Open Source Development** module at Coventry University. This project demonstrates use of version control, GitHub Actions, automated testing, and collaboration via GitHub Issues.

---

## 📁 Folder Structure

```
portfolio/
├── worksheet1_version_control/
├── worksheet2_github_actions/
├── worksheet3_github_issues/
└── opensource_essay/
```

Each folder contains:
- Code or config files
- Screenshots (where applicable)
- A markdown report documenting the activity

---

## 🛠 Features

- 5 lockable dice
- Scoring methods: Ones → Yatzy
- Dice roll logic and game mock-up
- Automated unit testing with `unittest`
- GitHub Actions for CI
- GitHub Issues for peer feedback & resolution

---

## 🚀 How to Run the Game

```bash
python game.py
```

- Roll dice up to 3 times
- Lock dice using index input
- Final scores are displayed based on all categories

---

## 🧪 How to Run Tests

Run all unit tests for the scoring logic:

```bash
python -m unittest discover
```

Tests are located in `test_yatzy.py` and include checks for each scoring method.

---

## ⚙️ GitHub Actions

GitHub Actions is configured to:
- Trigger on push/pull to `main`
- Set up Python environment
- Automatically run all tests

Workflow file:
```
.github/workflows/python-app.yml
```

---

## 🐛 GitHub Issues & Fix Workflow

Includes:
- Screenshot of opened issue by peer
- Commit fixing the issue
- Merge screenshot
- Described in `worksheet3_report.md`

---

## 🧠 Essay

A 1500-word essay reflecting on open-source development and its personal relevance is included in:

```
opensource_essay/open_source_reflection.md
```

---

## 👤 Author

**Anurag sah**  
Coventry University  
Final Year – 2025  
Module: KOL389COM Open Source Development

---

## 📄 License / Disclaimer

This coursework is for educational use only.  
Do not publish or distribute beyond the intended submission to Coventry University.

