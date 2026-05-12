# Arabic Studies and NLP: Language, Power, and Method

**Format:** six-hour introductory workshop  
**Audience:** Arabic studies and humanities participants with no coding background  
**Tools:** JupyterLab, Python, CAMeL Tools, sample OpenITI/KITAB-style data  
**Level:** absolute beginner, academically framed

This repository contains materials for a six-hour introductory workshop on Arabic natural language processing (NLP) for students and researchers in Arabic studies, Islamic studies, Middle Eastern studies, linguistics, digital humanities, and adjacent fields.

The workshop assumes no previous experience with Visual Studio Code, Terminal, Python, Jupyter notebooks, or computational methods. It is designed as a first encounter with digital text analysis: participants learn how to open a notebook, run small pieces of code, inspect Arabic text as data, and discuss the scholarly limits of NLP methods.

> **Core principle:** the workshop teaches computational practice and critical interpretation together. Participants learn what the tools do, and also what the tools cannot responsibly claim.

## Learning Goals

By the end of the workshop, participants should be able to:

- explain what NLP means in the context of Arabic textual research;
- open and run a Jupyter notebook with instructor support;
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
| 1 | Arrival, orientation, folders, notebooks, and shared vocabulary | `00_welcome_and_navigation.ipynb` |
| 2 | Arabic strings, characters, Unicode, and printed Arabic output | `01_arabic_text_basics.ipynb` |
| 3 | Tokenization, normalization, and preprocessing as interpretation | `02_tokenization_and_normalization.ipynb` |
| 4 | Small-scale frequency and concordance work | `03_corpus_exploration_openiti.ipynb` |
| 5 | Conceptual introduction to Arabic language models | `04_intro_to_arabic_models.ipynb` |
| 6 | Dialects, digitization, historical corpora, bias, and responsible use | `05_bias_power_and_reflection.ipynb` |

## Start Here

| Role | First File | Purpose |
| --- | --- | --- |
| Participant | [PARTICIPANT-GUIDE.md](PARTICIPANT-GUIDE.md) | Plain-language orientation, setup expectations, and notebook basics |
| Instructor | [instructor-notes/teaching-plan.md](instructor-notes/teaching-plan.md) | Pedagogical plan, pacing, and facilitation principles |
| Teaching assistant | [setup/troubleshooting.md](setup/troubleshooting.md) | Common setup problems and beginner-friendly fixes |

For timing, use [instructor-notes/timing.md](instructor-notes/timing.md).

## Participant Website

The folder [docs/](docs/) contains a participant-only GitHub Pages website. It includes the public workshop overview, setup instructions, schedule, participant materials, glossary, readings, and instructor profile.

To publish it, configure GitHub Pages to deploy from the `/docs` folder. See [GITHUB-PAGES.md](GITHUB-PAGES.md).

## Repository Structure

| Path | Contents |
| --- | --- |
| `PARTICIPANT-GUIDE.md` | Plain-language guide for learners who are new to coding tools |
| `setup/` | Installation, quick start, installation test, and troubleshooting |
| `notebooks/` | Interactive workshop notebooks, numbered in teaching order |
| `data/` | Small sample text, cleaned text, metadata, and data notes |
| `readings/` | Essential readings, optional readings, and glossary |
| `exercises/` | Participant exercises and instructor solution outline |
| `instructor-notes/` | Teaching plan, timing, and backup activities |
| `slides/` | Slide companion notes and slide deck file |
| `docs/` | Participant-facing GitHub Pages website |

## Technical Requirements

Participants need:

- a laptop with internet access;
- permission to install software before the workshop;
- Miniconda or Anaconda;
- a modern browser such as Firefox, Chrome, Edge, or Safari.

No previous programming knowledge is required. Arabic reading knowledge is helpful for interpreting examples, but the code activities are designed to be understandable with transliteration or instructor explanation.

## Teaching Principles

This workshop treats NLP as both a practical method and an object of scholarly critique. The goal is not to make participants “fluent in Python” in one day. The goal is to make the basic workflow legible enough that participants can ask better research questions, evaluate tools more critically, and continue learning with confidence.

## Document Style

The materials use a consistent format: short introductions, tables for navigation, numbered steps for actions, and quotation-style callouts for important cautions. See [STYLE-GUIDE.md](STYLE-GUIDE.md) for maintainers.

## License

This repository is shared under the MIT License. See [LICENSE](LICENSE) for details.
