# Campus Bites - Campus Cafeteria Information Website

A small, plain HTML + CSS website for the fictional university cafeteria **Campus Bites**.
Built collaboratively by a team of five using Git and GitHub (feature branches, pull requests,
branch protection and `git rebase`).

## Pages

| Page | File | Owner |
| --- | --- | --- |
| Home | `src/index.html` | Team Lead |
| Menu | `src/menu.html` | Member 1 |
| Daily Specials & Deals | `src/deals.html` | Member 2 |
| How to Order | `src/order.html` | Member 3 |
| Feedback & Contact | `src/feedback.html` | Member 4 |

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
| (fill in) | (fill in) | Team Lead |
| (fill in) | (fill in) | Member 1 |
| (fill in) | (fill in) | Member 2 |
| (fill in) | (fill in) | Member 3 |
| (fill in) | (fill in) | Member 4 |
