# Automated_Reasercher_Writer_Agent
Research Agent: searches APIs, summarizes PDFs/webpages (scraper/API) Writer Agent: converts research into a structured report
ResearchAgent

Wikipedia search

News search via NewsAPI (optional; needs NEWSAPI_KEY)

Webpage scraping (BeautifulSoup)

PDF text extraction (PyPDF2)

Summarization using OpenAI (if OPENAI_API_KEY present) with a safe fallback when not available

research_pipeline() to orchestrate all research sources and produce structured summaries

WriterAgent

Builds an LLM prompt from research

Produces a polished Markdown report via OpenAI (or a fallback simple reporter)
