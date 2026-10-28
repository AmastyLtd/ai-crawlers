# AI Crawlers & Robots Policy List

A curated list of AI user-agents and web crawlers used by [Amasty SEO Toolkit for Magento 2](https://amasty.com/seo-toolkit-for-magento-2.html) to dynamically configure `robots.txt` access policies.

## Purpose

AI crawlers evolve rapidly. This repository provides a centralized, up-to-date source of known AI bots grouped by their intended behavior. It allows store owners to:
- **Block AI Training:** Prevent models from scraping storefront content for LLM pre-training.
- **Allow AI Search & RAG:** Retain visibility in AI-powered search engines, answer engines, and real-time retrieval systems.
- **Allow User-Triggered Fetchers:** Permit single-request fetches triggered directly by users in AI chat interfaces.

---

## Crawler Categories

Crawlers are categorized into three policy groups:

### 1. Training Crawlers (`training`)
Bots that scrape web data to pre-train or fine-tune foundational Large Language Models (LLMs).
- **Default agents:** `GPTBot`, `ClaudeBot`, `Google-Extended`, `CCBot`, `Applebot-Extended`, `Meta-ExternalAgent`

### 2. Search & Retrieval Crawlers (`search`)
Bots used by AI search engines, answer engines, and real-time Retrieval-Augmented Generation (RAG) systems.
- **Default agents:** `OAI-SearchBot`, `PerplexityBot`, `Claude-SearchBot`, `Meta-WebIndexer`, `Amazonbot`

### 3. User-Triggered Fetchers (`user_triggered`)
Bots that visit a page in response to an explicit real-time action or URL submission by an end user in an AI chat/assistant interface.
- **Default agents:** `ChatGPT-User`, `Claude-User`

