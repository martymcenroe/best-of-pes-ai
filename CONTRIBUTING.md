# Contributing to Best-of PES-AI

Thanks for your interest in improving this list! Contributions from the power systems and AI/ML communities are welcome.

## How to Add a Project

1. **Fork** this repository
2. **Edit** `projects.yaml` — add your project entry under the `projects:` section
3. **Submit a pull request** with a brief description of the project and why it belongs

### Project Entry Format

```yaml
- name: "Project Name"
  github_id: "owner/repo"
  category: "category-key"
  labels: ["python", "pytorch"]
  description: "Brief description (under 125 characters)."
  pypi_id: "package-name"          # optional
  conda_id: "conda-forge/name"     # optional
  homepage: "https://..."           # optional
```

### Available Categories

| Key | Title |
|-----|-------|
| `load-forecasting` | Load & Demand Forecasting |
| `grid-optimization` | Grid Optimization & Operations |
| `renewable-forecasting` | Renewable Energy Forecasting |
| `fault-detection` | Fault Detection & Diagnostics |
| `grid-stability` | Grid Stability & Reinforcement Learning |
| `der-management` | DER & Microgrid Intelligence |
| `nlp-standards` | NLP for Energy & Standards |
| `synthetic-data` | Synthetic Data & Benchmarks |
| `computer-vision` | Computer Vision for Infrastructure |
| `energy-markets` | Energy Market & Price Forecasting |

### Available Labels

`python`, `julia`, `jupyter`, `tensorflow`, `pytorch`, `university`, `national-lab`

## How to Suggest a New Category

[Open an issue](https://github.com/martymcenroe/best-of-pes-ai/issues/new) describing:
- The proposed category name and key
- Why it's distinct from existing categories
- At least 2-3 example projects that would belong

## Inclusion Criteria

A project **must** meet all of the following:

- Open source with a recognized license
- Hosted on GitHub
- Relevant to AI/ML applied to power & energy systems
- Actively maintained (or historically significant with substantial community use)

## Out of Scope

The following do **not** belong on this list:

- **Pure power systems tools without AI/ML component** — those belong in [best-of-ps](https://github.com/ps-wiki/best-of-ps)
- **Proprietary or commercial tools** — even if they have a GitHub presence
- **Academic papers without code** — we list software, not publications
- **General-purpose ML frameworks** — unless specifically adapted for energy applications

## Code of Conduct

Be respectful and constructive. We follow the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).

## Questions?

Open an issue or reach out to the maintainer.
