# Fitra Ramdhan Hafidz - AI Engineer Portfolio

A modern, highly interactive AI Engineer Portfolio built with Next.js App Router, Tailwind CSS, and Framer Motion. This portfolio showcases not just projects and experience, but live AI capabilities directly in the browser through the custom **AI Lab**.

![Portfolio Preview](./public/profile.png) <!-- Update with actual preview image if available -->

## 🌟 Key Features

### 1. Multi-Model AI Lab
The standout feature of this portfolio is the **AI Lab**, built with the Vercel AI SDK. It connects directly to multiple LLM APIs, each specialized for a specific task:
- 💬 **AI Chat** powered by **Llama 3.1 8B (Groq)**: Ask anything about Fitra's background and skills directly to an AI persona.
- 📝 **Resume Analyzer** powered by **Mistral Small**: Have AI review Fitra's qualifications and skills gap.
- 💻 **Code Explainer** powered by **Llama 3.3 70B (Groq)**: Paste code or ask complex coding questions, and the AI will explain it step-by-step with markdown formatting.
- 🔍 **Deep Reasoning** powered by **DeepSeek V3**: Ask complex ML/system design architecture questions for deep analytical thinking.

### 2. Modern UI/UX
- **Glassmorphism Design**: Sleek glass cards and glowing accents.
- **Scroll Animations**: Smooth reveal animations using `framer-motion` and `IntersectionObserver`.
- **Interactive Particle Background**: A dynamic canvas background that reacts to the mouse.
- **Custom Cursor Glow**: A soft glow that follows your cursor everywhere.

### 3. Core Sections
- **Hero**: Impactful introduction with tech stack tags.
- **About**: Personal summary and career objectives.
- **Experience**: Timeline of work history (Solos AI Consulting, Elice NIPA Korea ASEAN Academy, PT Solusi Intek Indonesia).
- **Projects**: Highlighted case studies (VisDrone, Deftection, MindVerse AI).
- **Skills**: Categorized technical skills with interactive progress bars.
- **Contact**: Quick links to Email, Phone, LinkedIn, and Jobstreet.

## 🛠 Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Styling**: Tailwind CSS v4, Vanilla CSS Variables
- **Animations**: Framer Motion
- **AI Integration**: Vercel AI SDK (`ai`, `@ai-sdk/react`, `@ai-sdk/groq`, `@ai-sdk/mistral`, `@ai-sdk/openai-compatible`)
- **LLM Providers**: Groq API, Mistral API, DeepSeek API

## 🚀 Getting Started Locally

### Prerequisites
You need Node.js installed (v18+ recommended) and active API keys for the AI providers.

### 1. Clone the repository
\`\`\`bash
git clone https://github.com/FitraRH/portfolio.git
cd portfolio
\`\`\`

### 2. Install dependencies
\`\`\`bash
npm install
\`\`\`

### 3. Set up Environment Variables
Create a \`.env.local\` file in the root directory and add your API keys:
\`\`\`env
# Groq API (Used for Llama 3.1 and Llama 3.3)
GROQ_API_KEY=your_groq_api_key_here

# Mistral API (Used for Resume Analyzer)
MISTRAL_API_KEY=your_mistral_api_key_here

# DeepSeek API (Used for Deep Reasoning)
DEEPSEEK_API_KEY=your_deepseek_api_key_here
\`\`\`

### 4. Run the development server
\`\`\`bash
npm run dev
\`\`\`

Open [http://localhost:3000](http://localhost:3000) in your browser to see the portfolio. The page will auto-update as you edit the files.

## ☁️ Deployment

This project is optimized for deployment on Vercel.

1. Push your code to a GitHub repository.
2. Go to [Vercel](https://vercel.com/) and create a new project.
3. Import the repository.
4. Add the Environment Variables (`GROQ_API_KEY`, etc.) in the Vercel project settings.
5. Click **Deploy**.

## 📄 License
This project is open-source and available under the Apache-2.0 License.

---
*Designed & Developed by [Fitra Ramdhan Hafidz](https://github.com/FitraRH)*
