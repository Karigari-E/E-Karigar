# E-Karigar

A verified local-services app for Nepal. Customers find nearby, identity-verified technicians for everyday jobs and see price estimates, availability, previous work and reviews before booking.

**Launch plan:** Kathmandu, starting with one neighborhood and about 30 service providers, then expanding.

## Services

- Plumber
- Electrician
- AC repair
- Bike repair
- Cleaning
- Electronics repair
- Carpenter

## Getting started

```bash
git clone https://github.com/Karigari-E/E-Karigar.git
cd E-Karigar
```

Setup and run instructions for the project will be added here as the stack is finalized.

## How we work (please read)

1. Never push directly to `main`.
2. Get the latest code before every task:
   ```bash
   git checkout main
   git pull
   ```
3. Create a branch for your task:
   ```bash
   git checkout -b feature/short-task-name
   ```
4. Commit your work with a clear message:
   ```bash
   git add .
   git commit -m "Short message about what you changed"
   ```
5. Push your branch and open a pull request on GitHub:
   ```bash
   git push -u origin feature/short-task-name
   ```
6. Ask a teammate to review. Do not merge your own pull request without a review.

### Branch names

| Prefix | Use for |
|--------|---------|
| `feature/` | new features, e.g. `feature/login-page` |
| `fix/` | bug fixes, e.g. `fix/booking-bug` |
| `docs/` | documentation, e.g. `docs/readme-update` |

### Rules

- One task = one branch = one pull request.
- Never commit passwords, API keys or `.env` files.
- Do not use `git push --force` on `main`.
- Pick a task from the **Issues** tab and assign it to yourself before starting, so two people don't do the same work.
