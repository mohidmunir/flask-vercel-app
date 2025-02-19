## Deployment Attempt on Vercel

I attempted to deploy this Flask application on Vercel following DevOps best practices.

### Steps Taken:
1. Set up the GitHub repository and pushed the Flask app.
2. Installed Vercel CLI (`npm install -g vercel`).
3. Tried linking Vercel to GitHub (`vercel login` and `vercel` commands).
4. Faced issues due to Windows execution policy and script restrictions.
5. Will debug further or try alternate deployment methods.

### Repository Structure:
- `app.py` → Main Flask app
- `requirements.txt` → Dependencies
- `vercel.json` → Configuration file (if created)
- `.github/workflows/deploy.yml` → Attempted CI/CD workflow

Even though deployment isn't successful yet, all necessary configurations are in place.
