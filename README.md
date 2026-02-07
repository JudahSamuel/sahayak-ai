# SAHAYAK AI 
**Voice-first AI assistant for rural India to access government schemes and public services.**

---

##  Overview
SAHAYAK AI is a serverless, multilingual, voice-first AI assistant built on AWS that helps citizens in rural India:
- Discover relevant government welfare schemes and public services  
- Check eligibility using structured questions  
- Get step-by-step guidance to complete applications  
- Generate required documents (letters, grievances, RTI drafts, complaints)  
- Receive verified answers using RAG (Retrieval Augmented Generation) from official sources

The solution is designed for **low-bandwidth connectivity** and **low digital literacy** environments.

---

##  Problem
Millions of eligible citizens fail to access welfare schemes due to:
- Lack of awareness
- Language barriers
- Complex portals and documentation
- Dependence on middlemen
- Confusing grievance and complaint processes

---

##  Key Features
- **Voice-first interface** (speech-to-text and multilingual support)
- **Scheme discovery & recommendation**
- **Eligibility checker** with explainable results
- **Guided workflow** (step-by-step application instructions)
- **Document generator**
  - Application letters  
  - Grievance letters  
  - RTI drafts  
  - Complaint drafts (e.g., cybercrime, consumer issues)
- **Verified answers only** using RAG from government sources
- **Low-bandwidth mode** for rural usability
- **Privacy-first design** (minimal storage, consent-based)

---

##  AWS Services Used
- **Amazon Bedrock** – LLM for reasoning, response generation, and workflow generation  
- **Amazon S3** – storage for official PDFs and portal content  
- **Amazon OpenSearch (Vector Search)** – RAG retrieval layer  
- **AWS Lambda** – backend APIs and orchestration logic  
- **Amazon DynamoDB** – user sessions, profiles, and workflow state  
- **Amazon Transcribe** – voice-to-text input  
- **Amazon Translate** – multilingual translation  
- **Amazon SNS** – optional SMS alerts/reminders  
- **Amazon QuickSight** – analytics dashboard (future scope)

---

##  Demo Scenarios (MVP)
1. **Scholarship Discovery**
   - User: “I’m a student, OBC, income 80k, Karnataka”
   - Output: Eligible schemes + required documents + step-by-step process + application letter draft

2. **Cybercrime Complaint**
   - User: “Someone scammed me on UPI”
   - Output: Complaint draft + correct reporting steps + portal guidance

3. **Pension / Ration Support**
   - User: “My pension stopped, what should I do?”
   - Output: Grievance workflow + required documents + formatted complaint letter

---

##  Repository Files
- `requirements.md` – System requirements generated using Kiro (Spec phase)
- `design.md` – System design generated using Kiro (Design phase)
- `README.md` – Project summary and submission overview

---

##  Hackathon Track
**AI for Communities, Access & Public Impact**

---

##  Team
LASYA SURESH
JUDAH SAMUEL
S LIKHITH ACHARI
JAYADEEP GOWDA

---

## 📌 Note
SAHAYAK AI is an informational and workflow guidance system.  
It does not directly submit applications to government portals in the MVP version.
