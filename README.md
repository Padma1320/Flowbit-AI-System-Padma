 Multi-Agent AI System for Document Classification , Detection & Extraction with Demo video here

 Objective

Build a multi-agent AI system that:
- Accepts input files in **PDF**, **JSON**, or **Email (text)** format.
- Classifies file format and intent (Invoice, RFQ, Complaint, Regulation).
- Routes data to the appropriate agent.
- Maintains a shared context for traceability (source, type, timestamp, extracted fields, thread ID).


 System Workflow

| Agent            | Functionality                                             
|------------------|----------------------------------------------------------
| Classifier Agent | Detects file format & intent (keyword + LLM). Routes file. 
| JSON Agent       | Validates JSON fields (`id`, `date`, `amount`).           
| Email Agent      | Extracts sender, subject, body, urgency.                  
| PDF Handler      | OCR text extraction using pytesseract.                    
| Shared Memory    | Logs source, type, timestamp, extracted fields, thread ID. 

---
 Repository Structure

| File/Folder                          | Description                                     
|-------------------------------------|-------------------------------------------------
| `Multi_Agent_AI_System.ipynb`       | Final Google Colab notebook with code.                 
| `PROJECT_OVERVIEW.docx`             | Project overview and system explanation.        
| `sample_files`                     | Sample PDF, JSON, Email files.  ( inside sample files)                
| `flowbit_logs.csv`                  | Extracted logs from shared memory as output              
| `README.md`                         | Project summary and instructions and video of demonstration             



 Demo Video

[Watch the Demo Video Here](https://drive.google.com/file/d/11aAirK2gfqc4zu_PYcwmvkCXxCX_sGJE/view?usp=sharing)



Tech Stack

- Python 3.x
- OpenAI GPT-3.5-turbo API
- pytesseract + pdf2image for PDF OCR
- Google Colab (execution environment)
- pandas for shared memory logs



Submission Notes

- GitHub repo: [https://github.com/Padma1320/Flowbit-AI-System-Padma](https://github.com/Padma1320/Flowbit-AI-System-Padma)
- project folder: [Chevk the entire project in google drive link  Here](https://drive.google.com/drive/folders/11XOHFV5MmJHYnFCukohjdkk3tZSP_6Bs?usp=sharing)

 

