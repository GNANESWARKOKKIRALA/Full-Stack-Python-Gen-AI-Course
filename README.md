# 🚀 Full Stack Python with Gen AI Course

Welcome to the **Full Stack Python with Gen AI Course** repository! A comprehensive, hands-on learning roadmap designed to take you from web development fundamentals to advanced Python programming, relational databases, data science libraries, data structures & algorithms, and state-of-the-art Generative AI & LLM applications.

---

## 📌 Course Roadmap & Sections

| Module | Core Topics | Key Resources |
|---|---|---|
| 🌐 **Web Fundamentals** | HTML5, CSS3, Semantic Tags, Forms, JavaScript | `HTML-CSS/`, `Javascript/` |
| 🐍 **Python Programming** | Basics, Pattern Programs, Logic Building, Modules | `python/basics/`, `python/scripts/` |
| ⚡ **Data Structures & Algorithms** | Stacks, Queues, Linked Lists, List Indexing | `dsa/`, `docs/dsa_*` |
| 🗄️ **Relational SQL Databases** | DDL, DML, Constraints, Joins (Inner, Full, Cross, Self) | `sql/`, `docs/sql_notes.docx` |
| 📊 **Python Data & ML Stack** | NumPy, Pandas, Plotly, Scikit-Learn, SciPy | `py_libraries/` |
| 🤖 **Generative AI & LLMs** | AI/ML/GenAI Architecture, Prompting, LangChain, Project Ideas | `generative-ai/resources/` |

---

## 📂 Repository Structure

```
Full Stack Python with Gen AI Course/
│
├── 🌐 HTML-CSS/                                  # Web Development (HTML5 & CSS3)
│   ├── 1st.html                                  # Basic HTML structure
│   ├── Links&Images.html                         # Hyperlinks & media embedding
│   ├── attributes.html                           # HTML attributes practice
│   ├── div_span.html                             # Block vs Inline element layout
│   ├── forms.html                                # Form fields & inputs
│   ├── list.html                                 # Ordered & unordered lists
│   ├── protfolio.html                            # Hands-on portfolio project layout
│   ├── semantic Tags.html                        # Modern HTML5 semantic elements
│   ├── tables.html                               # HTML table structures
│   └── HTML_CSS_30Day_Guide_CSS_FullCode.docx   # 30-Day HTML & CSS guide with complete code
│
├── ⚡ Javascript/                                # Client-Side Scripting
│   └── JavaScript_Complete_Course.pdf            # Comprehensive JavaScript course reference
│
├── 🐍 python/                                    # Core Python & Logic Building
│   ├── basics/
│   │   ├── 01_important_concepts.ipynb           # Armstrong, palindrome, string problems
│   │   ├── 02_pattern_programs.ipynb             # Number & star pattern printing
│   │   ├── 03_problem_solving.ipynb              # Max/min, logic & arithmetic problems
│   │   └── power.ipynb                           # Exponentiation & recursion algorithms
│   └── scripts/
│       ├── calculator.py                         # Modular calculator functions
│       └── module_demo.py                        # Importing custom modules in Python
│
├── 🧱 dsa/                                       # Data Structures & Algorithms
│   ├── 01_dsa_day1_stack_queue_linkedlist.ipynb  # Stack, Queue, Linked List in Python
│   └── 02_dsa_lists_linkedlist.ipynb             # List indexing & Linked List node insertions
│
├── 📊 py_libraries/                              # Data Science, ML & Visualization
│   ├── all_libraries_overview.ipynb              # Tour of NumPy, Pandas, SciPy & Matplotlib
│   ├── numpy.ipynb                               # NumPy arrays, vector operations & types
│   ├── pandas.ipynb                              # Pandas DataFrames & data manipulation
│   ├── Plotly.ipynb                              # Interactive charting with Plotly
│   ├── Scikit-Learn.ipynb                        # Machine Learning models with Scikit-Learn
│   └── student_data.csv                          # Sample dataset for data analysis
│
├── 🗄️ sql/                                        # Database Management & SQL Queries
│   ├── 01_create_table_basics.sql                # CREATE, INSERT, SELECT basics
│   ├── 02_insert_select.sql                      # Primary keys & basic CRUD operations
│   ├── 03_customer_table.sql                     # Relational customer schema practice
│   ├── 04_datatypes.sql                          # INT, VARCHAR, DECIMAL, DATE datatypes
│   ├── 05_constraints_notnull.sql                # NOT NULL & ALTER TABLE constraints
│   ├── 06_update_operations.sql                  # UPDATE queries with WHERE filters
│   ├── 07_inner_join.sql                         # INNER JOIN operations
│   ├── 08_full_join.sql                          # FULL OUTER JOIN operations
│   ├── 09_cross_join.sql                         # CROSS JOIN operations
│   ├── 10_self_join.sql                          # SELF JOIN (employee-manager hierarchy)
│   └── 11_database_creation.sql                 # CREATE DATABASE, CAST, GETDATE
│
├── 🤖 generative-ai/                             # Generative AI & Machine Learning
│   └── resources/
│       ├── advanced_ai_ml_genai_guide.pdf        # Deep dive into AI, ML & GenAI architectures
│       ├── generative_ai_fresher_guide.pdf       # Beginner-friendly GenAI guide (PDF)
│       ├── generative_ai_fresher_guide.docx      # Beginner-friendly GenAI guide (Word)
│       └── projects.pdf                          # GenAI project ideas & practical guides
│
├── 📑 docs/                                      # Reference Material & Interview Notes
│   ├── dsa_30day_guide.pdf                       # 30-Day DSA preparation PDF guide
│   ├── dsa_python_reference.docx                 # DSA reference manual in Python
│   ├── python_interview_notes.docx               # Comprehensive Python interview Q&A
│   └── sql_notes.docx                            # Detailed SQL guide & reference notes
│
├── requirements.txt                              # Python environment dependencies
├── .gitignore                                    # Virtual environments & cache exclusions
└── README.md                                     # Course overview & documentation
```

