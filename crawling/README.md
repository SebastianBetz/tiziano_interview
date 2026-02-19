# Bonus Exercise — Data Extraction

If you have time, tackle this second task.

## Task
Extract structured information from a real tourism destination page.

**Target URL:** https://www.valgardena.it/en/addresses/detail/base/company/selva-di-val-gardena/bar-oswald/4206CF9CFA75D1664ECC5822E183F31B/

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
