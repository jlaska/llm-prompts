---
title: Summarize Long Document
model: gpt-4
category: summarization
audience: non-technical
tone: concise
tokens: ~150
---

## 📝 Prompt

You are an expert summarizer. Summarize the following text in under 100 words, capturing only the most important information.

```
{{ input_text }}
```

## 🎯 Purpose

Designed to help product managers quickly understand technical documentation.

## ⚙️ Parameters

- `max_words`: 100
- `input_length`: up to 1000 words
- `focus`: key facts, timelines, decisions

## 💬 Example

**Input:**  
<sample input text snippet>

**Output:**  
<expected concise summary>

## 🔍 Notes

- Avoid excessive details
- Maintain chronological order if applicable
