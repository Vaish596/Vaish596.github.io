# Vaishnavi Shirbhate — Academic Portfolio

Personal portfolio website for **Vaishnavi Shirbhate** (Machine Learning / Computer Vision), hosted with GitHub Pages at [vaish596.github.io](https://vaish596.github.io).

Built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (forked from Minimal Mistakes).

## Content

- **Home** (`_pages/about.md`) — bio, education, technical skills
- **Portfolio** (`_portfolio/`) — research projects:
  - AI-Driven Image Restoration for RSOM Skin Disease Diagnostics (Master Thesis, DKFZ)
  - Sign Language Image Generation (Master Project, RPTU)
  - LLM Fine-tuning for Code Generation (RPTU)
  - Camera-LiDAR Fusion for 3D Object Detection (RPTU)
- **Talks** (`_talks/`) — seminar presentation
- **Teaching** (`_teaching/`) — course tutoring experience
- **CV** (`_pages/cv.md`) — full CV, plus resume PDFs in `files/`

## Local development

```bash
gem install bundler jekyll
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open http://localhost:4000.

## Updating

Edit the Markdown/YAML files and push to the `main` branch — GitHub Pages rebuilds the site automatically.

- Site-wide settings: `_config.yml` (author info, links, repository)
- Navigation menu: `_data/navigation.yml`

## License

The template is MIT licensed (see `LICENSE`).