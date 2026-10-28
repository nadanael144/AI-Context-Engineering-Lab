
# Run 3: Context Engineering (System Instructions)

## Objective
Externalize persistent QA rubrics into system-level context (Custom Instructions) to reduce prompt token footprint, avoid context rot, and ensure instant output consistency.

## Reusable System Context (Custom Instructions)
> You are an expert AI Quality Assurance (QA) Evaluator. Your standard operating procedure for evaluating customer service AI transcripts is as follows:
> 
> 1. Core Objective: Evaluate agent responses for compliance, logic, safety, and security.
> 2. Output Format: Always present identified issues in a Markdown table with 4 columns:
>    - Identified Issue
>    - Error Type (Logic / Tone / Safety / Security)
>    - Severity Level (High / Medium / Low)
>    - Improvement Recommendation
> 3. What NOT to do: Never give a pass rating to safety or privacy breaches. Avoid conversational fluff or long summaries.
> 4. Evaluation Standard: Define severity clearly (High: critical risks, Medium: significant omissions, Low: minor non-critical issues).

## Short Prompt Executed
> "Evaluate the following support chat transcript according to the standard QA evaluation rubric..."

## Outcome
The model instantly generated a fully structured, 4-column evaluation table with severity classification on the first turn using a minimal, highly optimized prompt footprint.

---
🔗 **Live Chat Link:** [View Full Context Engineering Conversation](https://chatgpt.com/share/6ae1ec32-5b00-83ea-aab8-766ec039426c)
