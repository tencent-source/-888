# Free Movie Paradise - GitLab Pages Setup

## 🎬 Website Overview
A weeb anime kawaii themed website featuring 10 free movie streaming sites with a dark theme and neon aesthetics.

## 🚀 GitLab Pages Deployment Instructions

### Step 1: Create GitLab Account
1. Go to [gitlab.com](https://gitlab.com)
2. Sign up for a free account
3. Verify your email address

### Step 2: Create New Project
1. Click "New project" or "Create blank project"
2. Set project name: `weeb-anime-kawaii` (or your preferred name)
3. Set visibility to "Public" (required for free Pages)
4. Click "Create project"

### Step 3: Upload Files
1. Click "Upload file" or "Add file" → "Upload file"
2. Upload all files from this folder:
   - `index.html`
   - `.gitlab-ci.yml`
   - `hosting_options.txt` (optional)

### Step 4: Configure GitLab Pages
1. Go to your project settings
2. Navigate to "Settings" → "Pages"
3. Note your Pages URL (will be: `https://yourusername.gitlab.io/weeb-anime-kawaii`)

### Step 5: Enable CI/CD
1. Go to "CI/CD" → "Pipelines"
2. The pipeline should automatically run and deploy your site
3. Wait for the pipeline to complete successfully

### Step 6: Access Your Site
Your site will be available at:
```
https://yourusername.gitlab.io/weeb-anime-kawaii
```

## 🔒 URL Obscuring Options

### Option 1: Custom Domain
1. Buy a domain from any registrar
2. In GitLab Pages settings, add your custom domain
3. Configure DNS settings as instructed

### Option 2: URL Shortener
Use services like:
- bit.ly
- tinyurl.com
- cutt.ly

### Option 3: Subdomain Masking
Use privacy-focused URL forwarding services.

## ⚠️ Important Notes
- GitLab Pages requires public repositories for free hosting
- The site is static HTML - no server-side processing needed
- Include the legal disclaimer as provided
- Consider copyright implications in your jurisdiction

## 🎨 Website Features
- Dark theme with neon pink/blue/purple aesthetics
- Animated stars background
- Kawaii emoji animations
- 10 free movie streaming sites
- Responsive design for mobile devices
- Interactive hover effects

## 📁 Project Structure
```
weeb-anime-kawaii/
├── index.html          # Main website file
├── .gitlab-ci.yml      # CI/CD configuration
├── hosting_options.txt # Additional hosting options
└── README.md          # This file
```

## 🔄 Updating Your Site
1. Edit `index.html` locally
2. Upload changes to GitLab
3. Pipeline automatically deploys updates
4. Changes appear within minutes

## 🆘 Troubleshooting
- If Pages don't appear, check CI/CD pipeline status
- Ensure `.gitlab-ci.yml` is in the root directory
- Verify project visibility is set to "Public"
- Check GitLab Pages documentation for advanced features
