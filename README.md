# LLM Conversation Analysis
_A user insights investigation conducted at Thumbtack_

## 🔍 Overview
On the app, customers and pros can have a conversation via messenger to align on job details before proceeding to a booking. However, very few conversations resulted in a booking. This led to a key question:
**What user pain points are preventing customers and pros from moving forward?**

## 📊 Analysis Details
Due to the large volume of user conversations, manual review was not feasible. Instead, we used large language models (LLMs) to analyze message threads and classify the reason a booking didn't occur into one of three categories: scope, price, or timing.

<!-- TODO: If you added a fourth category or used "other" or a confidence threshold, mention it here -->

## 🧠 Methods & Tools
- **Languages**: Python
- **Techniques**: Large Language Models (LLMs), prompt engineering  
- **Workflow**: Data querying → text preprocessing → LLM-based classification → validation and synthesis

## 🎯 Outcomes
- Quantified breakdown of booking blockers: X% price, Y% scope, Z% timing
<!-- TODO: Update values -->
- Enabled the team to understand which pain points were most common and actionable
- Insights directly shaped feature prioritization and product strategy to reduce booking friction

## 📂 Contents
- `scripts/`: Code
- `slides/`: Final deck summarizing findings and recommendations (PDF)
- `README.md`: Overview of the project
