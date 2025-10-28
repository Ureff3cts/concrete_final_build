# TJ's Asphalt and Concrete Repair — Static Site

Quick notes to deploy from GitHub:

- Put this repo on GitHub.
- Ensure `index.html` is at the repository root (it already is).
- The included GitHub Actions workflow `.github/workflows/deploy.yml` will run on pushes to `main` and publish the repo root to GitHub Pages via the official Pages actions.
- If your repository is a project page (username.github.io/REPO_NAME), update the `<base href="./">` in `index.html` to `<base href="/REPO_NAME/">`.
- For a custom domain, add a `CNAME` file in the repo root with your domain; GitHub Pages will use it.
- If your default branch is not `main`, either rename it to `main` or update `deploy.yml` to use your default branch.

That's it — push to `main` and check the repository's Pages settings (Settings → Pages) to confirm the site URL.
