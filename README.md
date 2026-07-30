# vinib

Technical writing, docs engineering, and web3 portfolio by **Vini Barbosa**.

This repository is the source of a static site built with [mdBook](https://rust-lang.github.io/mdBook/).

**Live site** (once deployed): `https://vinib.github.io/`

## Local development

```bash
# Install mdBook (if needed)
cargo install mdbook

# Optional but recommended
cargo install mdbook-mermaid
# mdbook-mermaid install   # once

# Serve with live reload
mdbook serve --open

# Build
mdbook build
```

## Structure

```text
src/
├── SUMMARY.md              # Table of contents
├── introduction/           # Welcome
├── about.md
├── building-this-site.md   # Meta / docs-as-code notes
├── projects/               # Selected work
├── recommendations.md
├── work-with-me.md
└── appendix/
```
