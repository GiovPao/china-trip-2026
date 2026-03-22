# 🇨🇳 China Trip 2026

A mobile-friendly travel website for my China trip, May 11 – June 1, 2026.

## Structure

```
china-trip/
├── index.html          ← Homepage with full itinerary overview
├── style.css           ← Shared styles
└── days/
    ├── may11.html      ← Arrival in Shanghai
    ├── may12.html      ← Travel to Xi'an
    ├── may13.html      ← Terracotta Warriors
    ├── may14.html      ← Travel to Chengdu + pre-wedding
    ├── may15.html      ← Free day in Chengdu
    ├── may16.html      ← 💍 WEDDING DAY
    ├── may17.html      ← Giant Pandas
    ├── may18.html      ← Travel to Zhangjiajie
    ├── may19.html      ← Avatar Mountains
    ├── may20.html      ← Tianmen Mountain
    ├── may21.html      ← Travel to Chongqing
    ├── may22.html      ← Full day Chongqing
    ├── may23.html      ← Travel to Beijing
    ├── may24.html      ← Forbidden City
    ├── may25.html      ← Great Wall
    ├── may26.html      ← Temple of Heaven + Summer Palace
    ├── may27.html      ← Lama Temple + Hutongs
    ├── may28.html      ← Travel back to Shanghai
    ├── may29.html      ← Suzhou day trip
    ├── may30.html      ← Shanghai deep dive
    ├── may31.html      ← Last day
    └── jun01.html      ← Fly home
```

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `china-trip-2026`)
2. Upload all files keeping the folder structure intact
3. Go to **Settings → Pages**
4. Set source to **Deploy from a branch → main → / (root)**
5. Your site will be live at `https://yourusername.github.io/china-trip-2026/`

## Add your own notes

Each day page has a **📝 My notes** section at the bottom. Edit the HTML directly to add:
- Hotel addresses and booking references
- Train booking references  
- Restaurant recommendations from Mengmeng
- Any links you find useful

Look for this section in each file:
```html
<div class="notes-area">
  <p><strong>Notes & reminders:</strong></p>
  <p>YOUR NOTES HERE</p>
```

## Customising links

Each day has a **🔗 Quick links** section. Add your own links by editing:
```html
<a href="YOUR_URL" target="_blank" class="link-btn">
  <span class="licon">🔗</span>
  <span class="ltxt">Link label</span>
</a>
```
