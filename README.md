# LinkShield AI – AI-Powered Phishing and Scam Detection Platform

## 📌 About the Project
LinkShield AI is a web-based application designed to help users identify potential phishing attempts and online scams by analyzing suspicious URLs and screenshots. It provides risk assessments and AI-generated explanations to help users understand possible security threats.

## ✨ Features
- **URL Analysis:** Analyzes URLs using rule-based security checks to identify potential phishing indicators.
- **Screenshot Analysis:** Extracts text from uploaded screenshots using Optical Character Recognition (OCR) and checks for suspicious patterns.
- **AI Security Assistant:** Uses Google Gemini API to provide easy-to-understand explanations about analysis results.
- **User Authentication:** Allows users to create accounts and log in.
- **Analysis History:** Stores analysis results and AI chat history in a MySQL database.

## 🛠️ Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, Flask
- **Database:** MySQL
- **OCR:** Tesseract OCR, Pytesseract
- **Image Processing:** Pillow
- **Generative AI:** Google Gemini API (Gemini 2.5 Flash)

## ⚙️ How It Works
1. The user enters a suspicious URL or uploads a screenshot.
2. For URL analysis, the backend checks configured URL security indicators using rule-based logic.
3. For screenshot analysis, OCR extracts visible text, which is checked for potential scam-related patterns.
4. The application generates a risk classification and displays the analysis results.
5. The user can ask the AI Security Assistant questions about the results.
6. User details, analysis results, and chat history are stored in MySQL.

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- MySQL Server
- Tesseract OCR
- Google Gemini API key

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/deepu-61/LinkShield-AI.git
   ```

2. Navigate to the project directory:
   ```bash
   cd LinkShield-AI
   ```

3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Configure the MySQL database using your project’s SQL schema.

5. Set the required environment variables, including your Gemini API key and database credentials.

6. Start the Flask application using the entry-point file in your project.

## 🔐 Security Note
LinkShield AI provides indicative risk assessments based on configured rules and extracted text. It does not guarantee that a website is safe or malicious. Users should avoid entering real passwords, banking details, or OTPs on suspicious websites.

Keep API keys and database credentials private. Do not upload `.env` files or other secrets to GitHub.

## ⚠️ Limitations
- Rule-based analysis may produce false positives or false negatives.
- OCR accuracy depends on screenshot quality.
- AI-generated explanations may not always be accurate.
- The application does not replace professional security tools or verified threat-intelligence services.

## 👩‍💻 Author
**Deepika**  
B.Tech – Information Technology

GitHub: https://github.com/deepu-61
