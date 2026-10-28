# AI Context Engineering & QA Evaluation Lab

## Overview
This case study demonstrates the optimization of LLM responses for AI Quality Assurance (QA) evaluation. It highlights the technical progression from simple baseline prompting to engineered output schemas, and ultimately to persistent system context engineering.

## Framework Methodology
- **Run 1 (Baseline):** Basic unguided prompting resulting in unstructured, text-heavy output.
- **Run 2 (Prompt Engineering):** Defined role personas, negative constraints, and structured Markdown output tables with iterative feedback loops.
- **Run 3 (Context Engineering):** Moved evaluation rubrics into persistent System Instructions (`Custom Instructions`), maximizing attention budget and enabling concise, predictable short prompts.

## Key Technical Concepts Applied
- **Attention Budget Management:** Directing token attention toward critical security violations.
- **Context Rot Mitigation:** Maintaining lean, high-signal system contexts without clutter.
- **Schema Enforcement:** Standardizing output structures for automated downstream ingestion.

## Repository Structure
- `01_baseline_run.md` - Initial baseline prompt and unstructured findings.
- `02_prompt_engineering.md` - Engineered prompt and 4-column feedback iteration.
- `03_context_engineering.md` - System instructions setup and optimized short prompt execution.
