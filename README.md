# Newsgenie — AI News Agent
A conversational news assistant that routes intelligently, filters misinformation with LLM credibility scoring, and stays available even when external APIs fail.

- LangGraph StateGraph routing: real-time NewsAPI vs. LLM general-knowledge path
- LLM credibility filtering on 4 signals: tone · source attribution · claim specificity · headline integrity
- 3-level fallback chain: NewsAPI → Tavily web search → LLM-only response
- Session-aware chat with transparent credibility labelling on every article card
