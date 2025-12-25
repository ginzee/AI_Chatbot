# Career & Job Search Decision Assistant for Data Analytics  
**Author**  
Sam Ginzburg  
📧 samginzee@gmail.com  

---

## Business Problem and Motivation

Breaking into data analytics is rarely a linear process. Candidates often face ambiguous job requirements, overlapping skill expectations, unclear portfolio standards, and conflicting advice about what matters most when transitioning into analytics-focused roles.

Rather than providing generic career advice, the goal of this project is to demonstrate how a lightweight Large Language Model (LLM)–powered assistant can support **structured decision-making** across common career and job-search scenarios in data analytics, such as:

- Resume positioning for analytics roles  
- Skill prioritization (SQL, Python, BI tools, etc.)  
- Portfolio strategy and project selection  
- Interview preparation  
- Career transitions into analytics  

This project emphasizes **reasoned guidance and trade-off analysis**, not automation of hiring decisions.

---

## Project Scope

This notebook implements a conversational assistant that:

- Maintains multi-turn conversational state
- Applies consistent constraints (low temperature, bounded responses)
- Asks clarifying questions when inputs are underspecified
- Provides pragmatic, analytics-oriented career guidance

The assistant is intentionally scoped as a **decision-support prototype**, not a production chatbot or recruitment system.

---

## Methods / Skills Used

This project demonstrates the following skills and techniques:

- Python  
- OpenAI API (Chat Completions)  
- Prompt Engineering (System Prompt Design)  
- Multi-Turn Conversation State Management  
- Deterministic Response Control (Temperature & Token Limits)  
- Environment Variable Management  
- Interactive CLI-Style User Input  
- Reproducible Jupyter Notebook Workflows  

---

## Results

The assistant successfully demonstrates:

- Context-aware resume feedback  
- Structured responses to career strategy questions  
- Clarifying follow-up questions when user input is ambiguous  
- Consistent, concise outputs suitable for decision support  

Rather than optimizing for creativity, responses are deliberately constrained to emphasize **clarity, reasoning, and applicability**.

---

## Quick Glance at Results

Example: Resume bullet rewrite for a data-analyst–oriented role  

![Resume Rewrite Demo](./assets/Screenshot%202025-12-25%20at%2016.09.10.png)

---

Example: Guidance on project selection for full-time data analyst readiness  

![Project Readiness Guidance](./assets/Screenshot%202025-12-25%20at%2016.08.32.png)

---

Example: Skill prioritization discussion (SQL, Python, BI tools)  

![Skill Prioritization](./assets/Screenshot%202025-12-25%20at%2016.08.10.png)

---

## How to Run This Project

1. Clone the repository  
2. Install dependencies  
   pip install -r requirements.txt
3. Create an environment file
   cp .env.example .env
4. Add your OpenAI API key to .env
5. Open and run the notebook
   jupyter notebook notebooks/for_loop_automated_AI_chatbot_Career.ipynb
   The .env file is excluded from version control.

## Limitations

- This assistant does not provide guarantees about hiring outcomes
- It does not replace professional career coaching or recruitment processes
- Guidance is generalized and should be adapted to individual circumstances
