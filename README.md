# SHiP student onboarding pages

Markdown source for a small onboarding site for new students joining SHiP and CERN.

## Edit the site

- Site configuration and navigation: `zensical.toml`
- Page content: `docs/`
- Local build, if Zensical is installed:

```bash
python3.14 -m pip install zensical
zensical build
```

The GitHub Pages workflow installs Zensical, builds the site into `site/`, and deploys it.
