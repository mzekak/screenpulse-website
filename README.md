# Screen Pulse Website

A clean, professional website for Screen Pulse - designed to support Apple App Store submissions and provide essential information about your apps.

## What's Included

- **Landing Page** (`index.html`) - Simple introduction to Screen Pulse
- **Our Apps** (`apps.html`) - Showcase page featuring Ibadah Focus
- **Privacy Policy** (`privacy.html`) - Comprehensive privacy policy with app-specific sections
- **Terms of Service** (`terms.html`) - Complete terms and conditions
- **Contact Page** (`contact.html`) - Contact information and form
- **Styles** (`styles.css`) - Clean, modern, mobile-responsive design

## Quick Deploy to Vercel (5 Minutes)

### Step 1: Upload to GitHub

1. Create a new repository on GitHub (https://github.com/new)
2. Name it something like `screenpulse-website`
3. Make it Public (required for free Vercel hosting)
4. Don't add README, .gitignore, or license (we already have files)

5. Upload your files:
   - Click "uploading an existing file"
   - Drag all the files from this folder
   - Click "Commit changes"

### Step 2: Deploy to Vercel

1. Go to https://vercel.com/signup
2. Sign up with your GitHub account (easiest option)
3. Click "Add New Project"
4. Import your `screenpulse-website` repository
5. Click "Deploy" (no configuration needed!)
6. Wait 30 seconds - your site is now live!

### Step 3: Connect Your Domain

1. In Vercel, go to your project → Settings → Domains
2. Add domain: `screenpulse.shop`
3. Add domain: `www.screenpulse.shop`
4. Vercel will show you DNS records to add

5. Go to Namecheap:
   - Domain List → Manage → Advanced DNS
   - Add the records Vercel provided (usually):
     - A Record: `@` → `76.76.21.21`
     - CNAME: `www` → `cname.vercel-dns.com`
   
6. Wait 10 minutes to 24 hours for DNS to update
7. Done! Your site is live at www.screenpulse.shop

## Email Setup (Recommended)

To make the contact emails work (contact@screenpulse.shop, support@screenpulse.shop, etc.):

### Option 1: Namecheap Email Forwarding (Free)
1. Namecheap Dashboard → Email Forwarding
2. Forward emails to your personal email
3. Example: `contact@screenpulse.shop` → `your-email@gmail.com`

### Option 2: Professional Email (Paid, ~$1/month)
- Google Workspace
- Namecheap Private Email
- ProtonMail

## Customization

### Update Contact Emails
If you set up different email addresses, update them in:
- `contact.html` (all email links)
- `privacy.html` (contact section)
- `terms.html` (contact section)

### Update App Information
- Edit `apps.html` to add more apps as you build them
- Add app-specific privacy/terms sections in `privacy.html` and `terms.html`

### Change Colors/Branding
- Edit `styles.css` - look for the `:root` section at the top
- Customize `--primary-color`, `--primary-dark`, etc.

## File Structure

```
screenpulse-website/
├── index.html          # Landing page
├── apps.html           # Apps showcase
├── privacy.html        # Privacy policy
├── terms.html          # Terms of service
├── contact.html        # Contact page
├── styles.css          # All styling
└── README.md           # This file
```

## For Apple App Store Submission

When submitting Ibadah Focus to the App Store, provide these URLs:

- **Privacy Policy URL**: `https://www.screenpulse.shop/privacy.html#ibadah-focus`
- **Terms of Service URL**: `https://www.screenpulse.shop/terms.html#ibadah-focus`
- **Support URL**: `https://www.screenpulse.shop/contact.html`
- **Marketing URL**: `https://www.screenpulse.shop/apps.html`

## Support

If you need help or want to make changes, all the code is standard HTML/CSS - any web developer can modify it easily.

## Notes

- The site is completely static (no backend needed)
- Works perfectly offline during development (just open index.html in a browser)
- Mobile responsive and fast loading
- SEO-friendly with proper meta tags
- SSL/HTTPS automatically provided by Vercel
