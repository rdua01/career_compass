# ⭐ Career Compass

**Career Compass** is an AI-powered campus event discovery platform designed to help students find events and clubs that actually align with their **major, career goals, and personal interests** — without getting lost in noisy social media feeds.

Built by first-year international students who personally struggled to navigate campus life.

---

## 🚩 The Problem

- Students are overwhelmed by hundreds of campus events with little guidance on relevance  
- First-year and upper-year students miss valuable career and academic opportunities  
- Social media feeds are noisy and unreliable for event discovery  
- Event attendance often favors popularity over actual value  
- Smaller clubs struggle to reach the right audience  

---

## 💡 The Solution

**Career Compass** uses AI-powered personalization to:

- 🎯 Recommend events based on **major & career path**
- 🤖 Learn from user behavior and verified event ratings
- ⚖️ Promote events based on **quality, not popularity**
- 🌱 Give smaller or newer clubs a fair chance to reach students
- 📅 Reduce event overlap and help students plan efficiently

---

## 🛠️ How We Built It

- **Next.js** – frontend & server-side rendering  
- **TypeScript** – type-safe development  
- **Tailwind CSS + shadcn/ui** – modern, responsive UI  
- **Firebase** – authentication & database  
- **Gemini API** – AI-powered event recommendations  

---

## 🚧 Challenges We Faced

- First-time integration with external APIs  
- Designing reliable fallback systems in case of AI downtime  
- Balancing frontend polish with rapid iteration during development  

---

## 🏆 Accomplishments

### 🔐 Secure & Verified Ratings
Users can only rate events they actually attend using a **unique access token** provided by clubs at each event.  
Comments are disabled to prevent misuse or harassment.

### 🔁 Reliable Fallback System
If the AI model is unavailable, the app continues to function by ranking events using **career paths and historical ratings**.

### 🛡️ Privacy-First Design
- Firebase authentication  
- No access to user passwords  
- Minimal data collection (email, major, career path only)

---

## 📚 What We Learned

- Practical AI integration using the Gemini API  
- Firebase authentication and data modeling  
- Designing real-world, user-focused systems under time constraints  

---

## 🚀 What’s Next

- Launching across **UBC** through direct club partnerships  
- Introducing a **buddy system** to help students connect at shared events  
- Expanding AI personalization and recommendation accuracy  

---

## 👥 Team

Built collaboratively with **[@vanyasharmaa](https://github.com/vanyasharmaa)**

---

## 🧑‍💻 Running the Project Locally

```bash
npm install
npm run dev
