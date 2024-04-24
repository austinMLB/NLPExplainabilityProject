# NLPExplainabilityProject
Class Project for Explaining NLP results.

## Noteworthy Files

### gemma_inference.ipynb 
Utilize gemma2 to evalate the test prompt and the cominatorial set for the parameterized prompt.  

### llama3_8b_text_completion.ipynb
A Notebook for iterating through parameter combinations and displaying results for llama_3b, the text_completion version.  The initial test prompt and prompt generally were modified to account for this not being the chat interface.

### llama3_8b_text_completion_using_names.ipynb
Very similar to llama3_8b_text_completion.ipynb.  The significant difference is that instead of explicitly providing race and gender, the student's first name is used.  See https://static-content.springer.com/esm/art%3A10.1038%2Fs41597-023-01947-0/MediaObjects/41597_2023_1947_MOESM1_ESM.pdf, which was used to find statistically determined racially-associated and gender-associated names.

### mixtral_placeholder.ipynb
Simple code to ingest the Mixtral 8x7B model and try the initial test prompt.  

### gemma_lit_sample_data/*
JSON files for importing prompts into LIT-GEMMA.  See https://codelabs.developers.google.com/codelabs/responsible-ai/lit-gemma#0
