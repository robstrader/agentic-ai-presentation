---
theme: seriph
background: https://cover.sli.dev
title: What is Agentic AI?
info: |
  ## What is Agentic AI?
  A presentation for UX/Visual Design students exploring the evolution
  from Transformers to Agentic AI.
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
---

# What is Agentic AI?

Understanding the Evolution of Modern AI

<div class="abs-br m-6 text-sm opacity-50">
  For UX/Visual Design Students
</div>

---
transition: fade-out
---

# The Journey of Modern AI

A timeline of key breakthroughs that led to Agentic AI

```mermaid {scale: 0.85}
timeline
    title Evolution of Modern AI
    2017 : Attention is All You Need
         : Transformer Architecture
    2022 : ChatGPT Released
         : GPT-3.5 & LLMs
    2023 : RAG Architecture
         : Retrieval-Augmented Generation
    2024 : Agentic AI
         : AI that takes actions
```

<v-click>

Each step built on the previous one, solving new problems and unlocking new capabilities.

</v-click>

---
transition: slide-up
---

# Transformer Architecture

The foundation that made modern AI possible

<div class="grid grid-cols-2 gap-8">
<div>

- **June 2017**: Google researchers published "Attention is All You Need"
- Introduced a new way for AI to understand language
- **Key insight**: AI can look at *all words* in a sentence at once
- This "attention mechanism" helps AI understand context better

<v-click>

- **GPT** = *Generative Pre-trained Transformer*
- Uses this architecture to generate human-like text

</v-click>

</div>
<div class="flex items-center justify-center">

<!-- Placeholder for attention visualization -->
<div class="border-2 border-dashed border-gray-400 rounded-lg p-8 text-center opacity-60">
  <div class="i-carbon-image text-4xl mb-2"></div>
  <p class="text-sm">Attention mechanism visualization</p>
  <p class="text-xs">Words connecting to related words</p>
</div>

</div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: slide-up
---

# ChatGPT & The Rise of LLMs

When AI became accessible to everyone

<div class="grid grid-cols-2 gap-8">
<div>

- **November 2022**: ChatGPT launched to the public
- First time anyone could chat with an advanced AI
- Reached 100 million users in just 2 months!

<v-click>

- **LLM** = *Large Language Model*
- Trained on massive amounts of text from the internet
- Can generate human-like responses to any question

</v-click>

<v-click>

### The Limitation

- LLMs only know what they were trained on
- Knowledge is "frozen" at a point in time
- Can't access new information or verify facts

</v-click>

</div>
<div class="flex items-center justify-center">

<!-- Placeholder for chat interface -->
<div class="border-2 border-dashed border-gray-400 rounded-lg p-6 text-center opacity-60 w-full">
  <div class="i-carbon-chat text-4xl mb-2"></div>
  <p class="text-sm">Chat interface mockup</p>
  <p class="text-xs">User asking questions, AI responding</p>
</div>

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

```mermaid {scale: 0.9}
flowchart LR
    A["🙋 User Question"] --> B["🔍 Search Knowledge Base"]
    B --> C["📄 Retrieve Relevant Info"]
    C --> D["🤖 LLM Generates Answer"]
    D --> E["✅ Response with Sources"]
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
- **Learns**: Improves based on results

</v-click>

<v-click>

### Real Examples

- GitHub Copilot building features
- AI assistants booking travel
- AI agents researching topics
- Tools like this presentation assistant!

</v-click>

</div>
<div>

```mermaid {scale: 0.75}
flowchart TD
    A["📋 Receive Task"] --> B["🗺️ Plan Steps"]
    B --> C["⚡ Execute Action"]
    C --> D["👀 Observe Result"]
    D --> E{"🎯 Goal Achieved?"}
    E -->|No| B
    E -->|Yes| F["✅ Return Result"]
```

<div class="text-center text-sm opacity-60 mt-2">
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
  <div class="bg-blue-500 bg-opacity-20 rounded-lg p-4">
    <div class="text-2xl mb-2">🧠</div>
    <div class="font-bold">Transformers</div>
    <div class="opacity-70">The architecture that understands context</div>
  </div>
  <div class="bg-green-500 bg-opacity-20 rounded-lg p-4">
    <div class="text-2xl mb-2">💬</div>
    <div class="font-bold">LLMs</div>
    <div class="opacity-70">AI that generates human-like text</div>
  </div>
  <div class="bg-purple-500 bg-opacity-20 rounded-lg p-4">
    <div class="text-2xl mb-2">🔍</div>
    <div class="font-bold">RAG</div>
    <div class="opacity-70">AI + Search for current info</div>
  </div>
  <div class="bg-orange-500 bg-opacity-20 rounded-lg p-4">
    <div class="text-2xl mb-2">🤖</div>
    <div class="font-bold">Agentic AI</div>
    <div class="opacity-70">AI that plans and takes action</div>
  </div>
</div>

<div class="mt-12 opacity-50">
  Each innovation built on the last, expanding what AI can do.
</div>

<PoweredBySlidev mt-10 />
