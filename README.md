# Ahmed Trading - Website Deployment Guide

This repository contains the static HTML, CSS, and JS files for the **Ahmed Trading and Services** website. 

Follow the step-by-step instructions below to deploy this website live to the internet using GitHub and Vercel.

---

## Step 1: Uploading to GitHub Manually

GitHub is where you will store your website's code online. 

1. **Create a GitHub Account (If you don't have one):**
   * Go to [github.com](https://github.com/) and click **Sign Up**.
   * Follow the prompts to create your account and verify your email.

2. **Create a New Repository:**
   * Once logged in, click the **`+`** icon in the top right corner and select **New repository**.
   * **Repository name:** Type `ahmed-trading-website` (or any name you like).
   * **Visibility:** You can choose **Public** (anyone can see the code) or **Private** (only you can see the code). Either works for Vercel.
   * **Initialize:** Do **NOT** check "Add a README file" right now. Leave it blank.
   * Click the green **Create repository** button.

3. **Upload Your Files:**
   * On the next screen, look for the text: *"…or create a new repository on the command line"* and *"…or push an existing repository from the command line"*.
   * Right above these sections, look for the link that says: **"uploading an existing file"** and click it.
   * Now, open the `ahmedtrdg-html` folder on your computer (where all our HTML files and the `assets` folder are located).
   * Highlight **all** the files and folders inside `ahmedtrdg-html` (including `index.html`, `about.html`, `css`, `assets`, and this `README.md`), and **drag and drop** them into the GitHub upload area in your browser.
   * Wait for all files to finish uploading.
   * Scroll down to "Commit changes", type a message like *"Initial website upload"*, and click the green **Commit changes** button.

Congratulations! Your code is now safely backed up on GitHub.

---

## Step 2: Deploying to Vercel

Vercel is a hosting platform that will take your code from GitHub and make it a live website.

1. **Create a Vercel Account:**
   * Go to [vercel.com](https://vercel.com/) and click **Sign Up**.
   * Important: Choose **Continue with GitHub**. This links your new Vercel account directly to your GitHub account so they can talk to each other.
   * Authorize Vercel to access your GitHub account.

2. **Import Your GitHub Project:**
   * Once logged into the Vercel dashboard, click the black **Add New...** button and select **Project**.
   * On the "Import Git Repository" page, look for your newly created `ahmed-trading-website` repository.
   * Click the **Import** button next to it.

3. **Deploy the Website:**
   * You will see a "Configure Project" screen. 
   * You do **not** need to change any settings (Framework Preset should be "Other", Build Command should be empty).
   * Simply click the blue **Deploy** button.
   * Vercel will now build your site. You will see some confetti and a "Congratulations!" message when it's done (usually takes less than 30 seconds).

4. **Get Your Live Link:**
   * Click **Continue to Dashboard**.
   * On your project dashboard, look for the **Domains** section. You will see a web address (e.g., `ahmed-trading-website.vercel.app`).
   * **Click that link**! Your website is now live on the internet!

---

## Step 3: Update This README

Now that you have your live website link, it's good practice to add it to your documentation.

1. Go back to your repository on [github.com](https://github.com/).
2. Click on the `README.md` file to view it.
3. Click the **pencil icon** ✏️ in the top right corner of the file to edit it.
4. Replace the bracketed text below with your actual Vercel link:

**Live Website Link:** [Insert your Vercel Link Here, e.g., https://ahmed-trading-website.vercel.app]

5. Scroll down to the bottom of the page and click the green **Commit changes...** button to save.

---
*If you want to update the website later, simply upload the new files directly to GitHub using the "Add File" -> "Upload files" button on your repository page, and Vercel will **automatically** update the live site within seconds!*
