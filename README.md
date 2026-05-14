<a id="readme-top"></a>

<br />
<div align="center">

  <h1>Dev Index AI</h1>

  <h3 align="center">The AI dev-tool space, indexed.</h3>

  <p align="center">
    An index of AI dev tools sorted into categories, mixing public signals with editorial judgment.
  </p>

  <p align="center">
    <a href="https://devindex.ai/">Website</a>
    &middot;
    <a href="https://devindex.ai/tools/">Browse tools</a>
    &middot;
    <a href="https://github.com/kar2phi/devindex/issues/new/choose">Give feedback</a>
  </p>
</div>

---

- [What is it about?](#what-is-it-about)
- [How scoring works](#how-scoring-works)
- [What's in this repo?](#whats-in-this-repo)
- [Feedback](#feedback)
- [License](#license)

## What is it about?

**devindex.ai** is an index of AI dev tools sorted into categories, mixing public signals with editorial judgment on what's worth a closer look. Numbers are signals, not the final word. The project is still in beta.

What it's good for:

- Getting a quick index of what tools exist in a category
- Finding a credible shortlist and spotting newcomers picking up momentum
- Narrowing down by maturity, pricing, or open source vs SaaS

It is not a benchmark or a feature-by-feature comparison. For a final decision you still need to test the tools yourself.

## How scoring works

Each score blends public signals (popularity, activity, momentum, maturity, confidence) with curated ranks and editorial weights.

Read scores as category-local signals. Scores are weighted within a category, so comparing a coding agent to an MCP directory by raw score isn't meaningful. Tools sit in one primary category even when they straddle two, and commercial products often score lower because they generate less public data. The index reflects a curated read of the space, and your own priorities may rank things differently.

## What's in this repo?

This repository mirrors the public Dev Index AI data as two CSV files:

- [`data/tool_landscape_live.csv`](data/tool_landscape_live.csv) - the current tool catalog with categories, scores, links, metadata, pricing, and maturity fields.
- [`data/tool_categories.csv`](data/tool_categories.csv) - the authored category and subcategory taxonomy used by the index.

The CSVs are refreshed when the upstream curator publishes a new snapshot. Paths are stable, and schemas live in the column headers.

## Feedback

Use [GitHub issues](https://github.com/kar2phi/devindex/issues/new/choose) to report stale tool data, suggest missing tools, flag taxonomy problems, or ask about scoring. Reports opened from the site are prefilled with tool metadata; please leave that machine-readable block intact.

## License

This repository is released under the **Apache License 2.0**. See [`LICENSE`](LICENSE).

---

<div align="center">
  <sub><a href="#readme-top">Back to top</a></sub>
</div>
