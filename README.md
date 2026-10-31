# Dong Sub (Dave) Kim — Resume & Portfolio

Public resume at [dongsubkim.github.io](https://dongsubkim.github.io), built with Jekyll and the modern-resume-theme. Content refreshed from the October 31, 2026 career package.

## Update the content

Edit `_config.yml` to update the profile, highlights, experience, five project case studies, MOGUM, AI-assisted engineering, skills, and education. The content source is `resume-package/40-web-portfolio/portfolio-web-EN.md` in the private career-package repository. Keep customer names and internal code names generalized. Publish verified results and distinguish implemented work from production rollouts; the chat API gateway is in QA as of October 2026.

Replace `resume.pdf` with the latest `resume-package/20-general-resume/resume-general-EN.pdf` when updating the downloadable resume. The header links to this file.

Only publication-ready content belongs in this repository. Work logs, raw exports, supporting evidence, and resume drafts are maintained in a separate private repository.

Project case studies use native `<details>` elements, so readers can expand the problem, constraints, decisions, results, and technology while scanning the main results. About, Highlights, and Experience link directly to the five project anchors.

## Run locally

1. Install Ruby 3.1.7 with rbenv.
2. Run `bundle install`.
3. Run `bundle exec jekyll serve`.
4. Open `http://localhost:4000`.

Run `bundle exec jekyll build` to verify the production output. GitHub Pages publishes the root of the `master` branch.
