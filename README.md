# New-Leaf-Oasis-Website
A website for a business that provides residential placement for young mothers and children and also women coming from domestic abuse situations while they get assessed by social workers.

🌿 New Leaf Oasis Website
A modern, accessible informational website for New Leaf Oasis Limited, a residential placement service supporting:
Young mothers and their children
Women escaping domestic abuse
Built with Next.js + Tailwind CSS, this project is designed to be simple, low-cost, and easy to deploy (Cloudflare Pages / Vercel).

🛠 Tech Stack
Framework: Next.js 14 (App Router)
Styling: Tailwind CSS
Deployment: Cloudflare Pages / Vercel / Netlify
Contact Forms: Formspree (free tier, configurable)
🚀 Getting Started

1. Prerequisites
Node.js v18 or newer
Git
VS Code
2. Clone the repository
git clone https://github.com/YOUR-USERNAME/new-leaf-oasis-website.git
cd new-leaf-oasis-website
3. Install dependencies
npm install
4. Run the dev server
npm run dev
Visit http://localhost:3000
5. Create .env.local
Copy .env.example → .env.local and add your Formspree endpoint:
NEXT_PUBLIC_FORMSPREE_ENDPOINT=https://formspree.io/f/yourid
6. Build for production
npm run build
npm run start
📂 Project Structure
src/
  app/
    layout.tsx      # Global layout
    page.tsx        # Homepage
  components/
    Header.tsx      # Sticky header with hide/show scroll
    Sections.tsx    # Hero, Services, Values sections
    ContactForm.tsx # Contact & referral form
  styles/
    globals.css     # Tailwind + custom styles
.env.example        # Example environment variables
README.md           # This file

🌐 Deployment
Option A: Cloudflare Pages (Free)
Connect your GitHub repo in Cloudflare → Build command: npm run build → Output: .next
Cloudflare auto-detects Next.js
Option B: Vercel Hobby (Free)
One-click import GitHub repo → deploy

📌 Git & GitHub Workflow
# Check status
git status

# Stage all changes
git add .

# Commit with a message
git commit -m "Initial commit"

# Push to GitHub (main branch)
git push origin main
Pro tip: use VS Code Source Control panel to stage/commit/push without CLI.

📄 License
MIT License – free to use, modify, and deploy.
✨ New Leaf Oasis – turning a new page for mothers, children, and women rebuilding their lives.
