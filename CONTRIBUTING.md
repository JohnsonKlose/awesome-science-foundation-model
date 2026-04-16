# Contributing

Thank you for your interest in contributing to the Science Foundation Models list! We welcome contributions from the community.

## How to Add a New Model

1. **Fork** this repository and create a new branch.
2. Add the model entry to **all relevant files** (see below).
3. Submit a **pull request** with a clear description.

### Which Files to Edit

Every model must appear in **4 files**:

| File | Format |
|------|--------|
| `README.md` | English 4-column table |
| `README.zh.md` | Chinese 7-column table |
| `<domain>/<domain>_en.md` | Same as README.md row |
| `<domain>/<domain>_zh.md` | Same as README.zh.md row |

### English Table Format (README.md, *_en.md)

```markdown
| Model Name | Paper Title | Brief description of the model. | [Venue](https://doi.org/...) |
```

### Chinese Table Format (README.zh.md, *_zh.md)

```markdown
| Model Name | Paper Title | First Author | Year | ArXiv/DOI | Venue | Chinese description |
```

## Inclusion Criteria

We include **foundation models** for scientific domains. The following are **excluded**:

- Pure datasets or benchmarks
- Challenge competitions
- Software libraries or toolkits
- Product-only announcements without a paper

## Quality Checklist

Before submitting, please verify:

- [ ] The model is a scientific foundation model (not a dataset/benchmark/library)
- [ ] The link points to the official publication or preprint
- [ ] The entry is placed in the correct domain and subsection
- [ ] The entry appears in all 4 required files
- [ ] English files contain no Chinese characters
- [ ] The description is one concise sentence

## Suggesting a Reclassification

If you believe a model is in the wrong subsection, open an issue or PR explaining why. Models with interdisciplinary relevance may appear in multiple sections.

## Code of Conduct

Be respectful and constructive. We are all here to build a useful resource for the scientific community.
