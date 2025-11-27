---
title: "Intenly – Voice Dataset Builder"
summary: "Intenly helps ML teams quickly collect multilingual speech with transcripts and intent labels, then export training-ready datasets."
dateString: 2025
draft: false
tags: ["Kotlin", "Android", "Jetpack Compose", "Hilt", "Room", "WorkManager", "OpenAI", "STT", "ASR", "NLU", "ML Tools"]
showToc: false
weight: 203
cover:
    image: "projects/Intenly-Voice-Dataset-Builder.png"
---

## Description

**Intenly** is a voice dataset builder designed for **ML and NLU teams** who need to collect **speech + transcript + intent label** quickly — especially for languages where typing is slow or painful (like Urdu).

The app streamlines the full loop:

1. **Record speech** on-device  
2. **Auto-transcribe** via OpenAI STT  
3. **Assign an intent label** to each utterance  
4. **Export a ZIP** that plugs into common ASR/NLU training scripts

The goal is to remove the friction of custom “data collection tools” and provide a clean, opinionated workflow from **spoken utterance → training data**.

---

## Key Features

- **Multilingual Recording & Transcription**  
  Record **16 kHz mono WAV** audio and auto-transcribe with OpenAI (e.g. `gpt-4o-mini-transcribe` or `whisper-1`), using **Auto Detect** or fixed language tags like `ur-PK` / `en-US`.

- **Intent-Centric Data Collection**  
  Create per-project intents (e.g. `check_balance`, `greet`) and attach each utterance so you always capture the full tuple: **(audio, text, intent)**.

- **Project-Based Workspaces**  
  Work inside clean, auto-named projects (`project-001`, `project-002`, …), rename them as needed, and let each project remember its last-used language.

- **Samples Browser with Playback**  
  Review saved samples per project — see transcript, intent, duration, date — and **play back audio** or delete items directly from the list.

- **One-Tap Dataset Export**  
  Export a **single ZIP** that contains:
  - `audio/` WAV files  
  - ASR manifests (`*.jsonl`)  
  - Intent manifests (`*.csv`)  
  - Split info (train/valid) and a small dataset card/schema  

- **Training-Ready Format**  
  The exported manifests are structured so you can wire them into ASR or intent-classification pipelines with minimal glue code.

---

## Tech Stack

- **Platform:** Android (Kotlin)  
- **UI:** Jetpack Compose (Material 3)  
- **Architecture:** Hilt for DI, Room for local storage, repository-based data layer  
- **Background Work:** WorkManager for dataset export  
- **Audio:** Custom WAV recorder (16 kHz mono)  
- **STT Integration:** OpenAI `/v1/audio/transcriptions` (configurable model, auto or fixed language)

---

Intenly sits at the intersection of **mobile UX** and **ML tooling** — giving teams a practical way to collect high-quality, multilingual speech datasets directly from real devices.