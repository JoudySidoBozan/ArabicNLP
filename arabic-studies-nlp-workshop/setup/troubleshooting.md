# Troubleshooting

**Use when:** Google Colab, Google Drive, or notebook cells do not behave as expected.

Colab and notebook errors are normal in beginner workshops. This page lists common problems and what to try first.

> **First rule:** read the message calmly, then check whether you are signed in to the right Google account.

## Quick Diagnosis

| Symptom | First thing to check |
| --- | --- |
| Colab notebook does not open | Sign in to a Google account and try a modern browser |
| Cannot save a copy | Check Google Drive storage and account permissions |
| Google Drive is full | Free space or use another Google account with about 6 GB available |
| A cell asks for permission | Read the prompt and approve only if it is needed for your notebook or Drive files |
| A notebook cell runs for a long time | It may be installing CAMeL Tools or downloading model data; ask before interrupting |
| Arabic text looks odd | Compare with the notebook display and the instructor's shared screen |

## Colab Does Not Open

Try these steps:

1. Make sure you are connected to the internet.
2. Sign in to your Google account.
3. Open the notebook link again:
   <https://colab.research.google.com/drive/1Y3qCbD6Gw1KEw-lixQx1rI6WlyWnrnDS?usp=sharing#scrollTo=X3KV4vNDDtG8>
4. If one browser fails, try Chrome, Firefox, Edge, or Safari.

## Google Drive Storage Is Full

Colab may need space to save a copy of the notebook and related files. Check that your Google Drive account has about 6 GB free. If not, delete unneeded files or use another Google account.

## Notebook Cells Do Not Run

Try these steps in Colab:

1. Use `Runtime > Restart session`.
2. Start again from the first cell.
3. Run cells in order from top to bottom.

If a cell is still busy after a long time, it may be installing packages or downloading model data. Ask the instructor before interrupting it.

## The Runtime Disconnects

Use the reconnect button in Colab. After reconnecting, rerun earlier setup cells if needed. Colab runtimes are temporary, so a disconnected session may forget variables or installed packages.

## Arabic Text Looks Disconnected or Reversed

Some tools display Arabic better than others. The notebook should display Arabic correctly in the browser. If output looks awkward, compare it with the instructor's screen before assuming the text is wrong.
