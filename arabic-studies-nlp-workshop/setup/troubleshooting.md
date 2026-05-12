# Troubleshooting

**Use when:** installation, JupyterLab, imports, or notebook cells do not behave as expected.

Installation and notebook errors are normal in beginner workshops. This page lists common problems and what to try first.

> **First rule:** read the error calmly, then check whether you are in the right folder and the right Conda environment.

## Quick Diagnosis

| Symptom | First thing to check |
| --- | --- |
| `conda` is not recognized | Use Anaconda Prompt on Windows, or reopen Terminal after installing Conda |
| `environment.yml` is missing | Move into the `arabic-studies-nlp-workshop` folder |
| `camel_tools` does not import | Activate `arabic-studies-nlp-workshop` |
| JupyterLab does not open | Copy the `http://localhost:` link into a browser |
| A notebook cell runs forever | It may be downloading a model; ask before interrupting |
| Arabic looks odd in Terminal | Compare with the notebook display in the browser |

## I Do Not Know Where the Repository Folder Is

Find the folder named `arabic-studies-nlp-workshop` in Finder, File Explorer, or your file manager.

Then open Terminal or Anaconda Prompt and use `cd` to move into that folder. If you are unsure how to do this, ask the instructor. This is one of the most common first-time issues.

## `conda` Is Not Recognized

This usually means Miniconda or Anaconda is not installed correctly, or the command window was opened before installation finished.

Try:

1. Close Terminal or Anaconda Prompt.
2. Open it again.
3. Run:

   ```bash
   conda --version
   ```

On Windows, use **Anaconda Prompt**, not PowerShell, unless you already know your setup works.

## The Environment Creation Fails

Check that you are inside the workshop folder:

```bash
ls
```

On Windows Anaconda Prompt:

```bash
dir
```

You should see `environment.yml`. Then try:

```bash
conda env create -f environment.yml
```

If Conda says the environment already exists, activate it instead:

```bash
conda activate arabic-studies-nlp-workshop
```

## Python Import Errors

If `camel_tools` or `transformers` fail to import, first check that the correct environment is active:

```bash
conda activate arabic-studies-nlp-workshop
python -c "import camel_tools, transformers; print('OK')"
```

If the command prints `OK`, the packages are installed.

## JupyterLab Does Not Open

Try:

```bash
jupyter lab
```

If that does not work, try:

```bash
jupyter notebook
```

If the browser does not open automatically, copy the `http://localhost:` link from the terminal into your browser.

## Notebook Cells Do Not Run

Try these steps in JupyterLab:

1. Use `Kernel > Restart Kernel`.
2. Start again from the first cell.
3. Run cells in order from top to bottom.

If a cell is still busy after a long time, it may be downloading a model. Ask the instructor before interrupting it.

## Arabic Text Looks Disconnected or Reversed

Some tools display Arabic better than others. The notebooks should display Arabic correctly in the browser. If a terminal output looks awkward, compare it with the notebook output before assuming the text is wrong.

## The Model Notebook Is Slow

The model notebook may download files the first time it runs. This can take several minutes and depends on the internet connection. The instructor can demonstrate this section from one machine if needed.
