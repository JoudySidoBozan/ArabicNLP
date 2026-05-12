# Workshop Exercise Sheet

**Audience:** participants  
**Mode:** individual or pair work  
**Use with:** notebooks `01` to `05`

These exercises are designed for first-time coders. Work slowly. You may complete them in pairs, and you may use the notebooks as models.

> **How to work:** run a known example first, then change one small thing. If the output changes, describe what changed.

## Exercise Overview

| Exercise | Method focus | Reflection focus |
| --- | --- | --- |
| 1 | Python strings, `print()`, `len()`, `split()` | What counts as a character or word? |
| 2 | Tokenization and normalization | What changes when text is standardized? |
| 3 | Corpus loading, frequency, search | What can a small sample show? |
| 4 | Written reflection | What are the limits of NLP evidence? |

## Exercise 1: Arabic Strings in Python

**Goal:** notice how Python treats Arabic text as text data.

1. Create a Python string with a short Arabic sentence.
2. Print the sentence.
3. Use `len()` to count characters.
4. Use `split()` to divide the sentence at spaces.
5. Write one sentence explaining whether the computer's count matches what you expected.

Example:

```python
text = 'هذا مثال قصير'
print(text)
print(len(text))
print(text.split())
```

## Exercise 2: Tokenization and Normalization

**Goal:** understand that preprocessing changes what can be counted.

1. Choose a short sentence with Arabic diacritics, punctuation, or different forms of alef.
2. Tokenize it with CAMeL Tools.
3. Remove diacritics or normalize one character form.
4. Compare the original and normalized versions.
5. Write down one scholarly risk: what might be lost when the text is normalized?

## Exercise 3: Corpus Exploration

**Goal:** move from one sentence to a small corpus sample.

1. Load `data/raw/openiti_sample.txt`.
2. Print the first lines or the full sample.
3. Count word frequencies.
4. Choose one word and search for it in context.
5. Write one cautious observation about the sample. Avoid making a claim about all Arabic texts from one small file.

## Exercise 4: Critical Reflection

Answer these prompts in a short paragraph:

1. What kinds of texts are represented in an OpenITI-style corpus?
2. Which kinds of Arabic might be less visible in such a corpus?
3. How might OCR errors, spelling variation, or editorial decisions affect NLP results?
4. Why should model outputs be treated as evidence that requires interpretation, rather than as automatic answers?

> **Submission format:** a short notebook, text document, or handwritten response is enough. The aim is to show method awareness, not polished programming.
