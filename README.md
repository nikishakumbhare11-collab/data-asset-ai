# AI-Assisted Data Asset Recognition & Valuation

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

&gt; Research Project** — Using NLP and Machine Learning to identify unreported data assets 
&gt; in Chinese A-share firms and estimate their fair value.

## Research Objective

China is the first country to formally recognize **data as a factor of production** on corporate balance sheets. 
However, barely 2% of listed firms have capitalized their data assets. This project uses:

- **NLP (BERT/LLM)** to detect data asset disclosures in annual reports
- **Machine Learning (XGBoost)** to estimate fair value of unreported data assets
- **Gap Analysis** to quantify the "Data Asset Reporting Gap"

### 1. Clone & Setup
git clone https://github.com/nikishakumbhare11-collab/data-asset-ai.git
cd data-asset-ai
pip install -r requirements.txt
