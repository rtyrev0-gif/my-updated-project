═══════════════════════════════════════════════════════════════
  SENTINEL FINANCE AI — PROJECT README
  Version 1.0 · April 2026
  For: Founders, Developers, Investor Relations Team
═══════════════════════════════════════════════════════════════


────────────────────────────────────────────────────────────────
  SECTION 1: FILES IN THIS PACKAGE
────────────────────────────────────────────────────────────────

  index.html                  ← Investor landing page (main file)
  style.css                   ← Stylesheet (must be in same folder)
  investor_deck_outline.md    ← 14-slide deck content guide
  README.txt                  ← This file
  Gemini_Generated_Image_...  ← Hero image (AI Shield)

  All files must remain in the SAME FOLDER for the site to
  display correctly.


────────────────────────────────────────────────────────────────
  SECTION 2: HOW TO LAUNCH THE SITE LOCALLY
────────────────────────────────────────────────────────────────

  OPTION A — Simple (No installation required)
  ──────────────────────────────────────────────
  1. Extract the ZIP file to a folder on your computer.
  2. Double-click "index.html".
  3. The site will open in your default web browser.

  NOTE: The Google Fonts (Sora + DM Sans) require an internet
  connection to load. Without it, the browser will fall back to
  system sans-serif fonts.


  OPTION B — Local Server (Recommended for demos)
  ──────────────────────────────────────────────
  Running a local server prevents any browser security warnings
  and ensures all assets load correctly.

  If you have Python installed:
    → Mac/Linux:
        cd /path/to/sentinel-folder
        python3 -m http.server 8080
        Open: http://localhost:8080

    → Windows:
        cd C:\path\to\sentinel-folder
        python -m http.server 8080
        Open: http://localhost:8080

  If you have Node.js installed:
        npx serve .
        Open the URL shown in the terminal


  OPTION C — Deploy Online (For Investor Sharing)
  ──────────────────────────────────────────────
  Upload all files to any static hosting service:

  • Netlify (recommended, free):
    1. Go to https://app.netlify.com/drop
    2. Drag the entire folder onto the page
    3. Share the generated URL with investors

  • Vercel:
    npx vercel --prod

  • GitHub Pages:
    Push to a public repo → Settings → Pages → Deploy from main

  • AWS S3 Static Website Hosting:
    Upload files to an S3 bucket with static website hosting
    enabled. Set index.html as the index document.


────────────────────────────────────────────────────────────────
  SECTION 3: USING THE HERO IMAGE
────────────────────────────────────────────────────────────────

  The hero image file (Gemini_Generated_Image_mhcgomhcgomhcgom.png)
  must be placed in the SAME folder as index.html and style.css.

  The landing page is designed so that:
  → The "AI Shield" in the image appears on the RIGHT side
  → All headline text ("Seniors Deserve.") appears on the LEFT
  → A gradient overlay fades the left edge so text is readable
  → On mobile, the image becomes a background with 25% opacity

  If you rename the image, update this line in index.html:
    <img src="Gemini_Generated_Image_mhcgomhcgomhcgom.png" ...>
  Replace the filename with your new name.


────────────────────────────────────────────────────────────────
  SECTION 4: CUSTOMISATION GUIDE
────────────────────────────────────────────────────────────────

  CHANGE CONTACT EMAIL:
  Search index.html for "invest@sentinelfinance.ai"
  Replace all instances with your real email address.

  CHANGE COLOUR PALETTE:
  Open style.css. Edit the :root { } block at the top.
  Key variables:
    --gold      : #D4A843  (accent / CTA colour)
    --navy-900  : #040D1A  (darkest background)
    --navy-800  : #071428  (section backgrounds)

  CHANGE COUNTER NUMBERS:
  In index.html, find elements with data-target="..."
  Example: <span class="stat-num" data-target="3402">
  Change the number after data-target= to update the animated stat.

  ADD A REAL TEAM PHOTO:
  Find the .team-avatar elements. Replace the emoji (👤) with:
    <img src="yourphoto.jpg" alt="Name" style="width:100%;height:100%;object-fit:cover;border-radius:50%;">


────────────────────────────────────────────────────────────────
  SECTION 5: THE CRITICAL INVESTOR QUESTION
  "How will you acquire customers cost-effectively at scale?"
