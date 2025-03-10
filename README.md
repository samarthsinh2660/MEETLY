
<div align="center">
  <!-- Project Banner Image -->
  <img src="https://github.com/user-attachments/assets/fa9988d6-44f6-424b-b08d-1c06cef03164" style="max-width: 100%; height: auto;" alt="Project Banner" />
  
  <h1>Meetly: Next-Gen Video Conferencing</h1>
  
  <div>
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="TypeScript" />
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="Next.js" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="Tailwind CSS" />
  </div>
</div>

## 📋 Table of Contents

1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Quick Start](#quick-start)
5. [Assets & Code](#snippets)
6. [More](#more)

## 🤖 Introduction

Built with the latest Next.js and TypeScript, **Meetly** offers a powerful and scalable video conferencing solution. Secure authentication via Clerk, advanced meeting controls, and real-time interactions are just a few features that make this project stand out.

## ⚙️ Tech Stack

- Next.js
- TypeScript
- Clerk
- getstream
- shadcn
- Tailwind CSS

## 🔋 Features

- **Authentication**: Secure sign-in/up with Clerk.
- **New Meeting**: Start meetings instantly with customizable options.
- **Meeting Controls**: Manage recording, screen sharing, and more.
- **Exit & End Meetings**: Options to leave or end meetings.
- **Schedule Meetings**: Plan future meetings with ease.
- **Past Meetings & Recordings**: Access historical meeting data.
- **Personal Room**: Unique meeting link for instant sessions.
- **Join via Link**: Easily join meetings via shared links.
- **Real-Time Functionality**: Secure, real-time interactions.
- **Responsive Design**: Optimized for all devices.

## 🤸 Quick Start

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

### Cloning the Repository

```bash
git clone https://github.com/samarthsinh2660/MEETLY.git
cd MEETLY
```

### Installation

```bash
npm install
```

### Set Up Environment Variables

Create a new `.env` file in the root directory and add:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

Replace the placeholder values with your actual Clerk and getstream credentials. You can obtain these credentials by signing up on the [Clerk website](https://clerk.com/) and the [getstream website](https://getstream.io/).

### Running the Project

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

## 🕸️ Assets & Code

*For detailed code snippets, refer to the source files under the `app` and `components` directories.*

---

Enjoy building with **Meetly**!
```
