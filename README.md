# AI4Aging Workshop Website

Static GitHub Pages website for a proposed NeurIPS 2026 workshop: **Foundation Models and Generative AI for Longevity Science**.

**Live URL (after setup):** https://ai4longevity.github.io

## Edit content

- Public site: `index.html` (lean pre-proposal page)
- Proposal drafts: `PROPOSAL_NOTES.md` (schedule, topics, checklist—organizers only)
- Styling: `assets/styles.css`

## Publish at `https://ai4longevity.github.io`

GitHub only serves a site at `https://<name>.github.io` when the repo is named **exactly** `<name>.github.io` and files sit at the repo root.

### Step 1 — Create the GitHub organization

1. Go to [Create a new organization](https://github.com/organizations/plan).
2. Choose the free plan.
3. Organization account name: **`ai4longevity`** (must match the URL you want).

### Step 2 — Create the Pages repository

1. In the **ai4longevity** org, click **New repository**.
2. Repository name: **`ai4longevity.github.io`** (exact spelling).
3. Public repo, no README/license (this repo already has the files).
4. Create the repository.

### Step 3 — Push this project to that repo

From this folder:

```bash
git remote add pages https://github.com/ai4longevity/ai4longevity.github.io.git
git push -u pages main
```

If `pages` already exists, use `git remote set-url pages https://github.com/ai4longevity/ai4longevity.github.io.git` instead.

### Step 4 — Enable GitHub Pages

1. Open **ai4longevity/ai4longevity.github.io** → **Settings** → **Pages**.
2. **Source:** Deploy from a branch.
3. **Branch:** `main`, folder **`/ (root)`**.
4. Save. The site is usually live within 1–2 minutes at https://ai4longevity.github.io.

### Optional — mirror on your personal repo

You can keep [akramb8i/ai-aging-workshop](https://github.com/akramb8i/ai-aging-workshop) as a backup; it would publish at `https://akramb8i.github.io/ai-aging-workshop/` if Pages is enabled there (project site URL, not the short custom name).

## Suggested edits before sharing publicly

- Replace placeholder speakers with confirmed names.
- Replace placeholder organizers with confirmed bios and headshots.
- Update dates after NeurIPS announces workshop details.
- Add OpenReview and reviewer nomination links after acceptance.
