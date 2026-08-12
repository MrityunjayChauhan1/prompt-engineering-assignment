# Zero-Shot, One-Shot & Few-Shot Prompting

## 1. Zero-Shot Prompting

### Meaning
Zero-Shot Prompting means asking an AI to perform a task without providing any examples.

### Example
Prompt:
"Translate this sentence into Hindi: I am learning Java."

The AI directly understands the task.

### Real Use
Useful when the task is simple and clearly defined.

---

## 2. One-Shot Prompting

### Meaning
One-Shot Prompting means providing one example to the AI before asking it to perform a similar task.

### Example

Example:
"Happy" → "Sad"

Now:
"Hot" → ?

The AI understands the expected pattern from one example.

### Real Use
Useful when you want the AI to follow a specific pattern.

---

## 3. Few-Shot Prompting

### Meaning
Few-Shot Prompting means providing multiple examples before asking the AI to perform a task.

### Example

"Java is easy" → Positive  
"Java is difficult" → Negative  
"I love coding" → Positive  

Now classify:
"I hate debugging."

The AI uses the examples to understand the pattern.

### Real Use
Useful for classification, formatting, and tasks that require a specific pattern.

---

## Quick Comparison

| Technique | Number of Examples | Main Idea |
|-----------|-------------------|-----------|
| Zero-Shot | 0 | Direct instruction |
| One-Shot | 1 | Learn from one example |
| Few-Shot | 2+ | Learn from multiple examples |

## Easy Way to Remember

- Zero-Shot = 0 examples
- One-Shot = 1 example
- Few-Shot = Few examples
