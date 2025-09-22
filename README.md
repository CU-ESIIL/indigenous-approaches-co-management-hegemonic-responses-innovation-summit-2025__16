# Indigenous Approaches to Co-Management — Hegemonic Responses (Innovation Summit 2025 Group 16)

This repository hosts the public website and shared resources for Innovation Summit 2025 Group 16. Use it to publish your in-progress findings, track updates, and keep the team aligned around shared code and documentation.

If you generated this project from the Innovation Summit template, the quick customization checklist lives in [TEMPLATE_GUIDE.md](TEMPLATE_GUIDE.md).

---

## 1) Understanding the repository

Think of this repository like a shared project drive. The most important folders are:

- **`code/`** — Python, R, and notebook files that back up your analysis. Keep filenames descriptive and include short header comments so teammates understand the intent.
- **`docs/`** — Every Markdown file in this folder appears on the public site at <https://cu-esiil.github.io/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/>.
- **`documentation/`** — Internal notes that do not need to be published. Summarize key insights on the public pages so visitors see the latest story.
- **`docs/assets/`** — Images, GIFs, and downloadable artifacts referenced across the site.

> Tip: Commit early and often. Small changes are easy to review and keep the site fresh.

---

## 2) How to update the website

The homepage and supporting pages live inside `docs/`. Every commit to `main` triggers the MkDocs GitHub Action that rebuilds the site.

1. Open the `docs/` folder and choose a page (for example `index.md`).
2. Click the pencil icon (✏️) to edit directly in the browser.
3. Make your changes, then write a short commit message like `Add Day 1 questions`.
4. Commit to `main`. The **Deploy site (MkDocs)** workflow publishes the update within a couple of minutes.

If Pages is not yet enabled, visit **Settings → Pages**, choose **GitHub Actions** as the source, and run the deployment workflow once.

---

## 3) How to share code

Store all reusable scripts, notebooks, and utilities in the `code/` directory.

1. From the repository home page, open **code/**.
2. Use **Add file → Upload files** to add an existing script, or **Create new file** for quick prototypes.
3. Include a short comment block explaining inputs, outputs, and dependencies.
4. Commit your changes. Reference important files from `docs/code.md` or the homepage so others can find them quickly.

Large datasets should live in your CyVerse Group 16 folder. Link to them from `docs/data.md` instead of committing bulky files to Git.

---

## 4) Quick links for teammates

- **Public site:** <https://cu-esiil.github.io/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16/>
- **GitHub repository:** <https://github.com/CU-ESIIL/indigenous-approaches-co-management-hegemonic-responses-innovation-summit-2025__16>
- **CyVerse storage:** `i:/iplant/home/shared/esiil/Innovation_summit/Group_16`

Share these links in Slack or email threads so everyone lands in the right place.

---

## 5) First tasks for new contributors

- [ ] Update `docs/index.md` with today’s status, visuals, and key decisions.
- [ ] Add yourself to the team table on the homepage.
- [ ] Upload your first notebook or script to `code/`.
- [ ] Post an entry in `docs/updates.md` summarizing what changed.

Once those steps are complete, your project page will read like a live, visual notebook for the summit.

---

## Need more help?

- Browse the day-by-day guides under **Instructions** in the site navigation.
- Review the MkDocs configuration in `mkdocs.yml` if you need to add new pages to the nav.
- Reach out in the `#innovation-summit-group-16` Slack channel or email the project point of contact if you are stuck.

Happy collaborating!
