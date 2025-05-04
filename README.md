# 🎯 Skillkart – Personalized Learning Roadmaps

Skillkart is a personalized learning platform where learners can build and follow custom roadmaps to master new skills like Web Development, UI/UX Design, or Data Science. 

🚀 Built with [Next.js](https://nextjs.org/) and [Supabase](https://supabase.com/)  
📦 Includes authentication, curated content, roadmap progress tracking, community support, and gamification.

---

## 🌟 Features

### 👤 Learner Profiles
- Sign up and log in via Supabase Auth.
- Set your interests, learning goals, and available weekly time.
- Get a personalized skill roadmap.

### 🧭 Roadmap Engine
- Generates a week-wise learning plan (e.g., 10-week UI/UX journey).
- Shows each module's content.
- Track your progress: `Completed` | `In Progress`

### 📚 Curated Content
- Content Curators (Admins) can upload:
  - Videos
  - Blogs
  - Quizzes
- Each roadmap step includes 2–3 high-quality resources.

### 💬 Peer Support
- Discussion threads per roadmap.
- Learners can ask/answer questions.
- Community-powered learning.

### 🎮 Gamification
- XP points for module completion.
- Badges for:
  - Topic mastery
  - Community engagement

---

## 🛠️ Tech Stack

| Tech           | Usage                            |
|----------------|----------------------------------|
| Next.js        | Frontend + Server-side rendering |
| Supabase       | Auth, Database, Video Storage    |
| Tailwind CSS   | Styling                          |
| React Query    | Data fetching & caching          |
| Markdown       | Content formatting (optional)    |

---

## 🔐 Environment Variables

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key

## ⚙️ How to Setup and Run the Project Locally


# 1. Clone the repo

# 2. Install dependencies
npm install

# 3. Set up environment variables
# See .env.local section above

# 4. Run the development server
npm run dev

