# DNA Analysis Tool (Local, Privacy-First)

**Live Demo:** [https://inblack.github.io/CLIDNAWEB/](https://inblack.github.io/CLIDNAWEB/)

This is a **100% private, local-only** DNA analysis tool. It takes raw DNA data files (from 23andMe or AncestryDNA) and cross-references them against a curated library of scientific findings.

## 🛡️ Absolute Privacy Guarantee
This tool operates entirely within your web browser. 
* **Zero Uploads:** Your raw DNA file is **never** uploaded to any server. 
* **Zero Telemetry:** The application makes no external API calls to process your data.
* **Local Processing:** All parsing, matching, and filtering happen in your computer's memory. If you refresh the page or close the tab, the data vanishes.

## ✨ Core Features
1. **Curated Actionable Insights:** Instead of thousands of noisy results, this tool uses a highly curated list of SNPs cross-referenced with **ClinVar** (for clinical significance) and **gnomAD** (for exact population rarity percentages).
2. **Smart Filtering:** 
   * Hides age-inappropriate data (e.g., zeroing out infant-specific risks for adults).
   * Filters out sex-specific risks that do not apply to the user.
3. **Plain English Summaries:** Translates cryptic scientific shorthand into human-readable, actionable descriptions.

## ⚠️ Legal Disclaimer & Caveats
### NO MEDICAL ADVICE
This software is provided for **educational and informational purposes only**. It is not a medical device, nor is it intended to diagnose, treat, cure, or prevent any disease. 

**DO NOT** make any medical decisions based on the information provided by this tool. Always consult with a qualified healthcare professional or genetic counselor before taking any action based on genetic data.

### ACCURACY AND LIMITATIONS
1. **Raw Data Errors:** Consumer DNA tests (like 23andMe or AncestryDNA) are prone to genotyping errors. Rare variants flagged by this tool may be "false positives" and must be confirmed by a clinical-grade laboratory.
2. **Incomplete Data:** This tool only analyzes a subset of the human genome. A "negative" result for a risk factor does not mean the risk does not exist.
3. **Statistical Rarity:** The rarity percentages provided are based on global databases and may vary significantly by ancestry and population group.
4. **No Claims:** The developers of this tool make no claims regarding the completeness, reliability, or accuracy of the genetic interpretations provided. By using this tool, you acknowledge that you are doing so at your own risk.

---
*Note: The source code for this application is maintained in a separate private repository to protect the curation algorithms and backend tooling. This repository only contains the compiled, minified code required to run the web application.*
