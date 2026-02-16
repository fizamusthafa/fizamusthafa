## Hi there 👋

I'm Fiza Musthafa, and welcome to my GitHub profile!

---

## 📊 GitHub Metrics

![GitHub Metrics](./github-metrics.svg)

---

## 🔧 Setup Notes

This profile uses the [lowlighter/metrics](https://github.com/lowlighter/metrics) GitHub Action to automatically generate contribution statistics.

### Required Secret

To enable automatic metrics generation, you need to set up a GitHub Personal Access Token (PAT):

1. **Create a Personal Access Token:**
   - Go to [GitHub Settings > Developer Settings > Personal Access Tokens > Tokens (classic)](https://github.com/settings/tokens)
   - Click "Generate new token (classic)"
   - Give it a descriptive name (e.g., "GitHub Metrics")
   - Set expiration as needed
   - Select the following scopes:
     - `repo` (Full control of private repositories) - required for accessing contribution data
     - `read:org` (Read organization data) - optional, for organization statistics
     - `read:user` (Read user profile data) - required for user information
     - `read:packages` (Read packages) - optional, for package statistics

2. **Add the token as a repository secret:**
   - Go to your repository Settings > Secrets and variables > Actions
   - Click "New repository secret"
   - Name: `METRICS_TOKEN`
   - Value: Paste your generated token
   - Click "Add secret"

3. **Workflow Schedule:**
   - The metrics are updated automatically every day at midnight UTC
   - You can also trigger updates manually via the "Actions" tab > "GitHub Metrics" workflow > "Run workflow"

### What's Included

The metrics card displays:
- 📈 Contribution activity and patterns
- 💻 Most used programming languages
- 📊 Lines of code statistics
- 🎯 Contribution habits and breakdown (commits, PRs, issues, reviews)
- 🏆 GitHub achievements
- ⭐ Notable contributions

---

<!--
**fizamusthafa/fizamusthafa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
