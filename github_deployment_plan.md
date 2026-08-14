# 🛠️ GitHub Pages Deployment Blueprint

## 🎯 Target Architecture
1. **GitHub Organization:** `geographerscraft` or `geographers-craft` (Fallback: `sounny/geographerscraft`).
2. **Repository Name:** `geographerscraft`
3. **Live Web URL:** `https://geographerscraft.github.io` (or `https://sounny.github.io/geographerscraft`)

## 🔑 Administrative Roles & Co-Ownership Instructions
- **Primary Host / Maintainer:** Dr. Moulay Anwar Sounny-Slitine (`sounny`)
- **Co-Owners / Admins:** Dr. Ken Foote (`ken.foote@uconn.edu`), Dr. Peter H. Dana (`pdana@pdana.com`)

### GitHub Account Setup Instructions for Co-Authors
1. **Existing GitHub Account:** Provide username/handle (e.g. `@kenfoote` or `@peterdana`).
2. **New GitHub Account Creation:**
   - Navigate to [https://github.com/signup](https://github.com/signup)
   - Enter email address, choose a password, and select a username.
   - Complete email verification.
3. **Invitation Process:** Once handles are received, send repository/organization co-ownership admin invites via GitHub settings.

## 📝 Deployment Steps for Agent
1. **Receive & Extract Archive:** Unzip the `.zip` archive from Ken Foote into `archive/`.
2. **Link Integrity Audit:** Run a python script to test for broken relative links or absolute legacy UT/UConn links (`http://www.utexas.edu/...` or `http://www.uconn.edu/...`).
3. **Open-Source License:** Add `LICENSE` (Creative Commons Attribution 4.0 International - CC BY 4.0) preserving original authorship credits to Ken Foote, Peter Dana, and contributors.
4. **Git Repository Setup:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Preserving The Geographer's Craft OER Archive"
   git remote add origin https://github.com/sounny/geographerscraft.git
   git branch -M main
   git push -u origin main
   ```
5. **Enable GitHub Pages:** Set source branch to `main` root `/` in repository settings.
