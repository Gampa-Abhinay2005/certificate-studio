# Certify — Certificate Studio

A lightweight, client-side certificate generator. Edit certificate details, preview the design live, download a high-resolution PNG, or print/save as PDF.

## Run locally

Open `index.html` in a modern web browser. No server or installation is needed.

## Publish online with GitHub Pages

### 1. Create a GitHub repository

1. Sign in to [GitHub](https://github.com/new) and create a new repository named `certificate-studio`.
2. For the simplest first push from your computer, leave **Add a README file** unchecked so the repository starts empty.
3. A public repository is the easiest option for GitHub Pages on GitHub Free.

### 2. Push this folder with Git

Install Git if it is not already installed. Open a terminal in this folder (the folder containing `index.html`) and run these commands, replacing `YOUR-USERNAME` with your GitHub username:

```bash
git init
git branch -M main
git add .
git commit -m "Add certificate studio website"
git remote add origin https://github.com/YOUR-USERNAME/certificate-studio.git
git push -u origin main
```

If Git asks you to identify yourself for the commit, configure your name and email using the instructions shown by Git. Authenticate to GitHub through Git's supported sign-in flow; do not put your password or token in this README.

### 3. Turn on GitHub Pages

1. Open the repository on GitHub.
2. Choose **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then click **Save**.
5. Wait for the Pages deployment to finish. The website URL will be:

   `https://YOUR-USERNAME.github.io/certificate-studio/`

Replace `YOUR-USERNAME` with your GitHub username.

### Update the live site later

Edit the files, then run:

```bash
git add .
git commit -m "Update certificate studio"
git push
```

GitHub Pages will publish the changes from the configured branch.

## Privacy note

The certificate generator processes certificate details in the browser and does not submit them to an application server. The published website itself is public, so do not store private information in the repository.
