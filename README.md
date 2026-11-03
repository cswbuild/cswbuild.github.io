# Chelse Swoopes — academic website

A minimal, responsive Jekyll + GitHub Pages site inspired by the layout structure of ziweigu.com (not a copy of its source code).

## Publish it

1. Create a **public** repository named `YOUR-GITHUB-USERNAME.github.io` on GitHub.
2. Upload **the contents of this folder**, including hidden `.github/`, to the repository on the `main` branch. The easiest way to preserve `.github/` is to unzip locally and push with Git, or use GitHub Desktop.
3. Open repository **Settings → Pages → Build and deployment → Source: GitHub Actions**.
4. The included workflow builds and deploys on every push. Visit `https://YOUR-GITHUB-USERNAME.github.io/` after deployment completes.
5. Optional custom domain: add a `CNAME` file containing your domain, set domain under Settings → Pages, and update DNS per GitHub's documentation. Set `url` in `_config.yml` to your final site's origin.

## Edit your website

- `_data/profile.yml` — biography, contact and external links. To add a headshot: put the image at `assets/img/headshot.jpg` and uncomment `photo` in profile.yml.
- `_data/publications.yml` — add or reorder papers; optional `paper`, `project`, `video`, `image` fields. An image path example is `/assets/img/chainforge.png`.
- `_data/news.yml` — add news items.
- `assets/docs/Chelse_Swoopes_CV.pdf` — replace with updated CV, preserving the filename.
- `assets/css/style.css` — visual design.

## Local preview (optional)

Install Ruby and Bundler, then run `bundle install` and `bundle exec jekyll serve` and open `http://localhost:4000`.

## Editorial checks before publishing

- Verify the descriptions of 2026 CS&Law accepted works, especially the precise status of the paper titled "Judges are Vulnerable to AI Influence; Interface Design Can Help".
- The three recent news years are sourced from the CV; edit to month/year if preferred.
- Confirm all publication author spellings, including Nielsen/Nielson variants in the CV.
- Link missing older papers and add optional publication thumbnails.
- Google Scholar could not be fetched directly due to rate limiting, so publication metadata comes primarily from the supplied CV, with a few public links independently checked.
