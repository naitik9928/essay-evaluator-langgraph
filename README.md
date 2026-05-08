# 📝 Essay Evaluation Agent

An AI-powered essay evaluation agent that uses **LangChain**, **LangGraph**, and **ChatGroq** to assess essays in parallel across clarity, depth, and language, then provides a final score and actionable feedback.

## 🚀 Features
- 🔍 Three-dimensional evaluation (clarity, depth, language)
- ⚡ Parallel processing using LangGraph workflows
- 📊 Automated scoring + final average score
- 💬 Actionable improvement feedback
- 🤖 LLM-powered with ChatGroq (Llama 3.3 70B)

## 🛠️ Tech Stack
- LangChain - Prompt templates & LLM orchestration
- LangGraph - State-based parallel workflow management
- ChatGroq - Fast LLM inference
- Pydantic - Structured output validation

## 🔄 Workflow
Input Essay → [Depth || Clarity || Language] (Parallel) → Final Evaluation → Score + Feedback
