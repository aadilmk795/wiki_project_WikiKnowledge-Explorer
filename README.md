# WikiKnowledge Explorer

Interactive Wikipedia article explorer — built for **Open Source Day 2026** (WikiClub Tech × GCU).

## Challenge
Challenge 2 — WikiKnowledge Explorer (Intermediate)

## Dataset
Wikimedia Structured Wikipedia Dataset (English Wikipedia, ~7.5M articles)
https://www.kaggle.com/datasets/wikimedia-foundation/wikipedia-structured-contents

## Features
- Search articles by name (instant substring match)
- Extract links recursively from article sections
- Classify related info into People / Organizations / Places / Topics using spaCy NER
- Interactive Gradio web UI
- Clean navigation between related articles

## Tech
Python, Pandas, PyArrow, spaCy, Gradio, Kaggle Notebooks

## How to Run
1. Open notebook on Kaggle
2. Attach the Wikimedia Structured Wikipedia Dataset
3. Run all cells top to bottom
4. The Gradio cell prints a public URL

## Limitations
- Full article fetch takes ~30–60s (dataset is split across ~265 parquet files)
- Not every Wikipedia article is present in the dataset

## AI Tools Used
Claude / Deepseek for debugging and code review. All code understood and tested.

## Team
Kira36
