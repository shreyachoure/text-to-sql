# Text to SQL analysis with Large Language Models

## Project Description
1. Enhanced the performance of Text-to-SQL translation models (Code Bison, Gemma, GPT 3.5) in a CS 410/510 project, achieving a notable improvement in accuracy; for example, GPT-3.5's Rouge-1 score increased to 0.92 post-fine-tuning.
2. Applied advanced fine-tuning techniques (LoRA, QLoRA) on a dataset of 78.5K examples, leading to significant efficiency gains; Code Bison achieved a CodeBleu score of 0.88, indicating a high level of syntactic and semantic accuracy in generated SQL queries.
3. Demonstrated a marked improvement in model performance, with closed models like GPT-3.5 showing near 95% accuracy for simple queries, and identified potential for future domain-specific enhancements to further boost SQL query translation accuracy.

## Models
1. Code Bison: https://cloud.google.com/vertex-ai/generative-ai/docs/model-reference/code-generation
2. GPT 3.5 Turbo: https://openai.com/blog/gpt-3-5-turbo-fine-tuning-and-api-updates 
3. Gemma - 2B: https://huggingface.co/google/gemma-2b

![Screenshot 2024-03-18 at 11 17 55 AM](https://github.com/shreyachoure/text-to-sql/assets/56231644/1cc1f288-1aea-4043-a3e2-47089218c9a5)

## Evaluation 
<img width="1131" alt="Screenshot 2024-03-18 at 11 19 15 AM" src="https://github.com/shreyachoure/text-to-sql/assets/56231644/466d46f5-9380-41ed-9b98-ec21dfadd316">
![Screenshot 2024-03-18 at 11 20 33 AM](https://github.com/shreyachoure/text-to-sql/assets/56231644/49bd530c-21e8-4d33-a9ce-9740a4400e79)


