# Loan Description Classification with GenAI (Gemini)

This project uses Google’s Gemini LLM to classify free-text LendingClub loan descriptions into structured categories, with validation, temperature analysis, and cost/time estimates for large-scale processing.

## 📌 Project Highlights
- Labeled 100 loan descriptions into `business`, `home improvement`, or `other` using Gemini LLM with prompt engineering.
- Validated model predictions against manually labeled data to assess classification accuracy.
- Analyzed the impact of temperature settings (0, 1, 2) on classification consistency and quality.
- Estimated labeling cost of **$4,370.89** and processing time of **85 days (free tier)** vs. **~1 hour (Tier 1)** for scaling to 126,053 records.

## 🛠 Technologies Used
- Python
- Gemini API
- Prompt Engineering
- Pandas
- Jupyter Notebook
