📰 The Hindu News Scraper Bot

An admin-controlled backend scraping system built with Node.js, Express, MongoDB, and Cheerio that extracts latest news articles from The Hindu website and stores them with duplicate-safe logic.

🚀 Overview

The Hindu News Scraper Bot is a modular, MVC-structured backend application that allows administrators to:

Create and manage a scraping bot

Enable or disable scraping dynamically

Trigger manual scraping

Run automated scraping via cron jobs

Store and retrieve scraped news articles

The system ensures production-level reliability with:

Unique indexing

Upsert-based duplicate prevention

URL validation to filter non-article links

Environment-based configuration

🛠 Tech Stack

Backend: Node.js, Express.js

Database: MongoDB, Mongoose

Web Scraping: Axios + Cheerio

Scheduler: node-cron

Environment Config: dotenv
