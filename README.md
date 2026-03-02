# Yiwen Jin - Academic Personal Website

A clean, professional academic personal website for Assistant Professor Yiwen Jin.

## 📁 Folder Structure

```
github-structured/
├── index.html                 # Main HTML file
├── README.md                  # This file
├── assets/
│   ├── css/
│   │   └── main.css          # Global styles & variables
│   ├── js/
│   │   └── main.js           # Scroll animations & navigation
│   └── images/
│       └── profile.png       # Your profile photo
├── shared/
│   └── nav.css               # Navigation styles
└── sections/
    ├── hero/
    │   └── hero.css          # Hero section styles
    ├── about/
    │   └── about.css         # About section styles
    ├── research/
    │   └── research.css      # Research section styles
    ├── teaching/
    │   └── teaching.css      # Teaching section styles
    ├── awards/
    │   └── awards.css        # Awards section styles
    ├── services/
    │   └── services.css      # Services section styles
    └── footer/
        └── footer.css        # Footer section styles
```

## 🚀 Deploy to GitHub Pages

### Option 1: Upload Files Directly

1. Create a new repository on GitHub (e.g., `yourusername.github.io`)
2. Upload all files maintaining the folder structure
3. Go to **Settings → Pages**
4. Select **Deploy from a branch**
5. Choose **main** branch and **/(root)** folder
6. Click **Save**
7. Your site will be live at `https://yourusername.github.io`

### Option 2: Using Git

```bash
# Clone your repository
git clone https://github.com/yourusername/yourusername.github.io.git
cd yourusername.github.io

# Copy all files from github-structured folder
cp -r /path/to/github-structured/* .

# Add, commit, and push
git add .
git commit -m "Initial website commit"
git push origin main
```

## ✏️ Customization

### Update Profile Photo
Replace `assets/images/profile.png` with your own photo (recommended size: 800x1000px).

### Update Links
Edit `index.html` to update:
- CV link (line ~76)
- Google Scholar link (line ~80)
- LinkedIn link (line ~84)

### Update Colors
Edit CSS variables in `assets/css/main.css`:
```css
:root {
  --color-dark: #1a1a1a;        /* Main text color */
  --color-accent: #4a6fa5;       /* Link/button color */
  --color-accent-light: #e8f0f8; /* Light accent background */
  /* ... */
}
```

## 📱 Features

- ✅ Responsive design (mobile & desktop)
- ✅ Smooth scroll animations
- ✅ Clean, professional academic styling
- ✅ Easy to customize
- ✅ No build process required
- ✅ Fast loading

## 🎨 Design

- **Primary Font**: Cormorant Garamond (headings), Inter (body)
- **Color Scheme**: Warm beige, navy blue accent
- **Style**: Clean, minimal, professional academic

## 📄 License

© 2025 Yiwen Jin. All rights reserved.
