# AI Training — Day 1 Practice (Chamber of Accounts, Kyrgyz Republic)

Browser-based Jupyter (JupyterLite) — **no accounts, no installs**. Python runs
inside each participant's browser. Three notebooks (Kyrgyz, English terms in
brackets): risk classification, confusion matrix and metrics, regression.

## Deploy (once, ~10 minutes)

1. Create a new GitHub repository (public) and push these files to the `main` branch.
2. In the repo: **Settings → Pages → Source: "GitHub Actions"**.
3. Wait for the "Build and Deploy JupyterLite" action to finish (green check).

Participant URL: `https://<YOUR-USERNAME>.github.io/<REPO-NAME>/lab/index.html`
Make a QR code from that URL (any QR generator) and put it on slide 45
("Ноутбугуңузда ачыңыз") of the deck.

## Before the training day

- Test the URL on the venue Wi-Fi with 2–3 laptops simultaneously. First page
  load downloads ~40 MB (then cached); the `%pip install` cell takes 30–60 s.
- Supported browsers: recent Chrome, Edge, Firefox. Safari mostly works.
- Participants' work is saved in their own browser (survives refresh, not
  laptop swaps).

## If the internet fails

Present from the pre-executed HTML copies of all three notebooks (shipped
alongside this repo) — every output and chart is already rendered.

## Edit the notebooks

Edit files in `content/`, commit, push — the site redeploys automatically.
