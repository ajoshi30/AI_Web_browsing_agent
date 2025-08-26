AI Web-Browsing Agent :

🔧 Tech Stack

SmolAgents (Hugging Face) – agent orchestration

OpenAI GPT-4o (configurable) – reasoning engine

Selenium + Helium – browser automation (navigation, clicks, scrolling)

DuckDuckGo Search Tool – web search integration

PIL – screenshot capture and visualization

🚀 What it Does

Runs an AI agent that can:

Perform web searches

Open and navigate real websites

Scroll, click, and close pop-ups

Capture screenshots during execution

Example task: Alfred the butler verifies if a guest is truly Wonder Woman by searching for images and Wikipedia details before granting access.

📂 How it Works

Initialize a CodeAgent with tools (search, browser navigation, screenshot capture).

Use an LLM to plan actions step-by-step.

Automate browsing in Chrome using Selenium/Helium.

Log screenshots + page info into agent memory.

💡 Use Case

This serves as a template for building AI agents that can control browsers, useful for tasks like information verification, automated research, or real-time data collection.