---

## ⚙️ Setup & Installation Guide

### 1. Clone the Repository
```bash
git clone https://github.com/GNANESWARKOKKIRALA/Full-Stack-Python-Gen-AI-Course.git
cd "Full-Stack-Python-Gen-AI-Course"
```

### 2. Set Up Virtual Environment
```bash
python -m venv venv

# On Windows (PowerShell / CMD):
venv\Scripts\activate

# On macOS / Linux:
source venv/bin/activate
```

### 3. Install Required Dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Environment
```bash
jupyter notebook
```

---

## 🛠️ Complete Tech Stack

- **Frontend & Web Development:** HTML5, CSS3, JavaScript (ES6+)
- **Core Programming:** Python 3.10+
- **Relational Databases:** SQL (MySQL, PostgreSQL, Microsoft SQL Server)
- **Data Analysis & Visualization:** NumPy, Pandas, SciPy, Matplotlib, Seaborn, Plotly
- **Machine Learning:** Scikit-Learn, XGBoost
- **Deep Learning & Frameworks:** PyTorch (CPU build), Torchvision, Torchaudio
- **Generative AI & LLMs:** Transformers, Sentence-Transformers, HuggingFace Hub, OpenAI API, Tiktoken
- **LLM Orchestration:** LangChain, LangChain-OpenAI, LangGraph, LangSmith
- **ORMs & Database Drivers:** SQLAlchemy, PyMySQL, Psycopg2-binary
- **Development Tools:** Jupyter Notebook, IPyKernel, Git

---

## 📌 Practical Learning Notes

- **Notebook Validation:** All `.ipynb` notebooks are pre-executed, clean, and error-free.
- **SQL Dialects:** SQL scripts utilize standard ANSI SQL compatible with **MySQL**, **PostgreSQL**, and **Microsoft SQL Server**.
- **GenAI Resources:** PDF & DOCX guides under `generative-ai/resources/` cover theoretical concepts and step-by-step project setup.
- **Web Practice:** Web files under `HTML-CSS/` can be opened directly in any modern browser for immediate visual testing.

---

## ⭐ Connect & Contribute

**GitHub Profile:** [GNANESWARKOKKIRALA](https://github.com/GNANESWARKOKKIRALA)

---

> *"Consistency beats intensity."* — Keep learning, keep coding, and build the future with AI! 🚀
