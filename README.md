AI System to Automatically Review and Summarize Research Papers

An AI-powered research assistant that automates the process of searching, analyzing, summarizing, and reviewing academic research papers. The system uses AI and NLP to generate structured systematic literature reviews, APA-style citations, and downloadable PDF reports, helping students and researchers save time and efficiently organize research findings.

✨ Features
🔍 Automated research paper search
📄 PDF extraction and preprocessing
🤖 AI-powered analysis and summarization
📚 Systematic literature review generation
🔗 APA-style citation formatting
📑 Structured research report generation
📥 PDF report generation
🔐 User authentication
💾 Research history storage
🖥️ Interactive web interface
🛠️ Technologies Used
Python
Gradio
Generative AI / LLM
Natural Language Processing (NLP)
SQLite
PyPDF
Research APIs
PDF Generation
🔄 How It Works
User enters research topic
          ↓
Search relevant research papers
          ↓
Download research papers
          ↓
Extract and preprocess PDF content
          ↓
AI analysis and summarization
          ↓
Generate systematic literature review
          ↓
Generate APA-style references
          ↓
Generate final PDF report
📂 Project Structure
research_ai/
│
├── app.py
├── backend.py
├── auth.py
├── database.py
├── paper_search.py
├── pdf_handler.py
├── analysis.py
├── reviewer.py
├── writer.py
├── apa_formatter.py
├── pdf_generator.py
├── workflow.py
├── check_models.py
│
├── requirements.txt
├── README.md
├── LICENSE
├── .gitignore
└── .env.example
⚙️ Installation
1. Clone the Repository
git clone https://github.com/NaveenVSuperneuraX/AI-System-to-Automatically-Review-and-Summarize-Research-Papers.git


cd AI-System-to-Automatically-Review-and-Summarize-Research-Papers
2. Create Virtual Environment

Windows:

python -m venv venv
venv\Scripts\activate

Linux/macOS:

python3 -m venv venv
source venv/bin/activate
3. Install Dependencies
pip install -r requirements.txt
🔑 Environment Configuration

Create a .env file in the project root:

GEMINI_API_KEY=your_gemini_api_key_here
SEMANTIC_SCHOLAR_API_KEY=your_semantic_scholar_api_key_here

⚠️ Never upload your actual .env file or API keys to GitHub.

Use .env.example as the configuration template.

▶️ Run the Application
python app.py

Then open the local URL displayed in the terminal, typically:

http://127.0.0.1:7860
📄 Generated Output

The system generates a structured literature review containing:

Abstract
Introduction
Methodology
Findings
Discussion
Conclusion
APA References
Downloadable PDF Report
🎯 Use Cases
🎓 College and academic projects
🔬 Research assistance
📚 Literature reviews
📝 Thesis preparation
📖 Research surveys
📑 Systematic literature reviews
🧑‍🏫 Academic research
🚀 Future Enhancements
☁️ Cloud deployment
📊 Research analytics dashboard
🔎 Advanced paper ranking
📚 Integration with additional academic databases
🧠 Multi-model AI support
📈 Research trend visualization
🔗 Automatic DOI extraction
👥 Collaborative research workspace
📱 Mobile application
👨‍💻 Developer

Naveen V
B.Tech – Artificial Intelligence & Data Science

This project was developed by Naveen V under the guidance of the project mentor, springboardmentor3847a-cloud, as part of the project work.

📜 License

This project is distributed under the MIT License.

See the LICENSE file for the complete license terms and copyright notice.
