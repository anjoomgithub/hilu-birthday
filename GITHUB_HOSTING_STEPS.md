# How to Host Your Website on GitHub (Free)

Follow these simple steps to put your beautiful birthday website online!

## Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in (or create an account).
2. Click the **+** icon in the top-right corner and select **New repository**.
3. **Repository name**: Give it a name (e.g., `hilu-birthday-wish`).
4. **Public/Private**: Choose **Public** (required for free hosting).
5. Leave the other settings (README, .gitignore) unchecked.
6. Click **Create repository**.
7. Keep this page open! You will need the URL shown (it looks like `https://github.com/your-username/hilu-birthday-wish.git`).

## Step 2: Prepare Your Local Code
I have already prepared your files. Now we need to upload them.
Open your terminal (or let me know, and I can try to run these for you if you provide the URL from Step 1).

Run these commands one by one in your terminal:

```bash
# 1. Initialize Git
git init

# 2. Add all your files
git add .

# 3. Commit your changes
git commit -m "Initial upload for Hiluuu's birthday site"

# 4. Rename the branch to main (best practice)
git branch -M main
```

## Step 3: Connect and Upload
Now replace `YOUR_REPO_URL` with the link you copied in Step 1.

```bash
# 5. Link your local folder to GitHub
git remote add origin YOUR_REPO_URL
# Example: git remote add origin https://github.com/Anjoom/hilu-birthday.git

# 6. Push your code online
git push -u origin main
```

## Step 4: Turn on the Website (GitHub Pages)
1. Go back to your repository page on GitHub.
2. Click on the **Settings** tab (gear icon).
3. On the left sidebar, click on **Pages**.
4. Under **Build and deployment** > **Source**, check that it says "Deploy from a branch".
5. Under **Branch**, select **main** and ensuring the folder is **/(root)**.
6. Click **Save**.

## Step 5: Share the Link!
Wait about 1-2 minutes. Refresh the **Pages** settings page.
You will see a bar at the top saying:
**"Your site is live at: https://your-username.github.io/hilu-birthday-wish/"**

Copy that link and send it to Hiluuu! ❤️
