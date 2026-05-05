# Setup Guide & Prerequisites

Before getting started with this Machine Learning Knowledge Base and publishing it to the web, you'll need to set up a few tools and accounts.

## 1. Install Obsidian
Obsidian is the core application used to write, view, and link your notes.
- **Download:** Go to [obsidian.md](https://obsidian.md/) and download the installer for your operating system.
- **Install:** Run the installer and open the app.
- **Usage:** Select "Open folder as vault" and choose the `ml_knowledge` directory.

## 2. Install Gemini CLI
Gemini CLI is your interactive assistant for executing tasks and helping manage this project.
- **Prerequisites:** Ensure you have Node.js installed.
- **Install Command:** Run `npm install -g @google/gemini-cli` in your terminal.
- **Authentication:** Follow the prompts after typing `gemini` to log in and set up your environment.

## 3. Sign Up for GitHub
GitHub will host the source code of your notes (the markdown files) and trigger your website deployments.
- **Sign Up:** Visit [github.com](https://github.com/) and create a free account if you don't already have one.
- **Setup:** Once logged in, you can create new repositories to store your vaults.

## 4. Sign Up for Vercel
Vercel is the platform that will build and host your Obsidian vault as a fast, public website using Quartz.
- **Sign Up:** Go to [vercel.com](https://vercel.com/) and sign up. **Tip:** Choose "Continue with GitHub" to easily link your Vercel account to your repositories.
- **Deploying:** You can import your GitHub repositories directly in Vercel to automatically build and deploy your Quartz site every time you push changes.