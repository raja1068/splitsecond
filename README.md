# SplitSecond – Social Challenge App

**Description:**  
SplitSecond is a vibrant, real‑time social challenge platform. Create, share, and respond to timed challenges, polls, and trivia with friends. Earn XP, badges, and streaks. Built as a mobile‑first web app with a colorful, glass‑morphism UI. (Browser prototype; Android IAP integration documented.)

## Project Structure
/
├── index.html # Main application – fully functional browser prototype
├── privacy-policy.html # Complete privacy policy
├── pom.xml # Maven dependency template for Xiaomi GetApps IAP
├── xiaomi_iap_snippets.md # Android IAP integration snippets & architecture
└── README.md # This file


## Getting Started

1. **Run the prototype** – open `index.html` in any modern browser.  
   No build tools or server required – it works immediately.

2. **Explore the features** – splash screen → onboarding → login (simulated) → home, create challenges, join live challenges, respond, view results, and track progress on your profile and leaderboard.

3. **Android WebView & IAP** – see `xiaomi_iap_snippets.md` and `pom.xml` for integration guidelines.

## Deployment (GitHub Pages)

Simply push the repository to GitHub and enable Pages for the root directory.  
`index.html` will serve as the entry point.

## Important Notes

- This is a **browser prototype** – real IAP and backend services are not active.
- All data is stored in memory (localStorage demo available).
- For production, connect to Firebase / Supabase and implement server‑side purchase validation.
- Review `privacy-policy.html` and update placeholders before publishing.

---

**Made with ❤️ for viral, safe social challenges.**
