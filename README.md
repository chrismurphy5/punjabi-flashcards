# ਪੰਜਾਬੀ Flashcards

A Punjabi vocabulary PWA with spaced repetition, themed browsing, and custom card creation. 5,120 cards merged from Wiktionary, Pimsleur, and curated themed decks — all with audio.

## Features

**📚 Browse by Theme** — 17 sections (Crash Course, Grammar, Food, People, Daily Life, Pimsleur Essentials, etc.) covering 56 categories. Study a specific topic or drill a category.

**🔄 SRS Review** — FSRS spaced repetition (the algorithm Anki uses). Rate each card Again / Hard / Good / Easy, and the scheduler brings it back at the optimal interval. Due cards queue up automatically.

**➕ Create Custom Cards** — Add your own words or phrases. Type English + Punjabi, record audio for each side, add example sentences with recordings, preview, and save. Custom cards appear in "Chris's Custom Cards" and feed into SRS like any other card.

**🔊 Audio Everywhere** — Every card has English + Punjabi audio (gTTS). Example sentences too. Custom card recordings play from device storage.

**📝 Per-Card Notes** — Jot down alternative spellings, usage tips, or anything else. Notes persist per card.

**📱 Installable PWA** — Add to iPhone home screen from Safari. Works offline, full screen, persists across sessions. No account, no server, no subscription.

## Tech

- Single-page PWA (HTML + vanilla JS, no framework)
- FSRS scheduler (simplified implementation)
- gTTS for audio generation (Python pipeline)
- localStorage for progress, notes, and custom cards
- IndexedDB for voice recordings
- Hosted on GitHub Pages

## Data Sources

| Source | Cards | Notes |
|---|---|---|
| Curated themed CSVs | 1,731 | 16 sections, examples, tags — translated via Gemini |
| Wiktionary frequency list | 916 | Human-edited definitions |
| Pimsleur transcripts | 27 | Conversational phrases |
| Leipzig Corpora (Punjabi Wikipedia) | 2,456 | Frequency-ranked, translated via glm-5.2 |

Deduplicated by Gurmukhi text. 5,120 unique cards total.

## License

Personal use. Not for redistribution.