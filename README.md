# .github

Tarde-safari-web
Repository navigation
Code
Issues
Pull requests
React web dashboard for trade safari sellers and admins

 0 stars
 0 forks
 0 watching
 3 Branches
 0 Tags
 Activity
 Custom properties
Private repository
Trade-safari/Tarde-safari-web
Name	
Waynemandem
Waynemandem
5 hours ago
README.md
5 hours ago
Repository files navigation
README
🛍️ Trade Safari
A multi-vendor marketplace platform enabling sellers to create stores, manage products & orders, and receive payments, while customers browse and purchase products seamlessly.

Status: 🚀 Active Development | Node.js: ≥ 16.0 | Package Manager: npm

📋 Table of Contents
Quick Start
Tech Stack
Project Structure
Team Setup
Development Workflow
Git & Branch Strategy
Pull Request Guidelines
Environment Variables
Useful Commands
Team Roles
Troubleshooting
Support & Communication
🚀 Quick Start
1. Clone & Install
git clone https://github.com/Trade-safari/Tarde-safari-web.git
cd Tarde-safari-web
npm install
2. Set Environment Variables
Create a .env file in the root directory:

VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
VITE_PAYSTACK_PUBLIC_KEY=your_paystack_public_key
⚠️ Never commit .env to GitHub — Use the team shared credentials document.

3. Run Development Server
npm run dev
The app will start at http://localhost:5173

🛠️ Tech Stack
Layer	Technology
Frontend	React.js, Vite, React Router, Axios
Backend	Supabase, PostgreSQL
Payments	Paystack
Deployment	Vercel
Version Control	Git, GitHub
📁 Project Structure
src/
├── assets/              # Images, icons, static files
├── components/          # Reusable UI components
├── pages/              # Page components (routed)
├── layouts/            # Layout wrappers
├── routes/             # Route definitions
├── services/           # API calls & external services
├── hooks/              # Custom React hooks
├── context/            # Context API providers
├── utils/              # Utility functions
└── features/           # Feature-specific modules
    ├── auth/           # Authentication logic
    ├── products/       # Product management
    ├── stores/         # Store management
    ├── orders/         # Order processing
    ├── seller-dashboard/  # Seller UI
    └── admin/          # Admin panel
👥 Team Setup
Your Team (6 Developers)
Role	Responsibility	Developer(s)
Frontend - Customer	Customer Web, product browsing, checkout	TBD
Frontend - Seller	Seller Dashboard, store management	TBD
Frontend - Admin	Admin Dashboard, user/order management	TBD
Backend	Database, APIs, Supabase setup	TBD
Payments & Orders	Payment integration, order flows	TBD
DevOps & QA	Deployments, testing, documentation	TBD
Action Items:

 Assign team members to roles above
 Create Slack/Discord channel for coordination
 Share Supabase project access with team
 Share Paystack sandbox credentials
🔄 Development Workflow
Step-by-Step Process
Pull Latest Changes

git checkout dev
git pull origin dev
Create Feature Branch (always from dev)

git checkout -b feature/your-feature-name
Make Changes & Commit

git add .
git commit -m "feat: add user authentication"
✅ See Git Commit Guidelines below

Push Your Branch

git push origin feature/your-feature-name
Open a Pull Request

Go to GitHub → Click "New Pull Request"
Set base: dev | Compare: your branch
Follow the PR template (see below)
Wait for Review

At least 1 team member must review before merge
Address feedback promptly
Merge to Dev

Once approved, click "Squash and merge"
Delete branch after merge
🌿 Git & Branch Strategy
Branch Types
Branch	Purpose	Protection
main	🔒 Production-ready code only	Require PR reviews, no direct push
dev	Development integration branch	Require PR reviews
feature/*	Individual feature development	None
bugfix/*	Bug fixes	None
hotfix/*	Critical production fixes	None
Branch Naming Convention
feature/user-authentication    ✅ Good
feature/auth                   ✅ Good
bugfix/payment-redirect        ✅ Good
feature/add-dark-mode          ✅ Good

Feature_UserAuth               ❌ Avoid (use hyphens, not underscores)
FEATURE/AUTH                   ❌ Avoid (lowercase preferred)
dev/feature                    ❌ Avoid (branch from dev, don't include in name)
