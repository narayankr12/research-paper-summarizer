[README (1).md](https://github.com/user-attachments/files/29709701/README.1.md)
# Research Paper Summarizer

Paste a research paper (or upload a PDF/txt) and get a clean, structured digest — abstract, methodology, key findings, limitations, and conclusion — in plain language. Built for reading papers in minutes instead of hours.

## Live demo

👉 [Open the app](https://summarizzerrer.netlify.app/)

## Features

* Paste text or drop a `.pdf` / `.txt` file — any length, long papers are read section by section
* Plain-language summary plus structured cards: abstract, methodology, findings, limitations, conclusion
* Key terms worth knowing, pulled straight from the paper
* Day / night reading mode
* Copy digest, download as Markdown, or print
* Recent digests saved locally in your browser ("shelf")

## How it works

The page is a single static HTML file — no build step, no backend to host. AI summarization runs through [Groq](https://groq.com)'s API, called via a small Cloudflare Worker proxy so the API key never lives in the browser or in this repo.

## Tech

* Vanilla HTML/CSS/JS
* [pdf.js](https://mozilla.github.io/pdf.js/) for in-browser PDF text extraction
* Groq (Llama 3.3 / 3.1) for summarization, via a Cloudflare Worker proxy

## Note

This tool summarizes with AI — always skim the original paper before citing anything from a digest.



deploy link = "https://summarizzerrer.netlify.app/"

