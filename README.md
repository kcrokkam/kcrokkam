# Krishna Chaitanya Rokkam

**Data Science · Machine Learning · AI Engineering**

Boston, MA · [LinkedIn](https://www.linkedin.com/in/krishna-chaitanya-rokkam/) · [Repositories](https://github.com/kcrokkam?tab=repositories)

I'm a data scientist and enterprise analytics professional. I build forecasting systems and AI applications that turn operational data into decisions, with attention to model evaluation, testable application logic, and the constraints of real workflows.

## Enterprise experience

- **Ahold Delhaize USA:** Standardized reporting across five retail brands and reduced a monthly reporting cycle from **more than 20 days to 3 days**.
- **Vertex Pharmaceuticals:** Used Python regression analyses to study drivers of drug development timelines.
- **Accenture:** Worked on production automation.

I'm pursuing a **Ph.D. in Artificial Intelligence at the University of the Cumberlands**, with interests in trusted enterprise AI, agentic systems, and AI evaluation.

## Selected projects

### [Bluebikes Intelligence](https://github.com/kcrokkam/bluebikes-intelligence) — ML forecasting and decision support

Built next-day hourly departure and arrival forecasts and a station monitoring watchlist using **13.3 million station-hour rows**. On **92 unseen test days**, LightGBM achieved **67.4% departure WAPE**, compared with **70.0%** for a frozen historical-profile baseline.

The workflow combines forecasts with live inventory context; an AWS Lambda, EventBridge, and S3 pipeline collects inventory snapshots. Historical backtests use observed weather; the watchlist is a monitoring signal based on trip depletion.

[Results and evaluation](https://github.com/kcrokkam/bluebikes-intelligence#results) · [Modeling decisions](https://github.com/kcrokkam/bluebikes-intelligence/blob/main/docs/modeling_decisions.md)

### [Customer Feedback Analyzer](https://github.com/kcrokkam/customer-feedback-analyzer) — Structured AI and API engineering

Turns written reviews into sentiment, satisfaction scores, and themes through a **FastAPI service and Streamlit dashboard**. Pydantic validates model responses; separate analytics and SQLite modules keep the application logic testable. The dashboard preserves partial successes and retries failed reviews.

[Demo](https://customer-feedback-analyzer-e9knamtt665fhwzv9strhq.streamlit.app/) · [Architecture](https://github.com/kcrokkam/customer-feedback-analyzer/blob/main/ARCHITECTURE.md) · [Tests](https://github.com/kcrokkam/customer-feedback-analyzer/tree/main/tests)

### [AI Shopping Agent](https://github.com/kcrokkam/ai-shopping-agent) — Multimodal tool use

Connects natural-language requests and product images to catalog search, rating lookup, and demo checkout. **LangChain coordinates the tools**, while Python and SQLite handle product data and orders. Catalog and rating tests run independently of model calls; checkout uses sample data and no real payments.

[Demo](https://ai-shopping-agent-nbnus6ixgzzhpu9hkatg5z.streamlit.app/) · [Architecture](https://github.com/kcrokkam/ai-shopping-agent/blob/main/ARCHITECTURE.md) · [Tests](https://github.com/kcrokkam/ai-shopping-agent/tree/main/tests)

### [Telecom RAG Assistant](https://github.com/kcrokkam/telecom-rag-chatbot) — Retrieval and Python packaging

Retrieves from **FAQs, resolved tickets, and a technical guide** using separate Chroma collections and local embeddings. Ingestion is separate from question answering, and the packaged workflow supports browser and terminal interfaces. Automated checks cover packaging and runtime behavior; retrieval and answer quality remain unbenchmarked.

[Demo](https://telecom-rag-chatbot-zr7jytflnhserbkps7uhaq.streamlit.app/) · [Retrieval design](https://github.com/kcrokkam/telecom-rag-chatbot/blob/main/ARCHITECTURE.md) · [Tests](https://github.com/kcrokkam/telecom-rag-chatbot/tree/main/tests)

### [Interview Synthesizer](https://github.com/kcrokkam/interview_synthesizer) — Evidence checks for AI workflows

A staged Claude Code workflow turns transcripts into themes and a memo, then applies **Python quote/number checks and a separate critic review**. Development runs use eight synthetic interviews. Saved outputs document both verified source matches and remaining problems with attribution and overstated claims.

[Sample memo](https://github.com/kcrokkam/interview_synthesizer/blob/main/output/memo.md) · [Quality checks](https://github.com/kcrokkam/interview_synthesizer/blob/main/output/quality_report.md) · [Critic review](https://github.com/kcrokkam/interview_synthesizer/blob/main/output/critic_review.md)

**Additional work:** [Blood Work Analyzer](https://github.com/kcrokkam/blood-work-analyzer), an educational two-stage extraction/interpretation experiment with injected-model tests and no clinical validation. [AI project collection](https://github.com/kcrokkam/agentic-ai-projects) includes earlier prototypes.

## Technical background

- **Data science and ML:** Python, SQL, R, pandas, NumPy, scikit-learn, LightGBM, regression, classification, feature engineering, forecasting, and chronological evaluation.
- **AI applications:** LangChain, RAG, agents, Chroma, local embeddings, FastAPI, Pydantic, Streamlit, SQLite, and pytest.
- **Enterprise analytics and cloud:** Snowflake, PostgreSQL, ETL, Alteryx, Power BI, AWS, and Azure.
