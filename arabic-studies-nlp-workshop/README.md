# Arabic Studies and NLP: Language, Power, and Method

**Format:** six-hour introductory workshop  
**Audience:** Arabic studies and humanities participants with no coding background  
**Tools:** Google Colab, Python, CAMeL Tools, sample OpenITI/KITAB-style data  
**Level:** absolute beginner, academically framed

This repository contains materials for a six-hour introductory workshop on Arabic natural language processing (NLP) for students and researchers in Arabic studies, Islamic studies, Middle Eastern studies, linguistics, digital humanities, and adjacent fields.

The workshop assumes no previous experience with Python, Google Colab, Jupyter-style notebooks, or computational methods. It is designed as a first encounter with digital text analysis: participants learn how to open a Colab notebook, run small pieces of code, inspect Arabic text as data, and discuss the scholarly limits of NLP methods.

> **Core principle:** the workshop teaches computational practice and critical interpretation together. Participants learn what the tools do, and also what the tools cannot responsibly claim.

## Learning Goals

By the end of the workshop, participants should be able to:

- explain what NLP means in the context of Arabic textual research;
- open and run a Google Colab notebook with instructor support;
- recognize Python strings, code cells, markdown cells, and printed output;
- describe why Arabic script, Unicode, diacritics, morphology, and dialects matter computationally;
- compare simple whitespace tokenization with Arabic-aware tokenization;
- perform a small corpus exploration using sample OpenITI/KITAB-style materials;
- interpret model demonstrations cautiously rather than treating model output as evidence on its own;
- connect technical choices to questions of corpus construction, representation, power, and bias.

## Workshop Route

The recommended route for a live six-hour session is:

| Stage | Focus | Main Material |
| --- | --- | --- |
| 1 | Introduction | Shared Colab notebook and website |
| 2 | What is (NOT) NLP | Website exercises and discussion |
| 3 | Arabic NLP | Shared Colab notebook |
| 4 | Lunch break | Break |
| 5 | Let's code! | Shared CAMeL Tools Colab notebook |
| 6 | Beyond Model Bias and evaluation | Discussion, evaluation, and outlook |

## Start Here

| Role | First File | Purpose |
| --- | --- | --- |
| Participant | [PARTICIPANT-GUIDE.md](PARTICIPANT-GUIDE.md) | Plain-language orientation, Colab expectations, and notebook basics |
| Teaching assistant | [setup/troubleshooting.md](setup/troubleshooting.md) | Common Colab problems and beginner-friendly fixes |

For the public schedule and participant-facing workshop route, use the GitHub Pages site in [../docs/schedule.html](../docs/schedule.html).

## Participant Website

The folder [docs/](docs/) contains a participant-only GitHub Pages website. It includes the public workshop overview, Colab setup instructions, schedule, participant materials, glossary, readings, and instructor profile.

To publish it, configure GitHub Pages to deploy from the `/docs` folder. See [GITHUB-PAGES.md](GITHUB-PAGES.md).

## Repository Structure

| Path | Contents |
| --- | --- |
| `PARTICIPANT-GUIDE.md` | Plain-language guide for learners who are new to coding tools |
| `setup/` | Colab readiness, quick start, and troubleshooting |
| `notebooks/` | Source notebook materials retained for instructor/reference use |
| `data/` | Small sample text, cleaned text, metadata, and data notes |
| `readings/` | Essential readings, optional readings, and glossary |
| `exercises/` | Participant exercises and instructor solution outline |
| `slides/` | Slide companion notes and slide deck file |
| `docs/` | Participant-facing GitHub Pages website |

## Technical Requirements

Participants need:

- a laptop with internet access;
- a Gmail/Google account, either existing or newly created;
- about 6 GB of free Google Drive storage for Colab files and runtime data;
- a modern browser such as Firefox, Chrome, Edge, or Safari.

Participants do not need to download this repository or install Python locally. The live hands-on work uses this shared Colab notebook:

https://colab.research.google.com/drive/1Y3qCbD6Gw1KEw-lixQx1rI6WlyWnrnDS?usp=sharing#scrollTo=X3KV4vNDDtG8

No previous programming knowledge is required. Arabic reading knowledge is helpful for interpreting examples, but the code activities are designed to be understandable with transliteration or instructor explanation.

## Teaching Principles

This workshop treats NLP as both a practical method and an object of scholarly critique. The goal is not to make participants “fluent in Python” in one day. The goal is to make the basic workflow legible enough that participants can ask better research questions, evaluate tools more critically, and continue learning with confidence.

## Document Style

The materials use a consistent format: short introductions, tables for navigation, numbered steps for actions, and quotation-style callouts for important cautions. See [STYLE-GUIDE.md](STYLE-GUIDE.md) for maintainers.

## License

This repository is shared under the MIT License. See [LICENSE](LICENSE) for details.
