# Campus Bites - Campus Cafeteria Information Website

A small, plain HTML + CSS website for the fictional university cafeteria **Campus Bites**.
Built collaboratively by a team of five using Git and GitHub (feature branches, pull requests,
branch protection and `git rebase`).

## Pages

| Page | File | Owner |
| --- | --- | --- |
| Home | `src/index.html` | Laiba Farooq |
| Menu | `src/menu.html` | Ali Hussain |
| Daily Specials & Deals | `src/deals.html` | Ali Ammar Raza |
| How to Order | `src/order.html` | Muneeb Jahangeer |
| Feedback & Contact | `src/feedback.html` | Muhammad Aun Ahmad |

All pages share one stylesheet: `styles/style.css`.

## Project Structure

```
campus-cafeteria/
├── .gitignore
├── README.md
├── src/
│   ├── index.html
│   ├── menu.html
│   ├── deals.html
│   ├── order.html
│   └── feedback.html
└── styles/
    └── style.css
```

## Branching Strategy

- `main` - production-ready code (3 approvals required)
- `develop` - active development (2 approvals required)
- `feature/<page-name>` - one branch per page, created from `develop`
- `release/v1.0` - QA and final fixes before merging to `main`

## How to Run

No build step is needed. Open `src/index.html` in any web browser.
    
## Team

| Name | GitHub Username | Role |
| --- | --- | --- |
| Muhammad Aun Ahmad |MuhammadAun-UCP| Team Lead |
| Ali Hussain |Ali-hussain0138| Member 1 |
| Ali Ammar Raza | Ali Ammar Raza | Member 2 |
| Laiba Farooq | l1f23bsse0026 | Member 3 |
| Muneeb Jahangeer | muneeb | Member 4 |
