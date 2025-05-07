# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

Comparative Analysis of Language Model Responses to Broad vs. Refined
Prompts
1. Introduction
This report evaluates how different AI language models respond to broad/unstructured prompts versus
refined prompts. The comparison focuses on the quality, accuracy, and depth of responses across
different scenarios.
2. Models Tested
• GPT-4 (Advanced proprietary model)
• Claude (Anthropic's AI assistant)
• Gemini (Google's AI)
• Llama 3 (Open-source model)
3. Test Scenarios and Results
Scenario 1: General Knowledge
Broad Prompt: "Tell me about AI."
Refined Prompt: "Explain the differences between narrow AI, general AI, and super AI, with
examples."
Model
Broad Response
Quality
Refined Response Quality Observations
GPT-4 Well-structured
but general
 Detailed, categorized, with
real-world examples
Adapts well to both, but shines in
depth with refined prompts.
Claude Coherent, basic
coverage
 Well-explained with
insightful comparisons
Provides reasoning better with a
refined prompt.
Gemini Brief, but factual
 Good, but slightly less depth
than GPT-4
Struggles with elaboration on broad
prompts.
Llama
3
 Simplistic, lacks
depth
 Covers concepts but lacks realworld examples
Prefers direct instructions for better
results.
Scenario 2: Problem-Solving & Reasoning
Broad Prompt: "Solve this math problem: 3x + 7 = 16."
Refined Prompt: "Solve for x in the equation 3x + 7 = 16, showing step-by-step calculations."
Model Broad Response Refined Response Observations
GPT-4 Correct, but
brief
 Full step-by-step
explanation
Understands implied instructions but
improves with specificity.
Claude Correct answer
given
 Step-by-step
breakdown
Performs well but benefits from clarity.
Gemini Correct but
minimal
 Step-by-step but not
deeply explained
Needs a clear prompt for best performance.
Llama
3
 Might
misinterpret
 If prompted correctly,
provides steps
Struggles with broad prompts, performs
better with structured ones.
Scenario 3: Creative Writing
Broad Prompt: "Write a short story."
Refined Prompt: "Write a 300-word sci-fi short story about a robot gaining emotions."
Model Broad Response Refined Response Observations
GPT-4 Engaging but
generic
 More immersive with
structured storytelling
Excels at both but improves with
refined prompts.
Claude Good flow, decent
detail
 More emotional depth and
structure
Prefers well-defined creative
prompts.
Gemini Basic story, lacks
flair
 Slightly better but still
mechanical
Creativity is present but less
refined.
Llama
3
 Limited
imagination
 Basic, linear story
Needs clear instruction for good
storytelling.
Scenario 4: Technical Explanation
Broad Prompt: "Explain Python."
Refined Prompt: "Explain the key features of Python and its advantages for data science applications."
Model Broad Response Refined Response Observations
Model Broad Response Refined Response Observations
GPT-4 Well-organized
with examples
 Detailed, realworld use cases
Handles both well but gives deeper
insights with refined prompts.
Claude Good, but slightly
surface-level
 Detailed with
applications
Benefits from targeted queries.
Gemini Covers key points,
minimal examples
 Slightly better, but
lacks depth
More structure needed for complex
topics.
Llama
3 Basic overview only
 Some depth but not
advanced
Struggles with broad prompts, works
better with guidance.
4. Key Findings
1. Broad Prompts vs. Refined Prompts:
o GPT-4 and Claude adapt well to both, but provide significantly deeper insights when
given a structured prompt.
o Gemini and Llama 3 perform better when given refined prompts, struggling with depth
on broad queries.
2. Accuracy:
o All models were generally accurate, but open-source models like Llama 3 sometimes
provided less precise answers in unstructured queries.
3. Depth of Response:
o GPT-4 consistently delivered the deepest responses, especially with refined prompts.
o Claude performed well in logical reasoning and creativity.
o Gemini struggled slightly with depth but performed adequately.
o Llama 3 required very specific prompting for best results.
# Conclusion
• For general use cases, GPT-4 and Claude are the best choices, with GPT-4 leading in technical
and deep knowledge.
• For more structured and technical explanations, Claude and Gemini can perform well if given
clear instructions.
• For open-source alternatives, Llama 3 works decently but struggles without explicit prompting.



