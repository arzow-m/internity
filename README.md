### Potential File Structure
```faang-interview-bot/
│
├── frontend/                  # React frontend (chat UI, scoring, etc.)
│   ├── public/                # Static assets
│   ├── src/
│   │   ├── components/        # Reusable React components (ChatBox, ScoreCard, etc.)
│   │   ├── pages/             # Main routes or views
│   │   ├── hooks/             # Custom React hooks (e.g., useChat)
│   │   ├── api/               # Frontend API calls to backend
│   │   ├── styles/            # Tailwind config or custom CSS
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── tailwind.config.js
│   └── package.json
│
├── backend/                   # FastAPI backend
│   ├── app/
│   │   ├── routes/            # API endpoints (e.g., /evaluate, /ask)
│   │   ├── services/          # Core logic (LLM prompts, scoring, etc.)
│   │   ├── models/            # Pydantic models (input/output schemas)
│   │   ├── database/          # DB connection logic (Supabase/MongoDB)
│   │   └── main.py            # FastAPI app entry point
│   ├── requirements.txt       # Backend dependencies
│   └── .env                   # API keys, secrets
│
├── shared/                    # (Optional) Shared prompt templates, config, docs
│   ├── prompts/
│   ├── constants/
│   └── README.md
│
├── .gitignore
├── README.md
└── LICENSE
```

### GitHub Cheat Sheet for Collaboration
```
# ✅ Clone the repository
git clone https://github.com/your-username/your-repo.git
cd your-repo

# ✅ Create and switch to a new branch
git checkout -b feature/your-feature-name

# ✅ Make changes to your files...

# ✅ Stage your changes
git add .

# ✅ Commit your changes with a message
git commit -m "Add: your short description here"

# ✅ Push your branch to GitHub
git push origin feature/your-feature-name

# ✅ Go to GitHub and open a Pull Request (PR)
#    → GitHub will suggest "Compare & pull request"
#    → Write a title and description, then submit

# ✅ After your teammate reviews and approves the PR, you or they can merge it

# ✅ To update your local main branch:
git checkout main
git pull origin main

# ✅ To delete the feature branch locally and remotely after merging:
git branch -d feature/your-feature-name
git push origin --delete feature/your-feature-name
```
