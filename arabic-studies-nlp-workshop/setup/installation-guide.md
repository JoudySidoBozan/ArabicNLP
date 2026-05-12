# Installation Guide

**Audience:** first-time users  
**Goal:** create the workshop environment and open JupyterLab  
**Estimated time:** 20-40 minutes, depending on internet speed

This guide prepares your computer for the Arabic Studies and NLP workshop. It is written for first-time users. Please move slowly and copy commands exactly.

> **Before you begin:** if installation fails, you can still participate through the instructor's screen or a partner's working setup.

## What Installation Means

The workshop uses Python packages that are not usually installed on a new computer. We use **Conda** to create a separate workshop environment. This keeps the workshop tools together in one place.

You only need to do the installation once.

## Installation Overview

| Step | Action | Success marker |
| --- | --- | --- |
| 1 | Install Miniconda or Anaconda | `conda --version` prints a version number |
| 2 | Open Terminal or Anaconda Prompt | You can type commands |
| 3 | Move into the workshop folder | `README.md` and `environment.yml` are visible |
| 4 | Create the environment | Conda finishes without an error |
| 5 | Activate the environment | The prompt shows the workshop environment name |
| 6 | Start JupyterLab | A browser window opens |
| 7 | Open the first notebook | A code cell prints output |

## Step 1: Install Miniconda or Anaconda

Install either Miniconda or Anaconda before the workshop:

- Miniconda: https://docs.conda.io/en/latest/miniconda.html
- Anaconda: https://www.anaconda.com/download

If you are unsure which one to choose, use Miniconda. It is smaller.

After installation, close and reopen Terminal or Anaconda Prompt.

## Step 2: Open the Correct Command Window

Use the command window for your operating system:

| System | Open this |
| --- | --- |
| macOS | `Terminal` |
| Windows | `Anaconda Prompt` from the Start menu |
| Linux | Your usual terminal application |

In the workshop, “terminal” means this command window.

## Step 3: Go to the Workshop Folder

Your command window needs to be inside the repository folder before you create the environment.

If the folder is on your Desktop, the command may look like this:

```bash
cd Desktop/arabic-studies-nlp-workshop
```

If the folder is somewhere else, ask the instructor for help. You can also drag the folder into many terminal windows to paste its path.

To check that you are in the right place, run:

```bash
ls
```

On Windows Anaconda Prompt, use:

```bash
dir
```

You should see files such as `README.md`, `environment.yml`, `notebooks`, and `setup`.

## Step 4: Create the Workshop Environment

Run this command from inside the workshop folder:

```bash
conda env create -f environment.yml
```

This step may take several minutes. It downloads Python and the required packages.

## Step 5: Activate the Environment

Run:

```bash
conda activate arabic-studies-nlp-workshop
```

After this works, you may see `(arabic-studies-nlp-workshop)` at the beginning of the command line. That is a good sign.

## Step 6: Open JupyterLab

Run:

```bash
jupyter lab
```

A browser window should open. If it does not open automatically, the terminal usually prints a link beginning with `http://localhost:`. Copy that link into your browser.

## Step 7: Open the First Notebook

In JupyterLab, open:

```text
notebooks/00_welcome_and_navigation.ipynb
```

Run the first code cell. If you see printed output underneath the cell, your installation is ready.

## If Something Goes Wrong

Use [troubleshooting.md](troubleshooting.md). If the environment creation fails during the workshop, continue with the instructor's shared screen or the backup activities. Installation problems are common and do not mean you are doing badly.
