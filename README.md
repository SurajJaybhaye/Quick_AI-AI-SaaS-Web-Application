# ⚡ Quick AI – Full-Stack AI SaaS Platform  

### 🚀 AI Tools for Smarter Content, Design & Career Growth  

**Quick AI** is a full-stack AI SaaS platform that brings together multiple AI-powered tools for creators, designers, and job seekers.  
It helps users generate content, design visuals, and even analyze resumes — all in one seamless web app.  

🌐 **Live Demo:** [https://quick-ai-lake-three.vercel.app/](https://quick-ai-lake-three.vercel.app/)  

---

## 🧠 Features  

### ✍️ AI Article Writer  
Generate high-quality, engaging articles on any topic using advanced AI language models.  

### 📰 Blog Title Generator  
Instantly create catchy, SEO-friendly blog titles that capture attention.  

### 🎨 AI Image Generation  
Create stunning visuals from text prompts — powered by AI image generation technology.  

### 🧼 Background Removal  
Effortlessly remove image backgrounds with precision using AI-driven tools.  

### 🧹 Object Removal  
Remove unwanted objects from images while maintaining natural backgrounds.  

### 🧾 Resume Reviewer  
Upload your resume and get instant, AI-based feedback to improve structure, readability, and job relevance.  

---

## 🧰 Tech Stack  

| Layer | Technology |
|--------|-------------|
| **Frontend** | React.js, Tailwind CSS |
| **Backend** | Node.js, Express.js |
| **Database** | PostgreSQL (via Neon) |
| **Hosting** | Vercel |
| **Authentication** | Clerk |
| **AI Integration** | OpenAI API (GPT / Image Gen Models) |

---

## ⚙️ Core Highlights  

- 🧩 **Modular Architecture** — Each tool (Article, Image, Resume) is built as a separate module, making it scalable and maintainable.  
- 🔐 **Secure Authentication** — Integrated with **Clerk** for frictionless user login and session handling.  
- 💾 **Serverless PostgreSQL** — Deployed with **Neon** for lightning-fast database access.  
- 🌩️ **Optimized Deployment** — Deployed on **Vercel**, leveraging serverless functions for performance and cost efficiency.  
- 📈 **User-Friendly UI** — Clean and responsive interface built with **Tailwind CSS**, focusing on accessibility and design consistency.  

---

## 🛠️ Getting Started  

### Clone the Repository  
```
git clone https://github.com/SurajJaybhaye/Quick_AI-AI-SaaS-Web-Application.git
cd Quick_AI-AI-SaaS-Web-Application
```

### Server Setup
```
cd server
npm install
```

### Setup Environment Variables Create a .env file in the server folder with:

```
DATABASE_URL=your_postgresql_url

# Clerk Auth
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# Google Gemini
GEMINI_API_KEY=your_gemini_key

# Clipdrop
CLIPDROP_API_KEY=your_clipdrop_key

# Cloudinary
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
```
### Run the Server
```
npm run dev
```
### 3️⃣ Client Setup
```
cd ..
cd client
npm install
```
### Setup Environment Variables Create a .env file in the client folder with:
```
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_BASE_URL=your_backend_url
```
### Run the Client
```
npm run dev
```

## 💡 Future Improvements

Add custom user dashboards to track previous AI generations

Integrate AI-powered code assistant module

Introduce team collaboration features with shared projects

Implement billing & subscription with Stripe integration