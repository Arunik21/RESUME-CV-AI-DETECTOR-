
A full-stack AI Resume &amp; CV Analyzer developed in Python to automate resume parsing, ATS evaluation, skill analysis, and job matching using modern NLP techniques.
AI Full-Stack Resume Analytics Hub 🚀

An interactive, single-notebook full-stack application built entirely inside Jupyter Notebook. This platform parses uploaded resume PDFs, extracts text metadata, audits qualification alignments against a target job description using Generative AI, logs historical analytics to a local SQLite database, and presents insights via a dynamic web-style interface dashboard.

🛠️ The Tech Stack
Frontend (UI): ipywidgets and IPython.display HTML/CSS components.

Data Visualization: plotly for live interactive metric score gauges.

File Processing: pdfplumber and io.BytesIO for rapid in-memory PDF text extraction.

Database (Persistence Layer): sqlite3 tracking database ledger logs.

AI Engine Backend: OpenAI gpt-4o-mini generating strict structured JSON payloads.

🔑 Crucial Setup: OpenAI API Key Requirement
Why it is Mandatory
Because a standard Jupyter Notebook environment runs locally on your machine, it doesn't possess the native computational intelligence to read a resume, identify missing engineering keyword gaps, or write custom interview coaching drills.

This project uses OpenAI's Large Language Models as its remote cloud-computing core. The API key functions as a mandatory security passport to access these cognitive capabilities. Without a valid key, the pipeline cannot connect to the backend engine and will throw a 401 Unauthorized runtime crash.

How Each User Obtains a Key
Every individual user running this repository must use their own personal OpenAI Developer key:

Create or log into an account at the OpenAI Developer Platform.

Navigate to the API Keys tab on the dashboard sidebar and click "Create new secret key".

Copy the token immediately (starts with sk-proj-). OpenAI will hide this key permanently once you close the modal.

💳 Prepaid Developer Balances
Note that OpenAI API access is managed on a pre-paid utility consumption model. It is completely separate from a consumer retail ChatGPT Plus Subscription ($20/mo). To avoid 429 Insufficient Budget or usage limit errors, navigate to Settings ➔ Billing within your OpenAI Developer dashboard and load a small foundational balance (e.g., $5.00) onto your account
THE FOLDER IS IN PROGRESS AND WILL BE UPLOADED WITH ALL ITS COMPLETED MODULES FURTHER.
THANK YOU
