# ProResume-Analyzer

Here’s a professional and polished **README.md** file for your **ProResume-Analyzer** project:


---

````markdown
# 📄 ProResume-Analyzer

**ProResume-Analyzer** is an AI-powered tool designed to **intelligently analyze resumes** and provide **instant feedback** on structure, skills, and key components. Built using Python and spaCy, this script extracts text from PDF resumes, identifies relevant named entities (like names, organizations, and dates), and checks for technical skills — empowering job seekers to craft optimized, well-structured CVs.

---

## 🚀 Features

- ✅ **PDF Resume Parsing**  
  Seamlessly extracts text from PDF files using `PyPDF2`.

- 🧠 **Named Entity Recognition (NER)**  
  Utilizes spaCy's `en_core_web_sm` model to detect important resume elements such as:
  - 👤 Person names  
  - 🏢 Organizations  
  - 📅 Dates  
  - 🌍 Locations  
  - 📦 Products  
  - 🎉 Events

- 🔍 **Smart Skill Detection**  
  Automatically checks for in-demand tech skills like:
  `Python`, `SQL`, `Tableau`, `Power BI`, `Hadoop`, `Cloud`, and more.

- 📢 **Automated Resume Feedback**  
  Flags missing essentials:
  - Name
  - Work experience (Dates)
  - Email ID
  - Phone Number (valid 10-digit check)
  - Company names

- 💾 **Exports a Detailed Feedback Report**  
  Saves your resume analysis into `Resume_Feedback.txt`.

---

## 📂 How to Use

1. 🔧 **Install Requirements**

   ```bash
   pip install spacy PyPDF2
   python -m spacy download en_core_web_sm
````

2. 📝 **Add Your Resume Path**

   Update this line in the code:

   ```python
   pdf_path = r"E:\Drive E downloader\Arjun Overleaf.pdf"
   ```

3. ▶️ **Run the Script**

   ```bash
   python resume_analyzer.py
   ```

4. 📄 **Output**

   * Named Entities detected
   * Technical Skills matched
   * Feedback summary printed on terminal
   * Feedback saved to `Resume_Feedback.txt`

---

## ✨ Sample Output

```text
📄 Named Entities (Relevant):
 - Arjun Dixit: PERSON
 - Lovely Professional University: ORG
 - 2023: DATE
 - Python: PERSON
 - Excel: PRODUCT

🛠 Detected Skills:
Python, SQL, Tableau, Excel

🧠 Resume Feedback:
✅ Your resume looks well-structured!

📝 Feedback saved to 'Resume_Feedback.txt'
```

---

## 🛠 Tech Stack

* Python 🐍
* spaCy (NLP) 🧠
* PyPDF2 (PDF Parsing) 📄
* Regular Expressions (re) 🔍

---

## 💡 Ideas for Enhancement

* Integrate a GUI using `Tkinter` or `Streamlit`
* Add resume score / ranking system
* Visualize skill-match percentage with matplotlib or seaborn
* Upload resumes via web app (Flask/Django)
* ATS simulation compatibility checks

---

## 🧑‍💼 Perfect For

* Final-year students
* Job applicants
* Resume builders
* HR tech enthusiasts
* Career services teams

---

## 📬 Contact

Made with ❤️ by **Arjun Dixit**
🔗 GitHub: [arjundixit18](https://github.com/arjundixit18)

---

## 📘 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```

---

Let me know if you want to auto-generate a badge-style skills chart or wrap this as a Streamlit app!
```
