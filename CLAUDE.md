# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repo Is

A bilingual (EN/ZH) awesome-list cataloging 1,000+ scientific foundation models across 9 domains. This is a **content-only** repo — no source code, no build system, no tests. All files are Markdown.

## File Structure & Ground Truth

- **README.md** — English ground truth. All content originates here.
- **README.zh.md** — Chinese translation. Must stay in sync with README.md.
- **9 domain subdirectories** (e.g., `life-sciences/`, `medicine/`) — each contains `{domain}_en.md` and `{domain}_zh.md`, which are subsets of the corresponding README extracted by domain section.

### Heading Level Convention

README files use `## Domain` and `### Subsection`. Subdirectory files use `## Subsection` (one level less, since the domain heading becomes the file title).

### Table Formats

English files (README.md, *_en.md) use 4 columns:
```
| Model | Paper Title | Description | Link |
```

Chinese files (README.zh.md, *_zh.md) use 7 columns:
```
| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
```

### File Header Convention

Each subdirectory file has a header block (title, language switch link, description, index link, ToC) that is **independent** from README content. When syncing from README, preserve the existing file header and only replace content after it.

## Common Operations

### Adding a New Model

1. Add the row to README.md in the correct domain/subsection table
2. Add the corresponding Chinese row to README.zh.md in the matching section
3. Add the row to the domain's `_en.md` and `_zh.md` subdirectory files

### Moving a Model Between Sections

1. Remove from old location in all 4+ files (README.md, README.zh.md, old domain _en.md, old domain _zh.md)
2. Add to new location in all relevant files (README.md, README.zh.md, new domain _en.md, new domain _zh.md)

### Syncing Subdirectory Files from README

Extract the domain section from README.md/README.zh.md, adjust heading levels (`###` → `##`), and replace content in the subdirectory file while preserving its header block.

## Content Rules

- English files must contain **no Chinese characters**
- Models with interdisciplinary relevance may appear in multiple domain sections
- Only include foundation models — exclude pure datasets, benchmarks, challenge competitions, libraries, and product-only pages
- Link column should point to the official publication (journal/conference) or preprint (arXiv/bioRxiv)

## URL Verification Notes

- bioRxiv returns HTTP 403 to automated `curl` requests (bot blocking) — these URLs are valid
- Google/HuggingFace/DeepMind domains may return 000 from Chinese networks — these URLs are valid outside China
- DOI URLs (doi.org) returning 302 redirects are normal behavior
