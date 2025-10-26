# S3-Cloudflare-GitHub-Actions


Slide 1 — S3-Cloudflare-GitHub-Actions

Title: Scalable Static Website with S3 + Cloudflare + GitHub Actions
Subtitle: Auto-deploy a static website with global CDN and HTTPS
Your Name: Sufiyan
Date: [22-10-25]

Slide 2 — Objective

Objective:

Host and auto-deploy a static website using AWS S3 (free tier).

Ensure global CDN and HTTPS via Cloudflare.

Automate deployments via GitHub commits.

Slide 3 — Tools Used

AWS S3 (Free) — Static hosting and versioning

Cloudflare (Free) — Global CDN & HTTPS (Flexible TLS)

GitHub Actions — CI/CD automation

HTML / CSS / Bash — Website development & automation

Slide 4 — Mini Guide / Workflow

Create a static HTML site and push to GitHub.

Set up GitHub Actions to sync content to the S3 bucket automatically.

Enable S3 static website hosting with index.html.

Connect to Cloudflare (optional for free TLS / caching).

Enable cache settings & versioning for scalable deployments.

Slide 5 — GitHub Actions CI/CD Workflow

Workflow Steps:

Checkout code from GitHub.

Configure AWS credentials via aws-actions/configure-aws-credentials.

Sync website folder to S3 using aws s3 sync.

Auto-deploy triggered on every push to main branch.

(Optional: include a screenshot of your deploy.yml workflow here)

Slide 6 — S3 Website Hosting

S3 Bucket: sufiyan-cf-web-2025

Static website hosting enabled

Index Document: index.html

Error Document: error.html (optional)

Versioning enabled for rollback

Live Website:
http://sufiyan-cf-web-2025.s3-website-us-east-1.amazonaws.com/

(Include a screenshot of your live site)

Slide 7 — Cloudflare Integration (Optional)

Proxied traffic for HTTPS & caching (Flexible TLS).

Added CNAME or A records (if using a custom domain).

Enabled Always Use HTTPS & Automatic HTTPS Rewrites.

Slide 8 — Benefits

Fully automated deployment via GitHub Actions.

Scalable and versioned static hosting via S3.

Global CDN & HTTPS via Cloudflare.

Free solution with minimal operational overhead.

Slide 9 — Deliverables / Summary

GitHub Actions CI/CD workflow → Auto-deploys to S3.

Cloudflare + S3 integration → Optional CDN & SSL.

Live website link → S3 URL

Screenshots → Deployment report & live website preview.
