# PapyrusBayan AI Lab

> **Mission:** Push the frontiers of Arabic‑centric NLP, speech, and multimodal AI while remaining fully open, ethically grounded, and community‑governed.

[![Join our Slack](https://img.shields.io/badge/Slack-join%20chat-blue?logo=slack)](https://join.slack.com/t/aiarabicgroup/shared_invite/zt-38vr4mla8-oKptDEcVTO3eFkwtUfK5CQ)

---

## Table of Contents

1. [Manifesto](#manifesto)
2. [Contribution Guide](#contribution-guide)

   * [Code Projects](#code-projects)
   * [Research Papers](#research-papers)
3. [Governance & Licensing](#governance--licensing)
4. [Contact](#contact)

---

## Manifesto

1. **Arabic‑first, dialect‑inclusive** – Every model must cover Modern Standard Arabic **plus** at least four major dialect families (Egyptian, Levantine, Gulf, Maghrebi).
2. **Open by default** – We release weights, data, and evaluation scripts under OSI‑approved licenses (≥ Apache‑2.0).
3. **Sovereign data stewardship** – Source data within the region, strip PII at ingest, host on regional clouds.
4. **Native alignment** – RLHF and evaluation prompts are authored and vetted only by fluent Arabic speakers.
5. **Responsible deployment** – Zero tolerance for disinformation, extremist propaganda, or surveillance tooling.
6. **Community governance** – Quarterly public steering meetings; any artifact can be vetoed by a 2⁄3 vote of an external advisory board spanning ≥ 5 Arab countries.
7. **Talent cultivation** – A minimum of 20 % of the annual budget funds fellowships, summer schools, and MOOCs delivered in Arabic.

---

---

## Contribution Guide

All contributors **must** join Slack and post an introduction in `#00‑introductions` before opening any issue or pull request.

### Code Projects

1. **Proposal first** – Open a GitHub Issue with the `RFC` label describing *scope, datasets, metrics, timeline*.
2. **Branch naming** – `feat/<project‑id>/<username>/<topic>` (e.g., `feat/P‑3/ayman/quant‑int8`).
3. **Style & tooling** – Python ≥ 3.10, Black, isort, Ruff, pre‑commit; mandatory type hints.
4. **Tests** – Each PR must raise code coverage for its module or keep ≥ 90 %.
5. **CI** – GitHub Actions run lint + pytest + model card checks; red CI blocks merging.
6. **Reviews** – Two core‑team approvals required; at least one reviewer must be outside the project subgroup.
7. **Model cards** – Follow the Hugging Face template, include license, intended use, biases, eval results.
8. **Releases** – Tag with semantic versioning (`vMAJOR.MINOR.PATCH`); publish wheels/docker and update CHANGELOG.

### Research Papers

1. **Intent issue** – Label `PAPER` with title, abstract, target venue, and related project ID (if any).
2. **Templates** – Use the lab’s Overleaf/LaTeX template (`/docs/paper‑template`) with built‑in BibLaTeX.
3. **Repro package** – Submit dataset card, training YAML, and inference notebook. Results must be reproducible on a single A100 80 GB or smaller.
4. **Internal review** – Two‑round peer review on Slack (`#papers‑review`); second round light copy‑edit by publication chair.
5. **Compliance** – Papers describing new datasets must ship a filled‑out Datasheet for Datasets; new models require a Model Card ++.

*Pull requests that skip any of the above checklists will be auto‑closed.*

---

## Governance & Licensing

* **Code of Conduct** – We follow the Contributor Covenant v2.1. Report violations in the `#conduct` Slack channel.
* **Models** – Apache‑2.0 or Creative Commons‑BY‑SA‑4.0; require a `Responsible‑Use‑Disclaimer`.
* **Data** – CC‑BY‑4.0 for text; CC‑BY‑NC‑4.0 for copyrighted material with explicit permission.

Quarterly governance meetings are announced in `#announcements`; minutes are logged in `/docs/governance`.

---

## Contact

* **GitHub:** [https://github.com/https-huggingface-co-PapyrusBayan](https://github.com/https-huggingface-co-PapyrusBayan)
* **Hugging Face:** [https://huggingface.co/PapyrusBayan](https://huggingface.co/PapyrusBayan)
* **Slack:** primary channel `#general` – [Join here](https://join.slack.com/t/aiarabicgroup/shared_invite/zt-38vr4mla8-oKptDEcVTO3eFkwtUfK5CQ)

Help us build the next generation of Arabic‑centric AI—responsibly, openly, and together.
