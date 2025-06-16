# CeWL Wordlist Generator

CeWL is a Ruby-based command-line tool used by penetration testers to generate custom wordlists by spidering websites and scraping content. It can pull words, emails, and metadata, helping you build targeted password lists for use in tools like Hydra or John the Ripper.

🔗 [Use the CeWL Command Generator on SploitHQ](https://sploithq.com/cewl)

---

## 🔍 What Can CeWL Do?

- Crawl a website to extract words of a certain length
- Save results to a file for later use
- Optionally extract email addresses and document metadata
- Customize crawling depth, user agent, and output

---

## ⚙️ Basic Usage

```bash
cewl https://example.com
