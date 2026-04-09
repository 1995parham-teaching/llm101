# Large Language Models 101

> An introduction to LLMs by a non-AI developer.

A short, opinionated tour of Large Language Models for software engineers who
want a working mental model without diving into the math. Built with
[Slidev](https://sli.dev/).

## Topics

1. What an LLM actually is (and what "large" means)
2. Tokens, context windows, and why they matter for cost & latency
3. Transformers and attention — the one-slide version
4. Pre-training vs fine-tuning vs RAG vs prompting — picking the right tool
5. Prompt engineering basics
6. Tool / function calling and agents
7. Running LLMs locally with [Ollama](https://ollama.com/)
8. LLM as a service — hosted APIs and trade-offs
9. Limitations: hallucinations, prompt injection, knowledge cutoff

## Run locally

```sh
npm install
npm run dev
```

Then open <http://localhost:3030>. Edit [`slides.md`](./slides.md) and changes
hot-reload.

## Export to PDF

```sh
npm run export
```

Produces `slides-export.pdf`. See the [Slidev export
docs](https://sli.dev/guide/exporting) for options.

## Deployment

Pushes to `main` are deployed to GitHub Pages by
[`.github/workflows/deploy.yaml`](./.github/workflows/deploy.yaml).

## Credits & further reading

- Sebastian Raschka, _Build a Large Language Model (From Scratch)_ — the
  framing in the intro borrows from this book.
- [Slidev documentation](https://sli.dev/)
- [Ollama documentation](https://docs.ollama.com/)
