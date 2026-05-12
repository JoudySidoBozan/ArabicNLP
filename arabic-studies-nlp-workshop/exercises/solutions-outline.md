# Solutions Outline

**Audience:** instructors and teaching assistants  
**Purpose:** evaluation guidance, not a model answer sheet

This outline is for instructors and teaching assistants. Treat it as a guide to the kinds of answers that show understanding, not as a single correct solution.

## Evaluation Emphasis

| Look for | Do not require |
| --- | --- |
| Clear observation of output | Perfect Python syntax from memory |
| Awareness of preprocessing choices | Advanced linguistic analysis |
| Cautious claims about small data | Broad claims about Arabic from the sample |
| Connection between method and interpretation | Technical vocabulary without understanding |

## Exercise 1

- A suitable string might be `text = 'مرحبا بك في ورشة عمل العربية'`.
- `print(text)` should display the Arabic sentence.
- `len(text)` returns a character count, including spaces and diacritics if present.
- `text.split()` returns a list based on whitespace.
- A strong response notices that computer counts are precise but not automatically linguistically meaningful.

## Exercise 2

- CAMeL Tools tokenization should produce a list of tokens.
- Normalization may remove diacritics or standardize character forms.
- Learners should notice that normalization can help searching and counting.
- Learners should also notice that normalization may remove philologically or linguistically relevant detail.

## Exercise 3

- The notebooks use `Path(...).read_text(encoding='utf-8')` to load the sample.
- A simple dictionary or `collections.Counter` can count word frequencies.
- A concordance-style answer can use `text.find(query)` and print nearby characters.
- A strong response avoids overgeneralizing from the small teaching sample.

## Exercise 4

Answers should mention some combination of:

- corpus genre and provenance;
- digitized historical text;
- dialect and register representation;
- OCR or transcription problems;
- metadata limits;
- model predictions as outputs requiring interpretation.
