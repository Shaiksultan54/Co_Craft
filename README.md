# CoCraft: AI-Powered Project Collaboration Software  
**“CRAFT CODE, TOGETHER”**

---

## 🚀 **Abstract**  
CoCraft is an end-to-end AI SaaS platform designed to revolutionize GitHub workflows. By leveraging AI technologies like Retrieval Augmented Generation (RAG) and Google Gemini, CoCraft automates code comprehension, streamlines collaboration, and organizes project knowledge. It transforms fragmented workflows into seamless, AI-auditable processes, reducing wasted time, miscommunication, and inefficiencies in project management.

---

## 🛠 **Core Problem Statement**  
### **Challenges Faced by Teams**  
1. **Knowledge Fragmentation:**  
   - Scattered documentation and tribal knowledge.  
   - Time-consuming onboarding for new members.  
   - Hours wasted searching for context within codebases.  

2. **Code Comprehension Challenges:**  
   - Lack of contextual understanding of complex codebases.  
   - Inefficient manual code analysis.  
   - Rapidly changing repositories without AI-assisted tracking.  

3. **Collaboration Bottlenecks:**  
   - Misaligned team efforts on complex repositories.  
   - Unstructured meeting notes and missed decisions.  
   - 40% of project time lost to miscommunication.  

---

## 🌟 **Solution: CoCraft**  
An AI-powered collaboration and code intelligence platform that integrates seamlessly into GitHub workflows.

### **Key Features**  
#### **1. AI-Powered Knowledge Hub**  
- **Automated Repository Crawling**: Index entire codebases using LangChain and GitHub APIs.  
- **AI-Generated Project Summaries**: Instant overviews for onboarding developers.  
- **Q&A with Code Context**: Ask questions like “Where is the PDF loader?” and get relevant code snippets.

#### **2. Real-Time Code Intelligence**  
- **Retrieval Augmented Generation (RAG)**: Analyze codebases for logic, dependencies, and changes.  
- **Commit Summaries**: AI-generated commit messages for clear updates.  
- **Codebase Pulse Dashboard**: Visualize team activity and code changes in real-time.

#### **3. Seamless Collaboration**  
- **Team Notes with AI Insights**: Shared workspace with AI-highlighted key decisions.  
- **Meeting Analysis**: AI-generated summaries and Q&A from recordings (e.g., “What was decided about the API redesign?”).  
- **Saved Answers**: Preserve FAQs for onboarding and future reference.

#### **4. Scalable Access**  
- **Credit System**: Pay-as-you-go model for repository processing and meeting analysis.  
- **Cost Optimization**: Usage limits ensure budget-friendly scaling.  

---

## 🧩 **How It Works**  

### **Step 1: Repository Crawling**  
- **GitHub API**: Fetches code, issues, and commits.  
- **LangChain Document Loaders**: Processes files into structured data.

### **Step 2: Embedding & Vector Storage**  
- **Google Gemini Embeddings**: Converts code and documentation into vector format.  
- **Vector Database**: Pinecone/Chroma for fast retrieval of data.

### **Step 3: AI-Powered Query Engine**  
- **Retrieval Augmented Generation (RAG)**: Combines vector search and Gemini for context-aware answers.  
- **Meeting Analysis Pipeline**: Uses Assembly AI for transcription and Gemini for summaries.

### **Step 4: User Interaction**  
- **Frontend**: Built with Next.js for intuitive Q&A, dashboards, and collaboration.  
- **Stripe Integration**: Credit-based SaaS model for access to AI processing.  

---

## 🛠 **Technical Stack**  
- **Frontend**: Next.js  
- **Backend**: Next.js API routes, LangChain for RAG pipeline  
- **Database**: NeonDB (PostgreSQL) for user/project data and credits  
- **AI Layer**:  
  - Google Gemini for code analysis and Q&A  
  - LangChain for chunking, retrieval, and prompt engineering  
  - Assembly AI for meeting transcription  

---

## 💡 **Why CoCraft?**  
- **Organized Knowledge**: Turn chaotic codebases into structured, AI-auditable projects.  
- **Time Savings**: Reduce onboarding and project delays with AI-powered insights.  
- **Enhanced Collaboration**: AI-driven notes, decisions, and Q&A bridge communication gaps.  

---

## 🚀 **Getting Started**  
### **Clone the Repository**  
```bash
git clone https://github.com/yourusername/CoCraft.git
