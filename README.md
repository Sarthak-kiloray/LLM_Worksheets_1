# LLM Worksheets – Project Overview

### This repository contains a collection of Jupyter notebooks and scripts demonstrating how to use large language models (LLMs) for tasks such as API interaction, content generation, and tokenization. These worksheets were prepared as part of a learning project and illustrate various ways to harness LLMs to automate or assist with everyday work. Each notebook stands alone, but together they provide a progressive exploration of the OpenAI API, prompt engineering, and data manipulation.

---

## Repository contents

The root of the repository includes the following notable files and directories:

| File                      | Description                                                                                                                                                                                                                                                                                                                                                                                       |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `basic_lab.ipynb`         | A hands‑on lab showing how to call OpenAI’s chat completion endpoint using both raw HTTP requests and the OpenAI Python SDK.  It demonstrates reading the API key from a `.env` file, constructing request payloads, sending them to the API, and printing the responses.  Later cells show how to define a `system_prompt` and `user_prompt` to generate subject lines for a professional email. |
| `Business_brochure.ipynb` | A notebook (not viewable in the environment) presumably designed to use an LLM to generate marketing or business‑brochure content.  It likely demonstrates using a system prompt to instruct the model to act as a copywriter and then produces formatted text describing products or services.                                                                                                   |
| `Figma_AI.ipynb`          | This notebook failed to open due to an invalid JSON error.  It seems to be intended for integrating LLM‑generated content into Figma designs; however the file may be corrupted or incomplete.                                                                                                                                                                                                    |
| `tokenizer.ipynb`         | A notebook (not opened here) that likely explores how tokenization works in LLMs.  It may show how to use libraries such as `tiktoken` to count tokens and understand cost estimation.                                                                                                                                                                                                            |
| `scraper.py`              | A simple Python script (not executed here) for scraping text from websites.  It could be used to gather content that feeds into an LLM.                                                                                                                                                                                                                                                           |
| `requirements.txt`        | Lists the Python dependencies required for these notebooks, such as `openai`, `python-dotenv`, `transformers`, `gradio`, etc., to enable API calls and interactive demos.                                                                                                                                                                                                                         |


## Lessons from other notebooks

Business_brochure.ipynb (not viewable here) likely demonstrates using a system prompt to instruct the LLM to act as a marketing copywriter. It probably shows how to generate a brochure for a fictional business by providing details such as company name, services, and desired tone. Incorporate a screenshot of the generated brochure text or the relevant code cell to illustrate this capability.

Figma_AI.ipynb could be intended for integrating LLM‑generated content into Figma design files. The notebook did not open due to a JSON error
github.com
, but you may replace it or fix the notebook. If the notebook is repaired, include a screenshot demonstrating how textual output from the model can be used to populate design templates or UI components.

tokenizer.ipynb (not opened) probably explores token counting and cost estimation. A useful screenshot would show how different pieces of text are tokenized and how many tokens they consume. This helps stakeholders understand that API costs scale with tokens and emphasizes the importance of concise prompts.
