# Sound Partners - Venue Booking Information Pages

## Overview
This folder contains 5 professional, mobile-friendly HTML pages for your venue booking directives (plus an index page). Each page is fully self-contained: all styling, fonts, and icons are bundled into a single local `assets.css` file. There are **no external dependencies** — the pages render identically forever, even offline or if any third-party service goes down.

> **Important:** Keep `assets.css` and `SP-Logo-Blue-SmashingLogo.png` in the same folder as the HTML files. The pages won't be styled without `assets.css`.

**Files included:**
- `bateau-bay-hotel.html` — Bateau Bay Hotel
- `bay-hotel-bonnells-bay.html` — The Bay Hotel Motel (Bonnells Bay)
- `huntlee-tavern.html` — Huntlee Tavern
- `bellbird-hotel.html` — Bellbird Hotel
- `terrigal-hotel.html` — Terrigal Hotel

(Plus this README)

## Recommended Hosting: GitHub Pages (Easiest + Professional + Free)

### Why GitHub Pages?
- **Separate clean links** for each venue (you control the URLs)
- **Instant updates**: Edit directly in your browser on GitHub → save → live in ~30-60 seconds
- **Free forever**, reliable, fast global CDN
- **Version history** (see changes over time, revert if needed)
- **Professional** look and full ownership (no third-party branding like Notion)
- Acts get a clean, trustworthy page that looks like it belongs to Sound Partners

### Step-by-step Setup (10-15 minutes first time)

1. **Create GitHub account** (if you don't have one) at https://github.com

2. **Create a new repository**
   - Click the big green "+" (top right) → "New repository"
   - Name it something like: `sound-partners-venue-info` or `venue-booking-directives`
   - Make it **Public** (required for free GitHub Pages)
   - **Do NOT** initialize with README (you'll upload files)
   - Click "Create repository"

3. **Upload the files**
   - On the repo page, click the big **"uploading an existing file"** link (or drag & drop)
   - Drag **all** the files into the box: the 6 `.html` files (`index.html` + the 5 venue pages), **`assets.css`**, and **`SP-Logo-Blue-SmashingLogo.png`**. All files must be uploaded together or the pages won't be styled.
   - Add a commit message e.g. "Initial venue booking info pages"
   - Click **"Commit changes"**

4. **Enable GitHub Pages**
   - Go to the repo → **Settings** tab (top right)
   - Scroll down to **"Pages"** section (left sidebar or search "Pages")
   - Under "Build and deployment":
     - Source: **Deploy from a branch**
     - Branch: `main` (or `master`)
     - Folder: `/ (root)`
   - Click **Save**
   - Wait 30-60 seconds, then refresh the page. You should see a green banner with your live site URL, e.g.:
     `https://YOUR-USERNAME.github.io/sound-partners-venue-info/`

5. **Access your pages**
   Your 5 separate links will be:
   - Bateau Bay: `https://YOUR-USERNAME.github.io/sound-partners-venue-info/bateau-bay-hotel.html`
   - Bay Hotel: `https://YOUR-USERNAME.github.io/sound-partners-venue-info/bay-hotel-bonnells-bay.html`
   - Huntlee Tavern: `https://YOUR-USERNAME.github.io/sound-partners-venue-info/huntlee-tavern.html`
   - Bellbird Hotel: `https://YOUR-USERNAME.github.io/sound-partners-venue-info/bellbird-hotel.html`
   - Terrigal Hotel: `https://YOUR-USERNAME.github.io/sound-partners-venue-info/terrigal-hotel.html`

   (Replace YOUR-USERNAME with your actual GitHub username)

### How to Update Content (Super Easy)

**Option A - Edit directly in browser (no software needed):**
1. Go to your GitHub repo
2. Click the HTML file you want to update (e.g. `bateau-bay-hotel.html`)
3. Click the **pencil icon** (top right) to edit
4. Make your changes (the file is well-commented — look for `<!-- EDIT HERE -->` sections)
5. Scroll down and click the big green **"Commit changes"** button
6. Done! The page updates automatically within a minute. Share the same link — it always shows the latest.

**Option B - Edit on your computer (if you prefer VS Code etc.):**
1. Download the repo as ZIP or use Git
2. Edit the HTML files locally
3. Upload the changed file(s) back to GitHub (drag & drop works)
4. Commit

### Making URLs Even Nicer (Optional, Advanced)

You can create folders so links look like:
`https://yourname.github.io/sound-partners-venue-info/bateau-bay-hotel/`

To do this:
- Create a folder named `bateau-bay-hotel`
- Move/rename the file to `bateau-bay-hotel/index.html`
- Repeat for others
- Commit

GitHub Pages will automatically serve the folder nicely.

### Alternative Hosting Options

**Netlify (also excellent, sometimes even easier drag-and-drop):**
1. Go to https://app.netlify.com/drop
2. Drag the folder containing the 5 HTML files onto the page
3. Get instant live links + custom domain option later
4. To update: Either re-drag the folder or connect to Git (recommended for ongoing)

**Notion (Zero code, WYSIWYG editing - good if you hate any tech setup):**
- Create 5 separate Notion pages
- Copy-paste the content from these HTML files (or re-type nicely)
- Use headings, bullets, bold, links
- Publish each page to web
- Pros: Extremely easy to edit on phone or computer, beautiful by default
- Cons: URLs are long and Notion-branded (e.g. notion.so/Your-Page-Title-abc123). You can buy a custom domain later if desired.
- Many booking agents use this successfully.

### Design Notes
- These pages use **Tailwind CSS, fonts (Inter + Poppins), and icons all bundled locally** into `assets.css` — modern, clean, professional look that works great on mobile and desktop, with zero reliance on external services.
- Important sections (especially the late/cancellation policy) are highlighted with warning styling.
- All links (Google Maps, phone, email, social) are clickable and mobile-friendly.
- The pages are self-contained — no build step or internet connection required to view them.
- **One caveat when editing:** the styling in `assets.css` only includes the Tailwind classes currently used in the pages. If you hand-edit an HTML file and add a *brand-new* Tailwind class that wasn't used before, it may not take effect until `assets.css` is rebuilt to include it. Editing existing text, links, times, and notes is completely fine and needs no rebuild — just ask if you ever want new styling added.
- You can easily customize colors, add your logo later, or add a "Last updated" date at the top of each page when you edit.

### Need Help?
- If you want me to adjust the design (colors, layout, add logo, make sections collapsible, etc.), just tell me.
- If you want Markdown versions instead (easier for some people to edit), let me know.
- If you want a single landing page that lists all 5 venues with links, I can add that too.
- For custom domain (e.g. venues.soundpartners.com.au), both GitHub Pages and Netlify support it easily (you just update DNS).

These pages will make you look professional and organized to your acts and agents. The consistent layout across all venues helps acts quickly find the info they need.

Enjoy! 

— Generated for Sound Partners, June 2026