Short answer: yes — absolutely change your README 👍
Right now your README screams “default Next.js starter”, while your Devpost write-up is 100× stronger and actually tells the story of the product.
If a recruiter, judge, or club lead opens your GitHub today, they’ll miss why this project matters.
Let’s fix that.
What’s wrong with your current README (no shade 😅)
Your current README:
❌ Looks auto-generated
❌ Says nothing about Career Compass
❌ Hides the AI + product thinking
❌ Doesn’t credit collaboration clearly
❌ Feels like a tutorial project, not a real product
Your Devpost text:
✅ Clear problem → solution → impact
✅ Real user pain
✅ AI + systems thinking
✅ Trust, privacy, fairness (huge green flags)
You want GitHub to match Devpost energy.
What your README should do
Your README should answer, in 10 seconds:
What is this?
Why does it exist?
What makes it different?
How was it built?
Who built it?
Everything else is secondary.
Recommended README structure (copy-paste friendly)
Below is a polished, recruiter-ready README based on your exact Devpost content.
You can paste this and tweak wording if you want.
⭐ Career Compass
Career Compass is an AI-powered campus event discovery platform designed to help students find events and clubs that actually align with their major, career goals, and interests — without getting lost in noisy social media feeds.
Built by first-year international students who personally struggled to navigate campus life.
🚩 The Problem
Students are overwhelmed by hundreds of events with little guidance on relevance
First-year and upper-year students miss valuable opportunities
Social media is noisy and unreliable for event discovery
Event attendance favors popularity over actual value
Smaller clubs struggle to reach the right audience
💡 The Solution
Career Compass uses AI-powered personalization to:
🎯 Recommend events based on major & career path
🤖 Learn from user behavior and event ratings
⚖️ Promote events based on quality, not popularity
🌱 Give smaller or newer clubs a fair chance
📅 Reduce overlap and help students plan efficiently
🛠️ How We Built It
Next.js – frontend & server-side rendering
TypeScript – type-safe development
Tailwind CSS + shadcn/ui – clean, modern UI
Firebase – authentication & database
Gemini API – AI-powered recommendations
🚧 Challenges
First-time API integration required careful fallback planning
Ensuring the app remained functional without AI availability
Refining UX while balancing speed and clarity
🏆 What We’re Proud Of
🔐 Secure & Verified Ratings
Users can only rate events they actually attend using a unique access token provided at the event.
Comments are disabled to prevent misuse or harassment.
🔁 Reliable Fallback System
If the AI is unavailable, the app intelligently ranks events using career paths and historical ratings.
🛡️ Privacy-First Design
Firebase authentication
No password access
Minimal data collection (email, major, career path)
📚 What We Learned
Practical AI integration using Gemini
Firebase authentication & data modeling
Designing real-world, user-focused systems under time constraints
🚀 What’s Next
Launching at UBC through direct club partnerships
Introducing a buddy system to connect students attending similar events
Expanding personalization and recommendation accuracy
👥 Team
Built collaboratively with @vanyasharmaa
🧑‍💻 Running Locally
npm install
npm run dev
Visit http://localhost:3000
