# Bonus Exercise — Data Extraction

If you have time, tackle this second task.

## Task
Extract structured information from a real tourism destination page.

**Target URL:** https://www.valgardena.it/en/detail/base/events/snowshoeing-with-the-mountain-guides-gardenaguides-below-the-odle/EF24C975CEE84D66BFEB5746A8DC0F4A/19-02-2026/

Write a script that fetches the page and returns a JSON object with:
- `name` — destination or business name
- `opening_hours` — structured if possible
- `contact` — phone, email, address
- `description` — 2-3 sentence summary

## Constraints
- Python
- Any approach you like — scraping, LLM extraction, or a combination
- Should run in one command: `python crawl.py`
- Output JSON to stdout

## Requirements
```bash
pip install -r requirements.txt
```
