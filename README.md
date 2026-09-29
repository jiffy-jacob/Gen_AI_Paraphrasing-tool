# AI Text Paraphrasing & Evaluation

## Overview

A Natural Language Processing project that uses a transformer-based T5 model to generate paraphrases of human-written text and evaluate the generated outputs.

## Technologies Used

* Python
* Hugging Face Transformers
* T5
* Sentence Transformers
* NLTK
* ROUGE
* LanguageTool
* Pandas

## Workflow

1. Load the human-written text dataset.
2. Generate multiple paraphrases using a pretrained T5 model.
3. Select the generated paraphrase for evaluation.
4. Compare the AI-generated text with the human reference text.
5. Evaluate text similarity using ROUGE and semantic similarity techniques.
6. Analyze the quality of the generated paraphrases.

## Model

**humarin/chatgpt_paraphraser_on_T5_base**

## Evaluation

The project uses:

* **ROUGE-1** – word-level similarity
* **ROUGE-2** – phrase-level similarity
* **ROUGE-L** – sequence similarity
* **Sentence-BERT** – semantic similarity
* **LanguageTool** – grammar analysis

## Conclusion

The project demonstrates the use of transformer-based NLP models for automatic paraphrasing and evaluates whether generated text preserves the meaning of human-written text while using different wording.