────────────────────────────────────────────────────────────────

  This is THE question every seed investor will ask. Here is
  the full answer framework for your pitch meeting:


  ★ THE ANSWER: Channel-First, Not Consumer-First ★

  Sentinel's go-to-market strategy deliberately AVOIDS the
  high-CAC trap of direct B2C consumer acquisition. Instead,
  we distribute through credit unions and community banks who
  already OWN our target customer relationships.


  WHY CREDIT UNIONS?
  ─────────────────
  • 135 million members in the US alone
  • Average member tenure: 17 years (extremely sticky)
  • Credit unions are LEGALLY OBLIGATED to act on elder
    financial exploitation under the Senior Safe Act (2018)
  • They have NO current solution → we solve a compliance
    problem AND a member value problem simultaneously
  • Average credit union has 50,000–300,000 members
  • One signed deal = instant access to tens of thousands
    of qualified, pre-vetted senior accounts

  THE MATH (Unit Economics):
  ──────────────────────────
  • CAC via credit union channel: ~$40 per activated senior
    (allocated cost of CRO travel + partnership materials)
  • CAC via direct B2C (if we had to): ~$180–$220
    (industry benchmark for FinTech mobile app)
  • We WIN by being 4.5x more capital-efficient on acquisition

  • LTV calculation:
    - ARPU: $120/year
    - Average senior customer tenure in FinTech: 4+ years
    - LTV: $480
    - LTV:CAC ratio via credit unions: 12:1
    - (Industry benchmark for healthy SaaS: 3:1)

  THE FLYWHEEL:
  ─────────────
  1. Sign 1 credit union (5,000 members) → $12,500 MRR
  2. Senior uses Sentinel → tells their adult children
  3. Adult children share with their own parents
  4. Organic B2C signups from family referral → $0 CAC
  5. B2C user base = proof of demand → sign next credit union
  6. Repeat

  This word-of-mouth loop is ALREADY ACTIVE:
  Our 1,200-person waitlist was built with $0 in paid marketing.
  94% of beta users said they recommended the product to family.

  THE HONEST RISK (Acknowledge it before they ask):
  ──────────────────────────────────────────────────
  Credit union sales cycles are 3–9 months. This is slow.
  Our mitigation:
  → James Harrington (CRO) already has relationships with
    47 credit union CEOs from his Fiserv tenure
  → 3 LOIs already signed BEFORE we raised this round
  → We budget 9 months of runway before first revenue hits,
    so slow sales cycles don't threaten survival
  → Our B2C channel launches in parallel as a hedge


  IN ONE SENTENCE (for the 30-second answer):
  ────────────────────────────────────────────
  "Our CAC is $40 through credit union white-label
  partnerships, giving us a 12:1 LTV:CAC ratio —
  and our CRO has relationships with 47 credit union
  CEOs from his decade at Fiserv, so we're not starting
  cold. We have 3 LOIs signed before this round closes."


────────────────────────────────────────────────────────────────
  SECTION 6: INVESTOR DECK NEXT STEPS
────────────────────────────────────────────────────────────────

  The file "investor_deck_outline.md" contains the full
  14-slide content guide.

  RECOMMENDED TOOLS TO BUILD THE ACTUAL DECK:
  • Pitch.com (best for FinTech / startup decks, free tier)
  • Canva Pro (import the navy/gold palette directly)
  • Google Slides (share a link, no download required)
  • PowerPoint + "Beautiful.ai" plugin (auto-layout)

  DESIGN BRIEF FOR YOUR DESIGNER:
  • Primary font: Sora (display/headlines) — Google Fonts, free
  • Body font: DM Sans — Google Fonts, free
  • Primary colour: #040D1A (navy) + #D4A843 (gold)
  • Card style: Glassmorphism (frosted glass, 55% opacity)
  • Avoid: Purple, purple gradients, "generic AI" aesthetics
  • Reference: The index.html landing page as style guide


────────────────────────────────────────────────────────────────
  SECTION 7: LEGAL NOTICES
────────────────────────────────────────────────────────────────

  • This landing page is for INFORMATIONAL PURPOSES ONLY
    and does not constitute a public solicitation of investment.

  • The statistics cited (FBI, FTC, NCOA) are real. Ensure
    citations are verified and dated before investor meetings.

  • The SAFE Note terms ($4.5M cap, 20% discount) are indicative.
    Finalise with your legal counsel before presenting.

  • "Sentinel Finance AI" and "VoiceGuard", "BehaviourPrint",
    and "SentinelScore" are provisional brand names. Conduct
    trademark searches before public launch.

  • Ensure compliance with SEC Regulation D (US), OSC rules
    (Canada), and FCA financial promotion rules (UK) before
    distributing any investment materials.


────────────────────────────────────────────────────────────────
  CONTACT
────────────────────────────────────────────────────────────────

  General:     hello@sentinelfinance.ai
  Investors:   invest@sentinelfinance.ai
  Press:       press@sentinelfinance.ai
  Calendar:    calendly.com/sentinel-sarah-chen

═══════════════════════════════════════════════════════════════
  © 2026 Sentinel Finance AI Inc. All rights reserved.
  "Protecting the generation that built our wealth."
═══════════════════════════════════════════════════════════════
