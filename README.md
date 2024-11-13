# AI Chatbot Grading Results

This is a collection of the physics problems, mark scheme, results and responses gathered in an investigation of test how well large language models would be able to grade undergraduate physics solutions. We do this through testing how well LLM-based AI chatbots are able to grade physics solutions and compare them to human graders. The following LLMs are tested: GPT-4, GPT-4o, Gemini 1.5 Pro, Claude 3.5 Sonnet. All responses, problems and mark scheme are written and input in LaTeX. 

In this repository, you can find 4 different contents:

1. Physics problem dataset and mark scheme
2. Generated solutions by GPT-4 (to the problem dataset)
3. Grading done by each LLM model.
4. Human grading values
5. Prompts used for grading

## Physics Problem Dataset + Mark Scheme
The problem data set consists of 30 questions in three topics (Classical Mechanics - CM, Quantum Mechanics - QM, Electromagnetic Theory - EM). These are used to generate solutions and grade the solutions. Both AI and Human graders use the mark scheme when grading. Some problems have a corresponding figure which are also included here. 

## Generated GPT-4 Solutions
GPT-4 was asked to generate 90 solutions to the physics problems in the dataset - 3 solutions for each problem. The solutions stored are given in their LaTeX forms, they are also sorted by topic.

## LLM Grading 
Each TeX file stores the responses of LLMs to grading prompts. This includes the marks given to each solution. The responses are sorted by the LLM model, grading zero-shot or with a mark scheme, and the physics topic being graded (CM, QM, EM).

## Human Grading
Contained are spreadsheets showing the marks assigned by human graders to each of the generated solutions. Graders have been anonymized.

## Grading Prompts
These are the raw prompts used and input into each AI chatbot which gives instructions for grading solutions. For physics problems which have a corresponding figure, the figure is also input with the corresponding grading prompt.
