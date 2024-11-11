---
theme: seriph
title: LLM 101
info: |
  ## LLM 101

  Presentation about Large Language Models from a non-AI developer
class: text-center
drawings:
  persist: false
mdc: true
overviewSnapshots: true
favicon: "https://github.com/1995parham-me.png"
hideInToc: true
---

## LLM 101

Presentation about **Large Language Models** from a non-AI developer

<div class="abs-br m-6 flex">
  <a href="https://github.com/1995parham-teaching/llm101" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---

<Toc />

---

# Introduction

An LLM is a neural network designed to understand, generate, and respond to human-like text. These models are deep
neural networks trained on massive amounts of text data, sometimes encompassing large portions of the entire publicly
available text on the internet.

The "large" in "large language model" refers to both the **model's size** in terms of parameters and the **immense dataset**
on which it's trained.

---

LLMs utilize an architecture called the _transformers_; which allows them to pay selective attention to different parts
of the input when making predictions, making them especially adept at handling the nuances and complexities of human
language.

Since LLMs are capable of _generating_ text, LLMs are also often referred to as a form of generative artificial
intelligence, often abbreviated as **generative AI** or **GenAI**.

---

# Why we should build our own LLMs?

Research has shown that when it comes to modeling performance, custom-built LLMs (those are tailored for specific tasks or
domains) can outperform general-purpose LLMs.

---

LLM is trained on a large, diverse dataset to develop a board understanding of language. This pre-trained model then
serve as a foundational resource that can be further refined through fine-tuning, a process the model is specially
trained on a narrower dataset that is more specific to particular tasks or domains.

<img src="./img/llm-training.png" alt="llm-training" class="rounded mx-auto d-block shadow h-60">

---

# What is Ollama?

[Ollama](https://ollama.com/) stands for (Omni-Layer Learning Language Acquisition Model), a novel approach to machine learning
that promises to redefine how we perceive language acquisition and natural language processing. At its core,
Ollama is a groundbreaking platform that **democratizes access to large language models (LLMs)
by enabling users to run them locally on their machines**.
