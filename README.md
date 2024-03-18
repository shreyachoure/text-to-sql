# Text-to-SQL Code Generation vs Text Generation Models

## Overview
This project focuses on enhancing the performance of translating natural language questions into SQL queries. Utilizing Parameter-Efficient Supervised Fine-Tuning (PEFT) techniques on models like Code Bison, GPT-3.5, and Gemma, we aim to refine their ability to generate accurate SQL queries based on given schemas or table contexts.

## Goals
1. Investigate the performance improvements in code and text generation models following parameter-efficient supervised fine-tuning in the context of translating natural language queries into SQL commands.
2. Address challenges such as the scarcity of text-to-SQL research on recent models like Gemma and the generation of visualizations directly from natural language queries.

## Methedology
1. Fine-Tuning: We applied Parameter-Efficient Fine-Tuning to enhance model performance with a focus on text generation tasks. Techniques like Low-Rank Adaptation (LoRA) and Quantized Low-Rank Adaptation (QLoRA) were utilized to optimize the fine-tuning process.
2. Models Tested: The project tested models including Code Bison, Gemma, and GPT-3.5 Turbo through various fine-tuning workflows to improve their SQL code generation capabilities.
3. Performance Evaluation: Models were assessed based on ROUGE scores and exact match metrics to determine their effectiveness in producing accurate SQL queries.

## Results
1. Prompt Engineering: Our findings showed varied ROUGE scores across models, indicating differences in their text generation capabilities.
2. Fine Tuning: After fine-tuning, the models demonstrated significant improvements in generating text that closely matches reference SQL queries.
3. Model Experimentation: We created a database schema, according tables to showcase our LLM class schedule, student participation and other insights on PgAdmin as a part of our model  experimentation and wrote questions to get SQL queries.

## Future Directions
1. Extending model capabilities to specialized domains and different database types.
2. Enhancing models to automatically adapt to various database schemas.
3. Investing in advanced Natural Language Understanding techniques for better handling of complex SQL queries.
