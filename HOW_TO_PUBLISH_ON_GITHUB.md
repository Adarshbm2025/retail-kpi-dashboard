# How to put this project on GitHub (step by step)

> Delete this file before your final commit if you don't want it in your repo. It's a guide for you, not part of the project.

## 0. The work
`notebooks/kpi_dashboard.ipynb` is complete and has been run, so its outputs and charts will show on GitHub.
Read through it and make sure you can explain every step. Interviewers will ask about it.
To practise, redo it from scratch in `notebooks/kpi_dashboard_exercises.ipynb`.
Rewriting the Step 10 insights in your own words is the best way to make the project yours.

## 1. One-time Git setup (on your Mac)
Tell Git who you are (use the same email as your GitHub account):
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

## 2. Create an empty repository on GitHub
1. Go to https://github.com/new
2. Repository name: `retail-kpi-dashboard`
3. Description: *KPI dashboard for retail sales data with Python & Pandas*
4. **Public**. Do **not** tick "Add a README" (we already have one).
5. Click **Create repository**.

## 3. Turn this folder into a Git repo and push it
Run these in a terminal, from inside the `retail-kpi-dashboard` folder:
```bash
git init
git add .
git commit -m "KPI dashboard for retail sales with Pandas"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/retail-kpi-dashboard.git
git push -u origin main
```
When it asks for a password, GitHub needs a **Personal Access Token**, not your account password:
GitHub → Settings → Developer settings → Personal access tokens → *Tokens (classic)* → Generate, with the `repo` scope ticked.
(Or install **GitHub Desktop**, which handles login for you.)

## 4. Make it look good
- On the repo page, click ⚙️ next to **About** and add topics: `python`, `pandas`, `data-analysis`, `kpi`, `dashboard`, `matplotlib`.
- Pin the repo on your GitHub profile (Profile → *Customize your pins*).

## 5. Each time you change something later
```bash
git add .
git commit -m "Describe what you changed"
git push
```

## About credit
The README's **Credits** section links the original lesson by Mathew K Analytics and the dataset source.
Keep it there. Saying where you learned something is normal and honest, and interviewers respect it.
What makes the project *yours* is the different dataset, your own insights, and any stretch goals you add.
