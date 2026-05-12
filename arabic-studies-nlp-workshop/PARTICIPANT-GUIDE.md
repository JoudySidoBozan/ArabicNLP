# Participant Guide

**Purpose:** first orientation for learners new to coding tools  
**Use before:** `setup/installation-guide.md` and `notebooks/00_welcome_and_navigation.ipynb`

Welcome. This guide is written for people who have never used Visual Studio Code, Terminal, Python, or Jupyter notebooks before. You do not need to memorize the commands. During the workshop, the instructor will move slowly and you can ask for help at any point.

> **For beginners:** your task is not to become a programmer in one day. Your task is to learn enough of the workflow to understand what the tools are doing to Arabic text.

## What You Will Use

| Term | Meaning in this workshop |
| --- | --- |
| Folder | This repository, which contains all notebooks, data, and instructions |
| Terminal or Anaconda Prompt | A text-based way to ask your computer to open tools |
| Conda | A tool that creates a separate workshop environment |
| JupyterLab | A browser-based workspace where you run notebooks |
| Notebook | An interactive document with explanation cells and code cells |

## Before the Workshop

Please try to complete these steps before the session:

1. Install Miniconda or Anaconda.
2. Download or clone this repository.
3. Follow [setup/installation-guide.md](setup/installation-guide.md).
4. Run the test notebook described in [setup/quick-start.md](setup/quick-start.md).

If this does not work, do not panic. Bring your laptop anyway. The workshop includes a backup path for people whose installations fail.

## Workshop Path

| Step | File | What happens |
| --- | --- | --- |
| 1 | `PARTICIPANT-GUIDE.md` | Learn the basic vocabulary |
| 2 | `setup/installation-guide.md` | Install and prepare the environment |
| 3 | `setup/test-installation.ipynb` | Check that packages and data load |
| 4 | `notebooks/00_welcome_and_navigation.ipynb` | Learn how notebooks work |
| 5 | `notebooks/01...` to `05...` | Work through Arabic NLP examples |

## How to Read a Notebook

Jupyter notebooks are read from top to bottom.

| Notebook element | What it does |
| --- | --- |
| Markdown cell | Contains explanations, headings, or questions |
| Code cell | Contains Python code that can be run |
| Output | Appears underneath a code cell after it runs |
| Kernel | The Python process behind the notebook |

To run a code cell, click the cell and press the play button, or press `Shift+Enter`.

You are not expected to understand every symbol immediately. At this level, the first goal is to notice what changes when a cell runs.

> **If something breaks:** use `Kernel > Restart Kernel`, then run the cells again from the top.

## Workshop Etiquette

- Work slowly and keep the notebooks in order.
- Ask when a term is unfamiliar. Technical vocabulary is part of the lesson.
- Code errors are normal and often useful.
- If your screen does not match the instructor's screen, raise your hand early.
- When interpreting results, distinguish between what the computer counted and what a scholar can responsibly claim.

## File Map

- Start with `notebooks/00_welcome_and_navigation.ipynb`.
- Continue through the notebooks in numerical order.
- Use `exercises/exercise-sheet.md` for short practice tasks.
- Use `readings/glossaries/README.md` whenever a term feels unclear.
- Use `setup/troubleshooting.md` if the software does not open or a package fails to import.

## What This Workshop Is Not

This is not a full programming course, a complete Arabic linguistics course, or a comprehensive training in machine learning. It is a carefully paced introduction to the practical and critical questions that appear when Arabic texts become computational data.
