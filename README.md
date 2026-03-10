# 🎂 Birthday Perks Tracker

A mobile-friendly web app for tracking free birthday gifts, rewards, and perks from restaurants, retailers, and subscription services.

## Features
- Multiple user profiles — each person tracks their own perks independently
- Birthday countdown with birthday month celebrations
- Mark perks as Enrolled and Claimed
- Estimated dollar value per perk with total unclaimed value summary
- Direct links to rewards sign-up pages
- Category filters and search
- Annual reset reminder during your birthday month
- Backup and restore data via JSON export/import

## How to Use
1. Open the app and create a profile with your name and birthday
2. Browse the pre-loaded perks or add your own
3. Tap **+ Enroll** on any perk and use the sign-up link to create a rewards account
4. During your birthday month, tap **🎉 Claim** as you redeem each perk
5. Reset claimed statuses each year when prompted

## Deployment
This is a single-file app (`index.html`). Deploy by dragging onto [Netlify Drop](https://app.netlify.com/drop) or connect this repository to Netlify for automatic deploys.

## Tech Stack
- React 18 (via CDN)
- Plain HTML/CSS/JavaScript
- localStorage for data persistence
- No build tools required
