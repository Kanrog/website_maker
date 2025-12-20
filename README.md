# Free Website Template with Google Sheets CMS

Create your own website for **FREE** using GitHub Pages and Google Sheets.

Have a look at my example site - https://kanrog.github.io/website_maker/

## What You Need

- A GitHub account (free)
- A Google account (free)
- 15 minutes

## Setup

### 1. Create a GitHub Account

1. Go to https://github.com
2. Click "Sign up"
3. Follow the steps to create your account
4. Verify your email address

### 2. Fork This Repository

1. Go to this repository and click "Fork" at the top right
2. In the fork settings, name your repository: `YOUR_USERNAME.github.io` (replace `YOUR_USERNAME` with your actual GitHub username)
   - This naming convention gives you a clean URL without `/website` at the end
   - Example: If your username is `kanrog`, name it `kanrog.github.io` for the URL `https://kanrog.github.io`
   - You can also add on to an existing repo by giving it another name, like `example`, This way you'll get `YOUR_USERNAME.github.io/example`
3. Click "Create fork"

### 3. Create a Google Sheet

1. Click this link to make a copy of the template sheet: [Copy Template Sheet](https://docs.google.com/spreadsheets/d/1cLMaglrhcWkKaleRF6-ZwZtvSn0eNT9xfonY_QfRP1s/copy)
2. A new sheet will be created in your Google Drive - this is your copy to edit
3. Copy your Sheet ID from the URL: `https://docs.google.com/spreadsheets/d/YOUR_SHEET_ID/edit`
4. Click "Share" → "Change to anyone with the link" → Select "Viewer"

### 4. Update index.html

1. Open `index.html` in your forked repository
2. Click the edit pencil icon
3. Find: `const SHEET_ID` on line _194_
4. Replace the example ID with your actual Sheet ID
5. Commit the change

### 5. Add Images to Your Repository

1. In your GitHub repository, click on the `images` folder
2. Click "Add file" → "Upload files"
3. Drag and drop your images into the folder
4. Commit the changes
5. In your Google Sheet, use the image path: `/images/your-image.jpg`
   - Example: `/images/hero.jpg`, `/images/about.jpg`
- You can also use public image-URL's

### 6. Enable GitHub Pages

1. Go to Settings → Pages
2. Select "main" branch as source
3. Your site is now live at: `https://YOUR_USERNAME.github.io/`

## How to Update Your Website

Just edit your Google Sheet. Your website updates automatically when you refresh the browser!

## Tips

- Use hex color codes: `#FF5733`
- Include units for sizes: `24px`
- For images, upload to GitHub and use the raw URL, or use any public image URL
- Keep text concise for better readability
