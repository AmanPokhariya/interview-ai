# 🤖 Interview AI — AI-Powered Interview Preparation & ATS Resume Builder

Interview AI is a full-stack web application designed to help job seekers prepare for interviews and tailor their resumes to specific job roles using state-of-the-art Generative AI. 

Powered by **Google Gemini API**, it parses resumes, self-descriptions, and job descriptions to generate detailed, personalized feedback reports and PDF resumes.

---

## 🚀 Key Features

*   **📊 Smart Match Score:** Calculates how well your profile aligns with a specific job description (0–100%).
*   **🧠 Tailored Interview Questions:** Generates customized Technical and Behavioral questions that are highly likely to be asked, along with the interviewer's intent and optimized sample answers.
*   **📈 Actionable Prep Plan:** Provides a day-wise, step-by-step interview preparation schedule to target your weak spots.
*   **🔍 Skill Gap Analysis:** Detects critical skills missing from your profile with low, medium, and high severity levels.
*   **📄 ATS-Friendly Resume Tailoring:** Automatically rewrites and formats your resume for the target job description and exports it as a clean PDF (generated dynamically via Puppeteer).

---

## 🛠️ Tech Stack

- **Frontend:** React, Vite, React Router, SCSS
- **Backend:** Node.js, Express, MongoDB, Mongoose
- **AI Integration:** Google GenAI SDK (`@google/genai`)
- **PDF Generation:** Puppeteer
- **Validation:** Zod

---

## 📦 Installation & Setup

Follow these steps to run the project locally on your machine:

### 1. Clone the repository & Navigate
```bash
git clone https://github.com/AmanPokhariya/interview-ai.git
cd interview-ai
```

### 2. Setup the Backend
Navigate to the `Backend` directory, install dependencies, and configure your env variables:
```bash
cd Backend
npm install
```

Create a `.env` file in the `Backend` folder:
```env
PORT=3000
MONGO_URI=mongodb://localhost:27017/interview-db
GOOGLE_GENAI_API_KEY=your_gemini_api_key
JWT_SECRET=your_jwt_secret_key
```

Start the backend server in development mode:
```bash
npm run dev
```

### 3. Setup the Frontend
Open a new terminal window, navigate to the `Frontend` directory, and run the client:
```bash
cd Frontend
npm install
npm run dev
```

The app will now be live on `http://localhost:5173`.

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
