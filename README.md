# LLM Model Comparison & Output Evaluation (No-Code)

## Overview
This project evaluates the behavior of multiple Large Language Models (LLMs) — GPT, Gemini, and Claude — using identical prompts and a structured evaluation framework. The goal is to compare model outputs based on accuracy, completeness, tone, and safety without writing any code.

All experiments were conducted using no-code UI tools such as Google AI Studio and Claude Web Interface, reflecting real-world workflows.

## Objectives
- Compare LLM outputs using controlled prompts
- Identify behavioral differences across models
- Evaluate compliance risk and instruction adherence
- Build a reproducible, documented evaluation framework

## Models Evaluated
- GPT (via UI interface)
- Gemini (Google AI Studio)
- Claude (Anthropic Web UI)

## Evaluation Criteria
Models were scored using the ACTS framework:
- **Accuracy** – correctness of information
- **Completeness** – coverage of required points
- **Tone** – appropriateness and neutrality
- **Safety** – absence of interpretation or compliance risk

## Key Findings
- GPT produced the most comprehensive summaries but introduced interpretive compression.
- Claude demonstrated the most conservative and safety-oriented behavior but omitted certain procedural details.
- Gemini adhered most strictly to prompt instructions but under-covered some policy exclusions.

Model selection should be task- and risk-dependent rather than based on perceived overall quality.

## Skills Demonstrated
- Prompt evaluation and comparison
- LLM behavior analysis
- AI quality and safety assessment
- No-code AI workflows
- Technical documentation

## Disclaimer
This project is for evaluation and learning purposes only. Outputs were analyzed qualitatively and are not intended for production or legal use.
