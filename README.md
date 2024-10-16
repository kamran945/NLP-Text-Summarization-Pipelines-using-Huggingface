# NLP-Text-Summarization-Pipelines-using-Huggingface
## Hugging Face Pipelines for Text Summarization
* **Summarization**: Process of creating a shorter version of a longer text while retaining its key information and overall meaning is called text summarization.
* **Hugging Face pipeline** simplifies the implementation of this task by allowing users to quickly load pretrained models and apply them to their input text.
* **How to use**:
  * **Import the Library:** `from transformers import pipeline`
  * **Create a Summarization Pipeline:**  `summarizer = pipeline("summarization")`
  * **Summarize Text:**
    * `input_text = "Your long input text goes here."
    * `summary = summarizer(input_text, max_length=150, min_length=30, do_sample=False)`
    * `print(summary)`
`
