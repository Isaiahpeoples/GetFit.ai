<div align="center" id="toc">
<ul style="list-style: none">
<summary>
 <h1>GetFit.ai</h1>
</summary>
</ul>
</div>

<div align="center">

[![Built With](https://img.shields.io/badge/Built_with-Next.js-brightgreen)](https://nextjs.org/)
[![Gemini AI](https://img.shields.io/badge/AI-Gemini_AI-brightgreen)](https://ai.google.dev/gemini-api)
[![Clerk Auth](https://img.shields.io/badge/Auth-Clerk-brightgreen)](https://clerk.com/)
[![Voice Enabled](https://img.shields.io/badge/Voice_Via-Vapi-brightgreen)](https://vapi.ai/)
[![Convex](https://img.shields.io/badge/Database-Convex-brightgreen)](https://convex.dev)

[![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)](https://github.com/Isaiahpeoples/GetFit.ai)
[![Live](https://img.shields.io/badge/Live-Preview-brightgreen)](https://get-fit-ai.vercel.app/)

</div>
<br/>

## 💡 Project Overview

**GetFit.ai** is a modern AI-powered fitness assistant that offers personalized workouts, diet plans, and real-time voice coaching. Built with **Next.js**, **Tailwind CSS**, **Vapi**, and **Gemini AI**, it allows users to converse naturally with an AI agent to receive custom health and fitness programs—all with responsive design and seamless authentication.

<br/>

## 🚀 Technologies Used

| Technology     	| Description                                                                        	|
|--------------------|----------------------------------------------------------------------------------------|
| **Next.js**    	| ⚛️ React framework for full-stack application and routing.                         	|
| **Tailwind CSS**   | 🎨 Utility-first CSS framework for styling.                                         	|
| **Shadcn UI**  	| 🧩 Prebuilt UI components integrated with Tailwind CSS.                            	|
| **Clerk**      	| 🔐 Authentication system with social login options.                               	|
| **Vapi**       	| 🗣️ AI-powered voice interface for conversation-based interactions.                 	|
| **Convex**     	| ⚡ Real-time backend and database for program storage.                             	|
| **Gemini AI**  	| 🧠 LLM used for creating personalized workout and meal plans.                      	|

<br/>

## 📸 Project Screenshot

![GetFit.ai Preview](https://online-project-images.s3.us-east-2.amazonaws.com/getfit/GetFit-1.png)

*A voice-first fitness assistant powered by AI, showing personalized programs and coaching interface.*

<br/>

## 📑 Key Features

- 🎤 **Voice-Based AI Coaching** – Converse with your assistant about goals, routines, and preferences.
- 🏋️ **Custom Workouts** – Personalized plans based on user input, goals, and injuries.
- 🥗 **Smart Meal Plans** – Tailored to dietary needs, allergies, and preferences.
- 🔐 **Clerk Authentication** – Secure user login via Google, GitHub, or email/password.
- 📋 **Program Management** – View history, track active programs, and switch as needed.
- 📱 **Fully Responsive** – Optimized layout across phones, tablets, and desktops.

<br/>

## 🔧 Installation & Setup 🔧

1. **Clone the repository**:
```bash
git clone https://github.com/Isaiahpeoples/GetFit.ai.git
cd nextjs-store
```

2. **Install dependencies**:
```bash
npm install
```

3. **Environment variables: Configure the .env file with the following keys**:

```js
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Clerk Redirect URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Vapi Voice AI
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
NEXT_PUBLIC_VAPI_API_KEY=

# Convex Database
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
```

4. **Start the development server**:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

<br/>

## 📂 Project Structure 📂

- **/app: Next.js routes and API endpoints**

- **/components: UI components and forms**

- **/lib: Logic, helpers, and integrations (API calls, auth, utilities)**

- **/convex: Convex backend functions for program handling**

- **/public: Static assets and images**

<br/>

## 📌 Learn More 📌

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs)
- [Clerk Documentation](https://clerk.com/docs)
- [Vapi Documentation](https://docs.vapi.ai)
- [Convex Documentation](https://docs.convex.dev)
- [Gemini AI Documentation](https://ai.google.dev/gemini-api)

<br/>

## 🌐 Live Demo

Check out the live version:  
👉 [GetFit.ai Live Demo](https://get-fit-ai.vercel.app/)

<br/>

### ⭐️ Support ⭐️
If you found this project helpful or interesting, please give it a ⭐️! Your support helps to grow the project and boosts visibility. Thank you!
