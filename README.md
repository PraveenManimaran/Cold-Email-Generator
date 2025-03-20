# 📧 Cold Mail Generator  

The **Cold Mail Generator** is a powerful tool that automates the creation of personalized cold emails for business outreach. Built using **Groq**, **LangChain**, and **Streamlit**, this tool helps businesses connect with potential clients by extracting job listings from a company's careers page and generating customized cold emails. The emails include relevant portfolio links sourced from a vector database, tailored to each job description.

## **How It Works**  

1. A company (e.g., **Nike**) is hiring a **Principal Software Engineer** and is investing time and resources in the hiring process.  
2. A software development firm (e.g., **TechForge Solutions**) has a skilled software engineer ready to take on contract work.  
3. A business development executive from TechForge Solutions wants to reach out to Nike with a personalized cold email offering their services.  
4. The Cold Mail Generator automates this process by:
   - Extracting job listings from Nike's careers page.
   - Generating a personalized cold email using **LLMs**.
   - Adding relevant portfolio links based on the job description.  

## **Architecture Diagram**  
![Architecture](imgs/architecture.png)  

## **Set-up**  

### 1️⃣ **Obtain an API Key**  
- Sign up at **[Groq](https://console.groq.com/keys)** to generate an **API Key**.  
- Inside `app/.env`, update the `GROQ_API_KEY` with your generated key.  

### 2️⃣ **Install Dependencies**  
Run the following command to install required packages:  

```bash
pip install -r requirements.txt
