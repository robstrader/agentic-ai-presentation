---
theme: seriph
background: /images/dark-background.png
title: What is Agentic AI?
info: |
  ## What is Agentic AI?
  A presentation exploring the evolution from Transformers to Agentic AI.
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
css: unocss
---

<style>
@import './style.css';
</style>

# What is Agentic AI?

Understanding the Evolution of Modern AI

---
transition: fade-out
---

# The Journey of Modern AI

A timeline of key breakthroughs that led to Agentic AI

```mermaid {scale: 0.75}
timeline
    2017 : Attention is All You Need
         : Transformer Architecture
    2022 : ChatGPT Released
         : GPT-3.5 & LLMs
    2023 : Retrieval-Augmented Generation(RAG) Becomes Standard
         : Connecting LLMs to live data
    2024 : Agentic AI
         : AI that takes actions
```

---
transition: slide-up
---

# Transformer Architecture and Attention Mechanism

The foundation that made modern AI possible

<div class="grid grid-cols-2 gap-8">
<div>

- **June 2017**: Google researchers published "Attention is All You Need"
- **Key insight**: AI can understand relationships between *all words* simultaneously
- This "attention mechanism" helps AI understand context better

<v-click>

- **GPT** = *Generative Pre-trained Transformer*

</v-click>

<v-click>

- The output? **Embeddings**—numerical representations that capture meaning
- But what exactly goes *into* this attention mechanism? → **Tokens**

</v-click>

</div>
<div class="flex items-center justify-center">

<img src="/images/attention-mechanism.png" class="rounded-lg shadow-lg w-full" alt="Attention Mechanism visualization" />

</div>
</div>

---
transition: slide-up
---

# How LLMs Understand Language

From tokens to embeddings—what the Transformer actually processes

<div class="bg-blue-500 bg-opacity-20 rounded-lg p-3 mb-4 text-sm">
  <strong>The Flow:</strong> Text → <strong>Tokens</strong> → Transformer (Attention) → <strong>Embeddings</strong> → Meaning
</div>

<div class="grid grid-cols-2 gap-8">
<div>

### Tokens: The Input

- Remember: the Transformer needs input to process
- LLMs don't read words—they read **tokens**
- Tokens are pieces of text (words, parts of words, punctuation)
- Example: "understanding" → `["under", "stand", "ing"]`

<v-click>

- A typical prompt might be **hundreds of tokens**
- Models have token limits (context window)

</v-click>

</div>
<div>

<v-click>

### Semantic Understanding

- LLMs: understand **meaning** and relationships

</v-click>

<v-click>

<div class="mt-4 text-sm">

| Keyword Search | Semantic Understanding |
|----------------|----------------------|
| "car" ≠ "automobile" | "car" ≈ "automobile" |
| Matches exact words | Understands concepts |
| "bank" = "bank" | "river bank" ≠ "savings bank" |

</div>

</v-click>

<v-click>

<div class="mt-4 bg-green-500 bg-opacity-20 rounded-lg p-3 text-sm">
  <strong>Key Insight:</strong> LLMs convert tokens into vectors (embeddings) that capture meaning—similar concepts are "close" in this space.
</div>

</v-click>

</div>
</div>

---
transition: slide-up
---

# ChatGPT & The Rise of LLMs

When AI became accessible to everyone

<div class="grid grid-cols-2 gap-8">
<div>

- **November 2022**: ChatGPT launched to the public
- First time millions could easily chat with a state-of-the-art AI
- Reached 100 million users in just 2 months!

<v-click>

- Trained on massive amounts of text from the internet
- Can generate human-like responses to a wide range of questions

</v-click>

<v-click>

## The Limitation

- LLMs only know what they were trained on
- Can't access new information or verify facts

</v-click>

</div>
<div class="flex items-center justify-center">

<img src="/images/chatgpt-original-ui.png" class="rounded-lg shadow-lg w-full" alt="ChatGPT Original UI" />

</div>
</div>

---
transition: slide-up
---

# RAG: Retrieval-Augmented Generation

