# mahfouz-z.github.io

Personal academic website for Mohamed M. Shahawy — CS PhD Candidate at EPFL.

## How to Publish on GitHub Pages

### Step 1: Create the GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Name the repository **exactly**: `mahfouz-z.github.io`
3. Set it to **Public**
4. Do **not** initialize with a README (you already have one)
5. Click **Create repository**

### Step 2: Push the Files

Open a terminal and run:

```bash
cd mahfouz-z.github.io

git init
git add .
git commit -m "Initial commit: personal website"
git branch -M main
git remote add origin https://github.com/mahfouz-z/mahfouz-z.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repo on GitHub → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose **main** branch and **/ (root)** folder
4. Click **Save**

### Step 4: Visit Your Site

After 1–2 minutes, your site will be live at:

```
https://mahfouz-z.github.io
```

## Customization

- **Links**: Update the `href` values for GitHub, Google Scholar, and LinkedIn in the hero section of `index.html` with your actual profile URLs.
- **Profile photo**: To add a photo, place an image file in the repo and add an `<img>` tag in the hero section.
- **Content updates**: Edit `index.html` directly — it's a single self-contained file with no build step required.

## Structure

```
mahfouz-z.github.io/
├── index.html    ← entire website (HTML + CSS + JS)
└── README.md     ← this file
```
