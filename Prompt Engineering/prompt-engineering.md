# Prompt Engineering for AWS Certified AI Practitioner (AIF-C01

## 1. What is Prompt Engineering?
> Prompt engineering = Writing better instructions for AI to get better answers.

### Example
Prompt:
`Explain EC2 in simple words.`

Better prompt = Better output.

---

## 2. Why does it matter?
It helps AI:
- Give **accurate answers**
- Understand context better
- Reduce wrong answers (**hallucination**)
- Follow required format

### Example
Instead of asking:  
`Tell me about AWS`

Ask:  
`Explain AWS Lambda in 3 simple points.`

---

## 3. Zero-shot Prompting
AI is asked directly **without examples**.

### Example
> Classify this review as positive or negative.

No sample is provided.

**Simple meaning:**  
➡️ Ask AI directly.

---

## 4. Few-shot Prompting
You give AI **some examples first**.

### Example
- EC2 → Compute  
- S3 → Storage  
- RDS → ?

AI learns pattern and answers:

> Database

**Simple meaning:**  
➡️ Teach AI using examples.

---

## 5. Chain-of-Thought Prompting
Ask AI to think **step by step** before answering.

### Example
> Solve this problem step by step.

Useful for:
- Math
- Logic
- Complex reasoning

**Simple meaning:**  
➡️ Break big problem into small steps.

---

## 6. Role Prompting
Tell AI what role to act as.

### Example
> Act as an AWS trainer and explain VPC.

Now AI responds like a trainer.

**Simple meaning:**  
➡️ Give AI a role/personality.

---

# Quick Exam Revision Table

| Term | Meaning |
|------|---------|
| Prompt Engineering | Writing good AI instructions |
| Zero-shot | No examples |
| Few-shot | With examples |
| Chain-of-Thought | Step-by-step reasoning |
| Role Prompting | Assign AI a role |

## One-line Memory Trick
- **Zero = 0 examples**
- **Few = Some examples**
- **CoT = Think step-by-step**
- **Role = Act like someone**

This level is usually enough for **AIF-C01 exam**.
