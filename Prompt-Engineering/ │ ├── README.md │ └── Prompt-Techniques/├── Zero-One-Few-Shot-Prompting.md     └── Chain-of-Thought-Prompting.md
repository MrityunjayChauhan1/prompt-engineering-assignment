# Lesson 2 – Prompting Techniques

## Chain-of-Thought, ReAct & Self-Consistency

### 1. Chain-of-Thought (CoT) Prompting

**Meaning:**  
Chain-of-Thought prompting asks AI to solve a problem step by step.

**Example:**
> A product costs ₹500 and has a 10% discount. Solve it step by step.

**Answer:** ₹450

**Real Use:**  
Useful for mathematics, logical problems, and troubleshooting.

---

### 2. ReAct = Reason + Act

**Meaning:**  
ReAct combines reasoning with taking actions to solve a problem.

**Example:**
> Find the weather in Delhi and tell me whether I should carry an umbrella.

AI can reason about the task, get the required information, and give a recommendation.

**Easy Way:**
> Reason → Act → Observe → Continue

**Real Use:**  
Useful for AI agents, research, APIs, and tool usage.

---

### 3. Self-Consistency

**Meaning:**  
Self-Consistency asks AI to solve the same problem in different ways and choose the most consistent answer.

**Example:**
> What is 25 × 4?

Different approaches may give:

- 25 + 25 + 25 + 25 = 100
- 25 × 2 × 2 = 100
- 100 × 1 = 100

**Common Answer:** 100 ✅

**Real Use:**  
Useful for complex mathematical and reasoning problems.

---

## Quick Comparison

| Technique | Simple Meaning |
|-----------|----------------|
| Chain-of-Thought | Think step by step |
| ReAct | Reason + Act |
| Self-Consistency | Try multiple ways and choose the consistent answer |

## Easy Memory Trick

- **CoT → Think Step by Step**
- **ReAct → Think + Act**
- **Self-Consistency → Multiple Solutions → Common Answer**
