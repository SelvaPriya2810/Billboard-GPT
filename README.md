# 🎧 BillboardGPT – GPT-Powered Music Chart Analyzer

**BillboardGPT** is a fun and intelligent music data project that scrapes Billboard's Hot 100 chart and uses GPT-4 to analyze weekly chart trends and predict song genres.

🧠 It combines Python scraping with GPT magic to generate natural language insights and classify song genres like a mini A&R team.

---

## ✅ What It Does (So Far)

### 🎯 Weekly Chart Comparison
- Automatically scrapes:
  - **This week’s Billboard Hot 100**
  - **Last week’s chart** (auto-detected using date math)
- Uses **GPT-4** to:
  - Compare chart changes
  - Identify new entries and dropouts
  - Summarize artist trends and shifts in rankings

### 🎵 Genre Classifier (Top 10 Songs)
- Sends the **Top 10 songs** (title + artist) to GPT-4
- GPT acts as a music expert and **predicts genres**:
  - Pop, Hip-Hop, Rap, Country, R&B, etc.
- Useful for visualizing genre distribution and tracking trends

---

## 🧠 Example GPT Output

```text
- 6 new songs entered the chart this week.
- Taylor Swift remains dominant with 2 songs in the Top 10.
- Genres like Pop and Country are on the rise.
