Kavomaz – Pinterest-only Redirect Pages (ALL listings)

WHAT THIS IS
============
One HTML redirect page per Etsy listing. Each page fires your Pinterest Tag, then redirects to the listing.
Placeholders to edit in EVERY file:
- YOUR_PINTEREST_TAG_ID  → your real Pinterest Tag ID (Ads → Conversions → Install tag)
- PASTE_YOUR_PINTEREST_VERIFY_CODE → meta verification code (Settings → Claim → Add HTML tag)

HOW TO DEPLOY (GitHub Pages – free)
-----------------------------------
1) Create a new repo on GitHub (e.g., kavomaz-pins). Upload all files in this folder.
2) Settings → Pages → Build and deployment → Source: Deploy from branch → Branch: main / root.
3) Your site will be live at https://USERNAME.github.io/REPO/
   Your redirect links:
   - https://USERNAME.github.io/REPO/etsy-4347579918.html
- https://USERNAME.github.io/REPO/etsy-4347590161.html
- https://USERNAME.github.io/REPO/etsy-4350877720.html
- https://USERNAME.github.io/REPO/etsy-4350865485.html
- https://USERNAME.github.io/REPO/etsy-4350116013.html
- https://USERNAME.github.io/REPO/etsy-4347589164.html
- https://USERNAME.github.io/REPO/etsy-4347580923.html
- https://USERNAME.github.io/REPO/etsy-4347582218.html
- https://USERNAME.github.io/REPO/etsy-4347577596.html
- https://USERNAME.github.io/REPO/etsy-4345123630.html

HOW TO DEPLOY (Netlify – free)
------------------------------
1) Go to app.netlify.com → "Add new site" → "Deploy manually".
2) Drag & drop the whole folder.
3) Your site will be live at https://YOUR-SITE.netlify.app/
   Links will be: https://YOUR-SITE.netlify.app/<slug>.html

BUILD AUDIENCES (free to create)
--------------------------------
Ads → Audiences → Create → "Site visitors"
- Condition: "Visited URL contains" → each <slug>.html (create 7d / 30d / 90d versions)
- Example slugs:
  • etsy-4347579918.html
  • etsy-4347590161.html
  • etsy-4350877720.html
  • etsy-4350865485.html
  • etsy-4350116013.html
  • etsy-4347589164.html
  • etsy-4347580923.html
  • etsy-4347582218.html
  • etsy-4347577596.html
  • etsy-4345123630.html

PIN DESTINATION LINKS
---------------------
Use these live URLs as the Destination link in your Pins.

NOTES
-----
- The script waits ~300ms to send tag events before redirecting.
- Change UTM defaults if you want by editing __CAMPAIGN__ text in each file.