---
title: "best-ai-tools-for-teachers-2026"
description: "Best open source AI tools for teachers in 2026: verified GitHub repos for tutoring, transcription, OCR, translation, and self-hosted classroom AI."
icon: 📋
category: education
---

# Best AI Tools for Teachers 2026

[![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@main/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Topics](https://img.shields.io/github/stars/GagnDeep/awesome-best-ai-tools-for-teachers-2026?style=social)

> This curated list of the best AI tools for teachers in 2026 focuses only on open source projects that exist as public GitHub repositories. Every entry below has a GitHub URL, visible repository metadata, and a practical classroom use case such as tutoring, transcription, OCR, translation, or self-hosted course assistants.

## Table of Contents
- [TL;DR](#tldr)
- [Why This List](#why-this-list)
- [Open Source Tools](#open-source-tools)
- [FAQ](#faq)
- [Contributing](#contributing)
- [License](#license)

## TL;DR
- `HKUDS/DeepTutor` is the strongest teacher-facing AI tutor in this list if you want a document-grounded learning assistant with practice generation.
- `ggml-org/whisper.cpp` and `SYSTRAN/faster-whisper` are the most practical open source speech-to-text picks for lecture capture, accessibility, and note generation.
- `PaddlePaddle/PaddleOCR` and `ocrmypdf/OCRmyPDF` are the best open source OCR choices for turning worksheets, scans, and PDFs into searchable classroom material.
- `LibreTranslate/LibreTranslate`, `coqui-ai/TTS`, and `rhasspy/piper` are strong building blocks for multilingual and accessibility-focused teaching workflows.
- `langgenius/dify`, `open-webui/open-webui`, and `Mintplex-Labs/anything-llm` are the best self-hosted hubs for building school-safe AI assistants around course documents.

## Why This List
Most lists about AI for educators mix proprietary SaaS, affiliate-driven recommendations, and tools that are impossible to audit or self-host. This list is intentionally narrower: it tracks only GitHub-native, open source repositories that teachers, schools, and instructional designers can inspect, fork, self-host, and adapt. That matters for privacy, budget control, accessibility, and long-term curriculum ownership.

Gap note: dedicated teacher-first AI quiz-generation and grading repositories are still thin on GitHub. I found fewer than 5 actively maintained, clearly documented repos that met the same quality bar as the projects below, so this list focuses on stronger adjacent workflows instead of padding weak matches.

## Open Source Tools

### AI Tutoring and Study Companions

#### [DeepTutor](https://github.com/HKUDS/DeepTutor)
> **Description:** DeepTutor positions itself as an AI-powered personalized learning assistant rather than a generic chatbot. The README emphasizes four pillars: massive document knowledge Q&A, interactive learning visualization, knowledge reinforcement through practice generation, and deep research support. In practice, that makes it useful for teachers who want to upload textbooks, reference exams, or unit notes and turn them into explainers and targeted exercises. Its GitHub metadata shows an AGPL-3.0 license, about 10.9k stars, Python as the primary language, and a last commit date of Mar 30, 2026.

- **GitHub:** [github.com/HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)
- **Stars:** 10.9k ⭐
- **Language:** Python
- **License:** AGPL-3.0
- **Last Commit:** Mar 30, 2026
- **Category:** tutoring, rag, personalized-learning
- **Best for:** Building a self-hosted AI tutor around your own course documents

---

#### [ChatTutor](https://github.com/HugeCatLab/ChatTutor)
> **Description:** ChatTutor is one of the few repos in this space that explicitly frames itself as an AI teacher. Its README focuses on visual and interactive tutoring, especially for STEM instruction, where plain text explanations are often not enough. The project adds a whiteboard-style interface so an assistant can illustrate concepts instead of only answering in chat. That makes it interesting for teachers who want a more classroom-like tutoring interaction for math, science, and diagram-heavy lessons. GitHub shows roughly 982 stars, Vue as the main language, AGPL-3.0 licensing, and activity on Jan 9, 2026.

- **GitHub:** [github.com/HugeCatLab/ChatTutor](https://github.com/HugeCatLab/ChatTutor)
- **Stars:** 982 ⭐
- **Language:** Vue
- **License:** AGPL-3.0
- **Last Commit:** Jan 9, 2026
- **Category:** tutoring, visual-learning, stem
- **Best for:** Visual AI tutoring for STEM-heavy explanations

---

#### [Anki MCP Server](https://github.com/ankimcp/anki-mcp-server)
> **Description:** This project connects AI assistants to Anki through the Model Context Protocol. The README is concrete about what that means: agents can list decks, create or edit notes, manage media, and work with flashcards programmatically. For teachers, that is useful when turning lesson objectives, reading packets, or vocabulary lists into spaced-repetition study material without locking students into a proprietary workflow. The repo is openly licensed under AGPL-3.0-or-later, uses TypeScript, has about 200 stars, and showed activity on Mar 28, 2026.

- **GitHub:** [github.com/ankimcp/anki-mcp-server](https://github.com/ankimcp/anki-mcp-server)
- **Stars:** 200 ⭐
- **Language:** TypeScript
- **License:** AGPL-3.0-or-later
- **Last Commit:** Mar 28, 2026
- **Category:** flashcards, mcp, spaced-repetition
- **Best for:** Automating Anki deck creation from lesson materials

---

#### [Study Buddy](https://github.com/michael-borck/study-buddy)
> **Description:** Study Buddy is a local-first desktop tutor that runs on a teacher or student machine and defaults to private, local inference. The README highlights personalized tutorials, chat-based follow-up questions, offline use after setup, and educator deployment options for school environments. It is a good fit for districts that want an approachable desktop interface without defaulting to cloud accounts or student data export. GitHub lists it as MIT-licensed, primarily TypeScript, with about 10 stars, and the topic page shows activity on Mar 1, 2026.

- **GitHub:** [github.com/michael-borck/study-buddy](https://github.com/michael-borck/study-buddy)
- **Stars:** 10 ⭐
- **Language:** TypeScript
- **License:** MIT
- **Last Commit:** Mar 1, 2026
- **Category:** offline-ai, desktop-app, tutoring
- **Best for:** Private local tutoring on teacher or student devices

---

#### [AI-Tutor](https://github.com/hari7261/AI-Tutor)
> **Description:** AI-Tutor is a small but relevant repo for educators who want a simple local tutoring assistant. The README emphasizes step-by-step explanations, custom MCQ generation, and fully local operation through Ollama, which keeps data off third-party services. It does not have the ecosystem size of DeepTutor or Dify, but it is easy to understand and aligned with a privacy-first classroom workflow. GitHub shows an MIT license, Python as the primary language, about 12 stars, and recent activity on Jul 4, 2025.

- **GitHub:** [github.com/hari7261/AI-Tutor](https://github.com/hari7261/AI-Tutor)
- **Stars:** 12 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Jul 4, 2025
- **Category:** offline-ai, ollama, quizzes
- **Best for:** Lightweight local tutoring with quick quiz generation

---

### Speech, Transcription, and Accessibility

#### [whisper.cpp](https://github.com/ggml-org/whisper.cpp)
> **Description:** whisper.cpp is one of the most practical open source speech-to-text tools for teachers because it ports Whisper to efficient local C/C++ inference. Its README and topic description make the value clear: fast local transcription without having to push recordings to a hosted API. That is useful for lecture capture, classroom discussion notes, student oral reflections, and accessibility workflows. GitHub topic metadata shows about 48.1k stars, C++ as the primary language, a last commit on Mar 29, 2026, and the project is widely used as a foundation for offline transcription tools.

- **GitHub:** [github.com/ggml-org/whisper.cpp](https://github.com/ggml-org/whisper.cpp)
- **Stars:** 48.1k ⭐
- **Language:** C++
- **License:** MIT
- **Last Commit:** Mar 29, 2026
- **Category:** speech-to-text, offline, accessibility
- **Best for:** Local transcription of lectures and classroom audio

---

#### [faster-whisper](https://github.com/SYSTRAN/faster-whisper)
> **Description:** faster-whisper is a performance-focused Whisper implementation built on CTranslate2. The project is especially useful when teachers or school IT teams need a Python-native transcription engine that is faster and easier to integrate into note-taking, summarization, or media-processing pipelines. Compared with consumer lecture-transcription products, it stays inspectable and self-hostable. GitHub topic metadata lists about 21.8k stars, Python as the primary language, MIT licensing, and a last update on Nov 19, 2025.

- **GitHub:** [github.com/SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper)
- **Stars:** 21.8k ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Nov 19, 2025
- **Category:** speech-to-text, python, whisper
- **Best for:** Fast transcription pipelines for recorded lessons and videos

---

#### [whisperX](https://github.com/m-bain/whisperX)
> **Description:** whisperX extends Whisper-style transcription with word-level timestamps and diarization, which makes it particularly valuable in education. A normal transcript is helpful; a timestamped transcript that can separate speakers is much better for seminars, interviews, feedback sessions, and discussion-based classes. The README centers those strengths, and that makes whisperX a better fit than baseline transcription when teachers need searchable, reviewable classroom audio. GitHub topic metadata shows about 21k stars, Python as the primary language, BSD-2-Clause licensing, and recent activity on Mar 25, 2026.

- **GitHub:** [github.com/m-bain/whisperX](https://github.com/m-bain/whisperX)
- **Stars:** 21k ⭐
- **Language:** Python
- **License:** BSD-2-Clause
- **Last Commit:** Mar 25, 2026
- **Category:** diarization, timestamps, speech-to-text
- **Best for:** Timestamped and speaker-aware transcripts for class discussions

---

#### [Handy](https://github.com/cjpais/Handy)
> **Description:** Handy is an end-user speech-to-text desktop app rather than only a developer toolkit. The README is explicit about its goals: free, open source, private, extensible, and simple. It is built as a cross-platform app so users can press a shortcut, speak, and insert text into any field without sending audio to the cloud. That makes it relevant for teachers handling accommodations, quick dictation, lesson drafting, or accessible classroom computing. GitHub shows an MIT license, roughly 9.9k stars, TypeScript as the top language, and topic activity on Mar 29, 2026.

- **GitHub:** [github.com/cjpais/Handy](https://github.com/cjpais/Handy)
- **Stars:** 9.9k ⭐
- **Language:** TypeScript
- **License:** MIT
- **Last Commit:** Mar 29, 2026
- **Category:** dictation, offline, accessibility
- **Best for:** Cross-platform offline dictation for teachers and students

---

#### [Vosk API](https://github.com/alphacep/vosk-api)
> **Description:** Vosk is a mature offline speech recognition stack that supports phones, Raspberry Pi devices, and servers. Its README and topic page emphasize local speech recognition across multiple programming environments, which is useful for building classroom tools, language labs, kiosk setups, or accessibility aides that cannot rely on constant internet access. It is less turnkey than Handy but more flexible for custom school deployments. GitHub topic metadata shows about 14.5k stars, Jupyter Notebook as the detected primary language, Apache-2.0 licensing, and activity on Feb 22, 2026.

- **GitHub:** [github.com/alphacep/vosk-api](https://github.com/alphacep/vosk-api)
- **Stars:** 14.5k ⭐
- **Language:** Jupyter Notebook
- **License:** Apache-2.0
- **Last Commit:** Feb 22, 2026
- **Category:** offline-speech, multilingual, raspberry-pi
- **Best for:** Building custom offline speech features for classroom tools

---

### OCR and Document Understanding

#### [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)
> **Description:** PaddleOCR is one of the strongest document-processing repositories in this list because it is not limited to basic text extraction. The README and topic description position it as a toolkit that turns PDFs and images into structured data for AI workflows and supports more than 100 languages. For teachers, that means converting worksheets, textbook scans, handouts, and archived material into searchable or reusable content. GitHub topic metadata shows roughly 73.2k stars, Python as the main language, Apache-2.0 licensing, and a last commit on Mar 26, 2026.

- **GitHub:** [github.com/PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)
- **Stars:** 73.2k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** Mar 26, 2026
- **Category:** ocr, pdf, multilingual
- **Best for:** High-volume OCR and structured extraction from teaching materials

---

#### [Tesseract](https://github.com/tesseract-ocr/tesseract)
> **Description:** Tesseract remains the baseline open source OCR engine that many education workflows still depend on. The repo is focused on OCR itself rather than teacher UX, but it is valuable because it is stable, widely integrated, and works as the foundation for many document pipelines. Teachers and school technologists still use it to process scans, legacy PDFs, and digitized worksheets. GitHub topic data shows about 73.2k stars, C++ as the primary language, Apache-2.0 licensing, and a last commit on Mar 24, 2026.

- **GitHub:** [github.com/tesseract-ocr/tesseract](https://github.com/tesseract-ocr/tesseract)
- **Stars:** 73.2k ⭐
- **Language:** C++
- **License:** Apache-2.0
- **Last Commit:** Mar 24, 2026
- **Category:** ocr-engine, document-processing, scanning
- **Best for:** Core OCR infrastructure for self-hosted document workflows

---

#### [Umi-OCR](https://github.com/hiroi-sora/Umi-OCR)
> **Description:** Umi-OCR is closer to a teacher-ready app than a backend library. The README highlights offline OCR, screenshot OCR, batch image import, PDF recognition, QR code support, formula recognition, and multilingual libraries. That combination makes it useful when teachers need a no-cloud desktop utility for converting screenshots, scanned worksheets, or PDF packets into editable text. GitHub shows an MIT license, around 41.4k stars, Python as the main language, and recent activity on Nov 20, 2025.

- **GitHub:** [github.com/hiroi-sora/Umi-OCR](https://github.com/hiroi-sora/Umi-OCR)
- **Stars:** 41.4k ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Nov 20, 2025
- **Category:** offline-ocr, desktop-tool, pdf
- **Best for:** Teacher-friendly OCR of screenshots, scans, and PDFs

---

#### [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF)
> **Description:** OCRmyPDF focuses on a practical classroom problem: scanned PDFs that cannot be searched, highlighted, or copied. The README is very clear that the tool adds an OCR text layer, preserves layout, supports multiple languages, and can repair or normalize common PDF issues in a scriptable workflow. For schools digitizing reading packs, archived assessments, or photocopied documents, that is extremely useful. GitHub shows about 32.1k stars, Python as the primary language, MPL-2.0 licensing, and activity through Dec 15, 2025.

- **GitHub:** [github.com/ocrmypdf/OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF)
- **Stars:** 32.1k ⭐
- **Language:** Python
- **License:** MPL-2.0
- **Last Commit:** Dec 15, 2025
- **Category:** pdf, searchable-pdf, ocr
- **Best for:** Making scanned classroom PDFs searchable and copyable

---

#### [EasyOCR](https://github.com/JaidedAI/EasyOCR)
> **Description:** EasyOCR is a popular deep-learning OCR library that trades some end-user polish for broad language support and flexible integration. The README and topic page emphasize ready-to-use OCR across more than 80 languages and major writing systems, making it a good choice when teachers or edtech teams need to extract text from multilingual classroom content, posters, slides, or visual resources. GitHub topic metadata shows roughly 29.2k stars, Python as the primary language, Apache-2.0 licensing, and activity on Dec 5, 2025.

- **GitHub:** [github.com/JaidedAI/EasyOCR](https://github.com/JaidedAI/EasyOCR)
- **Stars:** 29.2k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** Dec 5, 2025
- **Category:** multilingual-ocr, deep-learning, image-text
- **Best for:** OCR across multilingual classroom visuals and resources

---

### Voice, TTS, and Multilingual Support

#### [TTS](https://github.com/coqui-ai/TTS)
> **Description:** Coqui TTS is one of the largest open source text-to-speech projects available on GitHub. The README describes it as a deep-learning toolkit for production-grade speech synthesis, voice conversion, and multi-speaker TTS. For teachers, it is especially relevant in accessibility and language-learning workflows: reading passages aloud, producing audio versions of content, or prototyping voice-enabled learning tools. GitHub shows about 44.2k stars, Python as the primary language, MPL-2.0 licensing, and the last visible update on Aug 16, 2024.

- **GitHub:** [github.com/coqui-ai/TTS](https://github.com/coqui-ai/TTS)
- **Stars:** 44.2k ⭐
- **Language:** Python
- **License:** MPL-2.0
- **Last Commit:** Aug 16, 2024
- **Category:** text-to-speech, accessibility, language-learning
- **Best for:** Generating classroom audio and accessibility voice output

---

#### [OpenVoice](https://github.com/myshell-ai/OpenVoice)
> **Description:** OpenVoice focuses on instant voice cloning and multilingual speech generation. The README highlights accurate tone cloning, fine-grained style control, cross-lingual voice cloning, and MIT-licensed commercial use. In a teaching context, that makes it more specialized than standard TTS: useful for localized audio content, teacher-voiced materials, and experimental language-learning assets where consistent voice identity matters. GitHub shows about 35.8k stars, Python as the primary language, MIT licensing, and a last commit on Apr 19, 2025.

- **GitHub:** [github.com/myshell-ai/OpenVoice](https://github.com/myshell-ai/OpenVoice)
- **Stars:** 35.8k ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Apr 19, 2025
- **Category:** voice-cloning, multilingual, tts
- **Best for:** Creating multilingual or teacher-voiced audio materials

---

#### [LibreTranslate](https://github.com/LibreTranslate/LibreTranslate)
> **Description:** LibreTranslate is not a tutoring app, but it solves a common classroom AI need: self-hosted machine translation without routing text through proprietary providers. The README is explicit that it is free, open source, self-hosted, and powered by open translation models instead of Google or Azure. That matters for multilingual classrooms, translated handouts, and accessibility support. GitHub shows about 13.5k stars, Python as the main language, AGPL-3.0 licensing, and visible activity through Dec 23, 2025.

- **GitHub:** [github.com/LibreTranslate/LibreTranslate](https://github.com/LibreTranslate/LibreTranslate)
- **Stars:** 13.5k ⭐
- **Language:** Python
- **License:** AGPL-3.0
- **Last Commit:** Dec 23, 2025
- **Category:** translation, multilingual, self-hosted
- **Best for:** Self-hosted translation for multilingual teaching workflows

---

#### [Piper](https://github.com/rhasspy/piper)
> **Description:** Piper is a fast local neural text-to-speech system designed for on-device use. That makes it a practical choice for schools that need offline TTS without recurring API costs. While the repository has been archived, it remains useful because the code is still public, MIT-licensed, and widely referenced in local voice stacks. For teachers, Piper is best viewed as infrastructure for local reading support, kiosk devices, assistive tools, or classroom assistants. GitHub shows about 10.3k stars, C++ as the primary language, and the archive notice dated Oct 6, 2025.

- **GitHub:** [github.com/rhasspy/piper](https://github.com/rhasspy/piper)
- **Stars:** 10.3k ⭐
- **Language:** C++
- **License:** MIT
- **Last Commit:** Oct 6, 2025
- **Category:** local-tts, offline, assistive-tech
- **Best for:** Offline text-to-speech on local devices and kiosks

---

#### [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx)
> **Description:** sherpa-onnx is a broader speech stack that includes speech-to-text, text-to-speech, diarization, and voice activity detection across many platforms. It is more engineering-heavy than teacher-facing, but it is valuable when schools or developers want one open source package to power voice features in classroom apps, Raspberry Pi devices, or local assistant hardware. GitHub shows Apache-2.0 licensing, about 9k stars, C++ as the detected main language, and visible activity through Dec 17, 2025.

- **GitHub:** [github.com/k2-fsa/sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx)
- **Stars:** 9k ⭐
- **Language:** C++
- **License:** Apache-2.0
- **Last Commit:** Dec 17, 2025
- **Category:** speech-stack, on-device, multilingual
- **Best for:** Building local voice features into school software or devices

---

### Self-Hosted Course Assistants and RAG Workspaces

#### [Dify](https://github.com/langgenius/dify)
> **Description:** Dify is one of the most mature open source platforms for building AI workflows and assistants around your own data. The project is not education-specific, but that is part of its value: teachers can use it to create course bots, reading assistants, FAQ helpers, and lesson-prep workflows without relying on a managed SaaS builder. The topic page positions it as production-ready agentic workflow software. GitHub topic metadata shows about 135k stars, TypeScript as the primary language, Apache-2.0 licensing, and activity on Mar 29, 2026.

- **GitHub:** [github.com/langgenius/dify](https://github.com/langgenius/dify)
- **Stars:** 135k ⭐
- **Language:** TypeScript
- **License:** Apache-2.0
- **Last Commit:** Mar 29, 2026
- **Category:** rag, workflow, self-hosted
- **Best for:** Building school-owned AI assistants and workflows

---

#### [LangChain](https://github.com/langchain-ai/langchain)
> **Description:** LangChain is the most widely adopted open source framework in this list for chaining LLM calls, retrieval, tools, and agent logic. It is not a teacher product by itself, but many education prototypes and internal school tools are built on it. For teachers and technical teams, LangChain matters because it can power curriculum chatbots, rubric assistants, reading guides, and document-grounded helpers around local or hosted models. GitHub topic metadata shows roughly 132k stars, Python as the primary language, MIT licensing, and activity on Mar 29, 2026.

- **GitHub:** [github.com/langchain-ai/langchain](https://github.com/langchain-ai/langchain)
- **Stars:** 132k ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Mar 29, 2026
- **Category:** framework, rag, agents
- **Best for:** Developing custom teacher or district AI workflows

---

#### [Open WebUI](https://github.com/open-webui/open-webui)
> **Description:** Open WebUI is a teacher-friendly interface layer for local and remote models, especially when paired with Ollama or OpenAI-compatible backends. Its README and topic description emphasize a user-friendly AI interface with self-hosted deployment, knowledge-base support, and broad model compatibility. For a school setting, that makes it a practical front end for a document-grounded class assistant without writing a full custom app. GitHub topic metadata shows about 129k stars, Python as the primary language, BSD-3-Clause licensing, and activity on Mar 29, 2026.

- **GitHub:** [github.com/open-webui/open-webui](https://github.com/open-webui/open-webui)
- **Stars:** 129k ⭐
- **Language:** Python
- **License:** BSD-3-Clause
- **Last Commit:** Mar 29, 2026
- **Category:** webui, self-hosted, knowledge-base
- **Best for:** Deploying a simple AI portal for teachers and students

---

#### [RAGFlow](https://github.com/infiniflow/ragflow)
> **Description:** RAGFlow is a retrieval-first platform built for document understanding and knowledge-grounded AI. The README and topic page frame it as a strong context layer for LLMs, combining RAG with agent capabilities. That maps well to school use cases where assistants must stay anchored to syllabi, handbooks, grading policies, or course packets instead of hallucinating from general web knowledge. GitHub topic metadata shows about 76.5k stars, Python as the primary language, Apache-2.0 licensing, and activity on Mar 29, 2026.

- **GitHub:** [github.com/infiniflow/ragflow](https://github.com/infiniflow/ragflow)
- **Stars:** 76.5k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** Mar 29, 2026
- **Category:** rag, document-understanding, self-hosted
- **Best for:** Document-grounded school knowledge bases and assistants

---

#### [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)
> **Description:** AnythingLLM is one of the most approachable self-hosted AI workspaces in this list. The project describes itself as an all-in-one AI productivity application with built-in RAG, agents, local-first operation, and no-code setup. For teachers, that means a relatively low-friction path to uploading policies, lesson notes, or reading packets and turning them into a searchable assistant. GitHub topic metadata shows about 57.1k stars, JavaScript as the primary language, MIT licensing, and activity on Mar 27, 2026.

- **GitHub:** [github.com/Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm)
- **Stars:** 57.1k ⭐
- **Language:** JavaScript
- **License:** MIT
- **Last Commit:** Mar 27, 2026
- **Category:** local-first, rag, no-code
- **Best for:** Quickly launching a private course assistant without much setup

---

## FAQ

### What are the best open source AI tools for teachers in 2026?
For most teachers, the strongest starting points are `DeepTutor` for tutoring, `whisper.cpp` or `faster-whisper` for transcription, `PaddleOCR` or `OCRmyPDF` for digitizing materials, and `Dify` or `Open WebUI` for self-hosted course assistants.

### Are there any truly free AI tools for teachers on GitHub?
Yes. Every project in this repository is a public GitHub repository with an open source license. Some projects may optionally connect to paid model APIs, but the repositories themselves are not proprietary SaaS products.

### Which open source AI tools help teachers create accessible classroom materials?
`whisper.cpp`, `faster-whisper`, `Handy`, `TTS`, `Piper`, and `LibreTranslate` are the strongest picks for captions, dictation, text-to-speech, and multilingual support.

### What is the best self-hosted AI assistant for school documents?
`Dify`, `RAGFlow`, `AnythingLLM`, and `Open WebUI` are the most practical choices if you want to upload syllabi, readings, policies, or handouts and build a private assistant around them.

### Which GitHub OCR tools are best for worksheets, scans, and PDFs?
`PaddleOCR` is the broadest OCR toolkit, `OCRmyPDF` is best for making scanned PDFs searchable, `Umi-OCR` is the easiest desktop-friendly option, and `EasyOCR` is a strong multilingual library.

### Why are there not more open source AI grading and quiz-generator tools in this list?
Because the GitHub ecosystem is still thin there. I found fewer than 5 repos that were both actively maintained and strong enough to recommend without reservations, so I documented the gap instead of filling the list with low-quality or abandoned projects.

### Can schools use these repositories without sending student data to the cloud?
Often yes, but it depends on deployment choices. Local-first tools like `Study Buddy`, `Handy`, `whisper.cpp`, `Piper`, and `LibreTranslate` are especially useful when privacy and offline operation matter.

## GitHub Search Queries Used

The initial narrow teacher-only searches were too sparse, so the research expanded into adjacent teacher workflows. These are the GitHub-oriented queries used:

```bash
gh search repos "ai tutor education" --match name,description,readme --sort updated --order desc
gh search repos "ai-tutor" --match name,description,topics --sort stars --order desc
gh search repos "ai-education" --match name,description,topics --sort stars --order desc
gh search repos "speech-to-text offline" --match name,description,topics --sort stars --order desc
gh search repos "ocr pdf ai" --match name,description,topics --sort stars --order desc
gh search repos "text-to-speech open source" --match name,description,topics --sort stars --order desc
gh search repos "self-hosted rag" --match name,description,topics --sort stars --order desc
gh search repos "translation self-hosted" --match name,description,topics --sort stars --order desc
gh search repos "teacher ai github" --match name,description,readme --sort updated --order desc
gh search repos "classroom ai open source" --match name,description,readme --sort updated --order desc
```

## Contributing

Contributions are welcome, but submissions must stay within the rules of this repository:

- Only submit tools that exist as public GitHub repositories.
- Every submission must include a `github.com` repository URL.
- No proprietary SaaS products, closed-source wrappers, or cloud-only services.
- Include the repo license, primary language, star count, and last commit date from GitHub.
- If a tool is teacher-adjacent rather than teacher-specific, explain the classroom use case clearly.

See [CONTRIBUTING.md](./CONTRIBUTING.md) for the full guide.

## License

MIT License - see [LICENSE](./LICENSE)