Giving AI access to external knowledge

<div class="mb-6">

**The Problem**: LLMs only know what they were trained on  
**The Solution**: Let AI search for information before answering

</div>

```mermaid {scale: 0.85}
flowchart LR
    A["🙋 Question"] --> B["🔍 Search"]
    B --> C["📄 Retrieve Info"]
    C --> D["🤖 LLM Answer"]
    D --> E["✅ Response"]
```

<v-click>

<div class="mt-6 grid grid-cols-3 gap-4 text-center">
  <div class="bg-blue-500 bg-opacity-20 rounded-lg p-4">
    <div class="font-bold">Think of it like...</div>
    <div class="text-sm">AI + Search Engine working together</div>
  </div>
  <div class="bg-green-500 bg-opacity-20 rounded-lg p-4">
    <div class="font-bold">Benefits</div>
    <div class="text-sm">Up-to-date info, cites sources</div>
  </div>
  <div class="bg-purple-500 bg-opacity-20 rounded-lg p-4">
    <div class="font-bold">Examples</div>
    <div class="text-sm">Perplexity, Bing Chat, Google AI</div>
  </div>
</div>

</v-click>

---
transition: slide-up
---

# Agentic AI

From responding → to *acting*

<div class="grid grid-cols-2 gap-8">
<div>

<v-click>

### What makes AI "Agentic"?

- **Plans**: Breaks down complex tasks into steps
- **Acts**: Uses tools (browse web, write code, send emails)
- **Decides**: Makes choices autonomously
- **Iterates**: Refines approach based on feedback

</v-click>

<v-click>

### Real Examples

- AI coding assistants writing code
- AI assistants booking travel
- AI agents researching topics
- Tools like this presentation assistant!

</v-click>

</div>
<div class="-mt-20 flex items-center justify-center">

```mermaid {scale: 0.6}
flowchart TD
    A["📋 Receive Task"] --> B["🗺️ Plan Steps"]
    B --> C["⚡ Execute Action"]
    C --> D["👀 Observe Result"]
    D --> E{"🎯 Goal Achieved?"}
    E -- "Yes" --> F["✅ Return Result"]
    E -- "No" --> B
```

<div class="text-sm opacity-80 ml-4 w-32 italic">
  The Agent Loop: Plan → Act → Observe → Repeat
</div>

</div>
</div>

---
layout: center
class: text-center
---

# Key Takeaways

<div class="grid grid-cols-4 gap-4 mt-8 text-sm">
  <div class="bg-blue-500 bg-opacity-20 rounded-lg p-4 transition-all duration-300 hover:bg-opacity-30 hover:scale-105">
    <div class="text-2xl mb-2">🧠</div>
    <div class="font-bold">Transformers</div>
    <div class="opacity-80">The architecture that understands context</div>
  </div>
  <div class="bg-green-500 bg-opacity-20 rounded-lg p-4 transition-all duration-300 hover:bg-opacity-30 hover:scale-105">
    <div class="text-2xl mb-2">💬</div>
    <div class="font-bold">LLMs</div>
    <div class="opacity-80">AI that generates human-like text</div>
  </div>
  <div class="bg-purple-500 bg-opacity-20 rounded-lg p-4 transition-all duration-300 hover:bg-opacity-30 hover:scale-105">
    <div class="text-2xl mb-2">🔍</div>
    <div class="font-bold">RAG</div>
    <div class="opacity-80">AI + Search for current info</div>
  </div>
  <div class="bg-orange-500 bg-opacity-20 rounded-lg p-4 transition-all duration-300 hover:bg-opacity-30 hover:scale-105">
    <div class="text-2xl mb-2">🤖</div>
    <div class="font-bold">Agentic AI</div>
    <div class="opacity-80">AI that plans and takes action</div>
  </div>
</div>

<div class="mt-12 opacity-90 text-lg font-light tracking-wide">
  Attention reads, LLMs write, RAG researches, but Agents <span class="font-semibold text-orange-300">do</span>.
</div>

<PoweredBySlidev mt-10 />
