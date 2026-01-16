# NullDev Homepage

Official website for NullDev apps.

## 🌐 Live Site

Visit: https://hellonulldev.github.io/

## 📱 Featured Apps

- **Indecisive** (결정장애 / 優柔不断) - Decision-making helper app
  - [Apple App Store](https://apps.apple.com/app/id6757303507)
  - Google Play (Coming Soon)

- **Three Habits** (3개의 습관 / 3つの習慣) - Minimal habit tracker focusing on just 3 habits
  - [Apple App Store](https://apps.apple.com/app/id6757355894)
  - Google Play (Coming Soon)

## 🌍 Multi-language Support

The website supports three languages:
- 🇺🇸 English
- 🇰🇷 한국어 (Korean)
- 🇯🇵 日本語 (Japanese)

Language preference is automatically detected from browser settings and saved in localStorage.

## 🔄 How to Update

1. Edit `index.html`
2. Commit and push to `main` branch
3. Changes will be live in 1-2 minutes

## 📂 Structure

```
Homepage/
├── index.html           # Main page with multi-language support
└── README.md           # This file
```

## 🚀 Adding New Apps

When releasing a new app, update the `apps-grid` section in `index.html`:

```html
<div class="app-card">
    <div class="app-icon">🎯</div>
    <h3 class="app-name" data-i18n="app-name-key">Your App Name</h3>
    <div class="app-name-local">한국어 / 日本語</div>
    <p class="app-description" data-i18n="app-desc-key">
        App description here...
    </p>
    <div class="download-buttons">
        <a href="APP_STORE_URL" class="btn btn-appstore">
            🍎 App Store
        </a>
        <a href="PLAY_STORE_URL" class="btn btn-playstore">
            📱 Google Play
        </a>
    </div>
</div>
```

Don't forget to add translations in the JavaScript `translations` object for all three languages.

## 🎨 Features

- **Responsive Design**: Works perfectly on mobile, tablet, and desktop
- **Multi-language Support**: EN, KO, JA with automatic detection
- **Modern UI**: Gradient backgrounds, smooth animations, and hover effects
- **App Store Links**: Direct links to Google Play and Apple App Store
- **Local Storage**: Saves user's language preference

---

© 2026 NullDev. All rights reserved.
