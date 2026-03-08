# ✈️ Travel Itinerary Page Generator Prompt

```
Build a single-file HTML travel itinerary page for my trip to [DESTINATION].

---

TRIP DETAILS
- Destination: [CITY/COUNTRY]
- Dates: [START DATE] to [END DATE] ([N] days)
- Cities/stops: [CITY 1], [CITY 2], ...

---

FLIGHTS
- Outbound: [ORIGIN] → [DEST], [DATE], [AIRLINE], flight [NUMBER], departs [TIME], arrives [TIME]
- Return: [DEST] → [ORIGIN], [DATE], [AIRLINE], flight [NUMBER], departs [TIME], arrives [TIME]

---

ACCOMMODATIONS
- [CITY 1]: [HOTEL NAME], [ADDRESS], check-in [DATE], check-out [DATE], booking ref: [REF]
- [CITY 2]: [HOTEL NAME], [ADDRESS], check-in [DATE], check-out [DATE], booking ref: [REF]

---

DAY-BY-DAY ITINERARY
- Day 1 ([DATE]): [Activities, meals, places to visit]
- Day 2 ([DATE]): [Activities, meals, places to visit]
- Day 3 ([DATE]): [Activities, meals, places to visit]
(continue for all days...)

---

DESIGN REQUIREMENTS
- Single self-contained HTML file (no external frameworks, CDN links only)
- Hero section with full-viewport background image from Unsplash relevant to the destination
- Color theme inspired by the destination's culture and aesthetics
- Typography: Playfair Display for headings, Inter for body (via Google Fonts CDN)
- Font Awesome icons for visual elements (via CDN)
- Day-by-day itinerary in a timeline layout
- Flight info cards with status badges (e.g. Confirmed / Booked)
- Hotel cards with photo, amenities list, and booking details
- Responsive and mobile-friendly
- Sticky navigation bar with smooth scroll

---

GITHUB PAGES HOSTING
- GitHub username: [YOUR_GITHUB_USERNAME]
- Repository name: [YOUR_REPO_NAME]
- Live URL will be: https://[YOUR_GITHUB_USERNAME].github.io/[YOUR_REPO_NAME]/

After generating the HTML, also:
1. Create a README.md with the trip title, date range, and live site URL
2. Create a GitHub Actions workflow at .github/workflows/deploy.yml that deploys
   index.html to GitHub Pages automatically on every push to main
3. Provide the exact terminal commands to:
   a. Initialize a local git repo
   b. Add the GitHub remote origin
   c. Commit and push everything to main
4. Remind me to go to GitHub repo Settings → Pages → Source and select "GitHub Actions"
```

---

## How to use this prompt

1. Replace every `[PLACEHOLDER]` with your actual info
2. Create an **empty** GitHub repo (no README, no license) at github.com/new
3. Paste the filled-in prompt into Kimi Code, Claude, or any AI coding tool
4. Follow the terminal commands it gives you to push and go live
