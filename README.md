# Document-analyser-

> A high-performance document intelligence tool that leverages Google Gemini and Firebase to provide deep insights into resumes, essays, and technical reports.
> 
✨ Key Features
 * Resume Auditing: Get an "ATS-compatibility" score and keyword gap analysis.
 * Essay Grading: Analyzes tone, grammar, and structural flow using advanced NLP.
 * Multimodal Extraction: Supports PDF and Docx uploads with OCR capabilities for scanned documents.
 * Real-time Feedback: Processing happens via Firebase Cloud Functions for a seamless, serverless experience.
 * Secure Storage: User documents are private and protected by Firebase Security Rules.
🛠️ Tech Stack
| Category | Technology |
|---|---|
| Frontend | React / Next.js |
| AI Model | Google Gemini (Pro & Vision) |
| Backend | Firebase Cloud Functions (Node.js) |
| Database | Cloud Firestore |
| Storage | Firebase Cloud Storage |
| Auth | Firebase Authentication |
🚀 Installation
 * Clone the repository
   git clone https://github.com/your-username/doc-analyzer.git
cd doc-analyzer

 * Install dependencies
   npm install

 * Set up Environment Variables
   Create a .env file in your root directory:
   REACT_APP_FIREBASE_CONFIG=your_config_object
GOOGLE_AI_API_KEY=your_gemini_api_key

 * Start the app
   npm run dev

🏗️ How to Upload to GitHub
If this is your first time pushing this project to a repository, follow these steps:
 * Create a new repository on GitHub.com.
 * Open your terminal in the project folder and run:
   git init
git add .
git commit -m "Initial commit: AI Document Analyzer"
git branch -M main
git remote add origin https://github.com/your-username/your-repo-name.git
git push -u origin main

📄 License
This project is licensed under the MIT License.
Would you like me to help you write the specific "System Prompt" that tells the AI exactly how to grade a resume versus an essay?
