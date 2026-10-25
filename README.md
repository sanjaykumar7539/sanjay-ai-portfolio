# Sanjay AI Portfolio

Static HTML portfolio and HTML resume. No build or dependencies required.

## Host with GitHub + Vercel
1. Create a GitHub repository named `sanjay-ai-portfolio` in your account.
2. Upload these files at the repository root and commit to `main`.
3. In Vercel, choose Add New Project, import that repository, select Other as framework, and leave build and install commands empty. Deploy.
4. Open the production URL and /resume. Confirm both work without login.

## Future updates
Edit index.html for portfolio content, projects, contacts and animations. Edit resume.html for your resume. Commit to main; the connected Vercel project automatically deploys the update. Previous deployments remain available for rollback.

## Contact messages
FormSubmit sends messages to sanjaykumarsan2007@gmail.com. Inbox activation is still required; migration does not activate email delivery. Activate the form using the email from FormSubmit and test from the new domain. Do not treat acceptance as confirmed inbox delivery.

## Local preview
Run `python -m http.server 8000` here, then open http://localhost:8000. For this basic local server use /resume.html. Vercel cleanUrls supports /resume.

## Deployment status
Portfolio source is committed to this GitHub repository. Vercel project creation previously returned 403 forbidden; no Vercel deployment has been created yet. Import this repository in Vercel to enable automatic deployments.
