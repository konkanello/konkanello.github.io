# Konstantinos Kanellopoulos’s Website

This repository is the static source for `https://konkanello.github.io`.
Edit `index.html` for page content and `libs/custom/my_css.css` for styling.
The current site does not require Jekyll or a build step.

## Preview

From this directory:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open `http://127.0.0.1:8765/`. Check the Selected/All publication controls,
education disclosure, light/dark themes, and mobile
layout before publishing. Local edits do not update the live GitHub Pages site
until deployed through its repository.

## CV-based updates

The shared CV at `../materials/cv/cv_redesigned.tex` is the reference for factual
updates. Publications appear in Selected and All; keep shared entries consistent.
Show only accepted or published papers in the publication lists. Omit manuscripts
under submission, including those that already have an arXiv preprint.

Website-specific preferences confirmed on 13 November 2026:

- Leave `assets/cv/cv_kanellok.pdf` unchanged unless explicitly asked to replace it.
- Do not display papers under submission.
- Do not add mentoring content.
- Do not add the ETH Doctoral Medal nomination.

Preserve the existing visual design, research introduction, and personal content
when making factual updates. Some older publication titles on the website use
full paper titles where the CV uses shortened wording.

## External Libraries
- Framework: [Jekyll](http://jekyllrb.com/)
- CSS
  - [Skeleton](getskeleton.com)
  - Tabs: [Skeleton Tabs](https://github.com/nathancahill/skeleton-tabs)
  - Experience: [Timeline](https://codepen.io/NilsWe/pen/FemfK)
  - Icons: [Font Awesome](http://fontawesome.io/)
- JS
  - [Jquery (3.1.1)](https://jquery.com/)
