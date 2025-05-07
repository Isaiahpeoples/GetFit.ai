<div align="center" id="toc">
<ul style="list-style: none">
<summary>
 <h1>GetFit.ai</h1>
</summary>
</ul>
</div>

<br>

A modern AI fitness assistant that delivers personalized workouts, meal plans, and real-time coaching through voice interaction—built with cutting-edge tech like Gemini AI, Vapi, and Next.js to help users achieve healthier lives effortlessly.

## 🚀 Technologies Used 🚀

- **Next.js**: React framework for building the frontend and API routes
- **Tailwind CSS & Shadcn UI**: For styling and UI components
- **Clerk**: Authentication and user management
- **Vapi**: Voice agent platform for conversational AI
- **Convex**: Real-time database
- **Gemini AI**: Large Language Model for generating personalized fitness programs

## 📑 Key Features 📑

- **Smart AI Assistant**: Engage in conversation with an AI that asks about your fitness goals, physical condition, and preferences
- **Personalized Workout Plans**: Get custom exercise routines based on your fitness level, injuries, and goals
- **Diet Recommendations**: Receive personalized meal plans accounting for your allergies and dietary preferences
- **User Authentication**: Sign in with GitHub, Google, or email/password
- **Program Management**: Create and view multiple fitness programs with only the latest one active
- **Responsive Design**: Beautiful UI that works across all devices

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

## 📂 Project Structure 📂

- **/app: Main application directory with API routes and pages**

- **/components: UI components and forms**

- **/lib: Logic, helpers, and integrations (API calls, auth, utilities)**

- **/convex: Convex backend functions for program handling**

- **/public: Static assets and images**

## 📌 Learn More 📌

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs)
- [Clerk Documentation](https://clerk.com/docs)
- [Vapi Documentation](https://docs.vapi.ai)
- [Convex Documentation](https://docs.convex.dev)
- [Gemini AI Documentation](https://ai.google.dev/gemini-api)

### ⭐️ Support ⭐️
If you found this project helpful or interesting, please give it a ⭐️! Your support helps to grow the project and boosts visibility. Thank you!