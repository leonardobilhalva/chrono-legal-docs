# Chrono - Legal Documents

Public repository hosting legal documents for the Chrono sleep tracking app.

## 📄 Documents

- **[Terms of Use](https://leonardobilhalva.github.io/chrono-legal-docs/terms.html)** - Terms and conditions for using Chrono
- **[Privacy Policy](https://leonardobilhalva.github.io/chrono-legal-docs/privacy.html)** - How we collect, use, and protect your data

## 🚀 Setup Instructions

### 1. Create Repository on GitHub

1. Go to https://github.com/new
2. Repository name: `chrono-legal-docs`
3. Visibility: **Public** ✅
4. DO NOT initialize with README (we already have one)
5. Click "Create repository"

### 2. Upload Files

**Option A: Via GitHub Web Interface**
1. Click "uploading an existing file"
2. Drag and drop these files:
   - `index.html`
   - `terms.html`
   - `privacy.html`
   - `README.md`
3. Commit message: "Initial commit - Legal documents"
4. Click "Commit changes"

**Option B: Via Command Line**
```bash
cd /path/to/docs-export
git init
git add .
git commit -m "Initial commit - Legal documents"
git branch -M main
git remote add origin https://github.com/leonardobilhalva/chrono-legal-docs.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to repository Settings
2. Click "Pages" in left sidebar
3. Source: Deploy from a branch
4. Branch: `main` / `/ (root)`
5. Click "Save"
6. Wait 2-3 minutes for deployment

### 4. Verify URLs

After GitHub Pages deploys, your documents will be available at:

- **Index:** https://leonardobilhalva.github.io/chrono-legal-docs/
- **Terms:** https://leonardobilhalva.github.io/chrono-legal-docs/terms.html
- **Privacy:** https://leonardobilhalva.github.io/chrono-legal-docs/privacy.html

## 📱 Integration with Chrono App

These URLs are referenced in:
- `OnboardingWelcomeStep.swift` (Terms acceptance checkboxes)
- `SettingsView.swift` (Legal section links)

## 🔄 Updating Documents

When you need to update the legal documents:

1. Update `TERMS_OF_USE.md` or `PRIVACY.md` in the main Chrono repo
2. Run the conversion script to regenerate HTML
3. Copy updated HTML to this repo
4. Commit and push changes
5. GitHub Pages will auto-deploy within 2-3 minutes

## 📝 Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0.0   | Jan 3, 2025 | Initial release |

## 📧 Contact

**Developer:** Leonardo Bilhalva
**Email:** leonardobilhalva@icloud.com
**Main App Repo:** [Chrono](https://github.com/leonardobilhalva/Chrono) (Private)

## 📜 License

© 2025 Leonardo Bilhalva. All rights reserved.

These legal documents are provided for reference purposes. The source Markdown files are maintained in the private Chrono repository.
