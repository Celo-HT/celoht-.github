# Deployment Guide

## Overview

This document explains how CeloHT projects can be deployed across supported hosting platforms.

Deployment methods may vary depending on the repository.

---

## Supported Platforms

- GitHub Pages
- Vercel
- Netlify

---

# GitHub Pages

GitHub Pages is recommended for documentation websites and static projects.

## Requirements

- GitHub repository
- Main branch
- GitHub Pages enabled

## Steps

1. Open the repository.
2. Go to **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/docs** or **/root**
5. Save the configuration.
6. Wait for the deployment to complete.

Your website will become available at:

```
https://celo-ht.github.io/<repository-name>/
```

---

# Vercel

Vercel is recommended for Next.js and modern web applications.

## Requirements

- GitHub account
- Vercel account
- Connected repository

## Deployment

1. Sign in to Vercel.
2. Import the GitHub repository.
3. Select the repository.
4. Configure environment variables if required.
5. Click **Deploy**.

Future updates pushed to the default branch will automatically trigger new deployments.

---

# Netlify

Netlify is recommended for static websites.

## Requirements

- GitHub account
- Netlify account

## Deployment

1. Log in to Netlify.
2. Click **Add new site**.
3. Choose **Import from Git**.
4. Select GitHub.
5. Choose the repository.
6. Configure the build settings if necessary.
7. Click **Deploy site**.

---

# Custom Domains

Projects may use custom domains when available.

Example:

```
https://example.org
```

Domain configuration depends on the hosting provider.

---

# Environment Variables

Some applications may require environment variables.

Example:

```
NODE_ENV=production
NEXT_PUBLIC_API_URL=https://api.example.org
```

Never commit secrets, private keys, API keys, or passwords to the repository.

---

# Continuous Deployment

Most CeloHT repositories support automatic deployment after changes are merged into the default branch.

Typical workflow:

1. Commit changes
2. Push to GitHub
3. CI workflow runs
4. Build
5. Deploy
6. Site updated

---

# Verification

After deployment, verify:

- Website loads correctly
- Links work
- Images display properly
- Documentation is accessible
- Mobile responsiveness
- HTTPS is enabled

---

# Troubleshooting

## Build failed

Check:

- Build logs
- Dependency versions
- Configuration files

---

## Page not found

Verify:

- Repository name
- GitHub Pages configuration
- Branch selection
- Folder selection

---

## Deployment failed

Review:

- GitHub Actions logs
- Vercel logs
- Netlify logs

Resolve any reported errors before redeploying.

---

# Best Practices

- Deploy from the default branch.
- Keep dependencies updated.
- Use HTTPS.
- Protect sensitive environment variables.
- Test locally before deployment.
- Monitor deployments regularly.

---

# Support

If deployment issues cannot be resolved, open a GitHub Issue with:

- Repository name
- Hosting platform
- Error message
- Build logs
- Steps to reproduce