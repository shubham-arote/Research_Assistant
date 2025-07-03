# 🧠 Multi-Agent Research System

A lightweight, multi-agent system powered by chat models that customizes the research process.

---

## 🎯 Goal

To build a lightweight, multi-agent system around chat models that customizes the research process.

---

## 📚 Source Selection

Users can choose any set of input sources for their research.

---

## 🧭 Planning

1. **Topic Input**  
   Users provide a research topic.

2. **Team Generation**  
   The system generates a team of AI analysts, each focusing on a specific sub-topic.

3. **Human-in-the-Loop**  
   Users refine and finalize sub-topics before research begins.

---

## 🧠 LLM Utilization

- Each analyst conducts a **multi-turn interview** with an expert AI using the selected sources.
- These interviews are modeled on the approach described in the **STORM** paper.
- Internal reasoning is captured in **sub-graphs** reflecting each agent's state.

---

## 🔁 Research Process

- Expert AIs gather information in **parallel** to answer analyst questions.
- All interviews are conducted **simultaneously** using a **map-reduce** structure.

---

## 📝 Output Format

- Insights from each interview are synthesized into a **final report**.
- Output formatting is customizable using **prompt templates** for flexible report generation.

---

