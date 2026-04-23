# Sushi Bar Osaka Website Plan

## What The Material Tells Us

The HTML file is not a site codebase. It is a saved planning conversation about making a first website for a newly opened sushi bar in Dobrich.

The menu images give us the real brand direction:

- Brand name: Sushi Bar Osaka
- Primary offer: sushi, uramaki, futomaki, hosomaki, poke bowls, sets, add-ons, allergens
- Tone: elegant, soft, slightly premium, not loud or neon
- Visual cues: pale blush background, dark burgundy typography, hand-drawn Japanese food illustrations, circular sakura logo, lots of negative space
- Key customer action: open menu, call, get directions, order delivery

## Recommended Site Goal

Build a fast one-page restaurant site that helps a mobile visitor do one of four things in under 10 seconds:

1. See the menu
2. Call the restaurant
3. Get directions
4. Open Instagram or delivery/contact info

This should be a lightweight marketing site, not a full app.

## Visual Direction

Use the menu artwork as the design anchor instead of inventing a different aesthetic.

- Background: soft blush or warm paper pink
- Main text: dark plum / near-black brown
- Accent: deep sushi red / burgundy
- Surface cards: slightly lighter cream-pink with thin illustrated borders or corner motifs
- Texture: faint line-art seafood / noodle illustrations in the background at low opacity
- Typography:
  - Display font: Japanese-inspired or sharp decorative heading font for hero titles only
  - Body font: clean readable sans-serif for menu text and details
- Mood: refined, calm, feminine-premium, handcrafted

## Recommended Pages

### Option A: Best First Version

One-page website with anchored sections:

1. Hero
2. Featured categories
3. Full menu
4. About / quality promise
5. Location and contact
6. Delivery info
7. Instagram / social proof

This is the best fit for a first client because it is simple to build, cheap to maintain, and mobile-friendly.

### Option B: Slightly More Premium

Separate pages:

1. Home
2. Menu
3. Contact
4. Delivery / ordering

Only do this if you want stronger SEO and a more polished business presentation.

## Homepage Structure

### 1. Hero

Should include:

- Logo or reconstructed brand mark
- Restaurant name
- Short line like: "Fresh sushi, poke and rolls in Dobrich"
- Primary CTA: View Menu
- Secondary CTA: Call Now
- Optional CTA: Get Directions

Visual treatment:

- Full-screen or near full-screen intro
- Background illustration inspired by the menu sheets
- One strong food image or collage framed like the printed menu

### 2. Featured Categories

Use icon-like cards or editorial tiles for:

- Sushi Sets
- Uramaki
- Futomaki
- Hosomaki
- Poke Bowls

Each tile should feel like part of the printed menu system, not generic food app UI.

### 3. Full Menu

Convert the photographed menu into structured HTML text.

Sections seen in the references:

- Hosomaki
- Uramaki
- Futomaki
- Sushi Sets
- Tataki and Sashimi
- Poke Bowl
- Add-ons
- Allergens

For each item, display:

- Name
- Weight or quantity
- Price in BGN
- Short ingredient description

Also include:

- Delivery phone
- Delivery fee

Keep the original menu images available as an optional "View original menu" gallery or lightbox, but do not rely on images alone for the main menu.

### 4. About Section

Short brand story, even if lightweight:

- Newly opened sushi spot in Dobrich
- Focus on fresh ingredients
- Japanese-inspired menu with local delivery

This section mainly builds trust and fills out the page visually.

### 5. Contact and Location

Must include:

- Click-to-call phone number
- Address
- Embedded map
- Opening hours
- Delivery area if available

### 6. Social / Trust

If available:

- Instagram feed or button
- Google review snippet
- A few food photos

If not available yet, use a simple gallery instead.

## Frontend Direction

The frontend should not look like a generic dark sushi template. It should feel like a digital version of the printed menu.

### Layout Principles

- Mobile-first
- Large vertical rhythm
- Decorative but restrained
- Readable menu typography
- Sticky CTA bar on mobile for call and menu

### UI Components

- Hero with layered illustration background
- Category cards with subtle border artwork
- Menu section accordions or tabs on mobile
- Floating call/order buttons
- Contact card with map and hours
- Image gallery with food closeups

### Motion

Keep it subtle:

- Soft fade-in on section reveal
- Gentle parallax or drift on background illustrations
- No heavy sliders or flashy transitions

## Content You Still Need From The Business

Before development, confirm:

- Exact address
- Opening hours
- Best contact number
- Instagram / Facebook links
- Whether they want delivery info on-site
- Whether they use Glovo, Takeaway, Foodpanda, or phone-only ordering
- Whether menu prices are current
- Whether they want Bulgarian only or Bulgarian + English
- A few real food photos
- Logo file if they have one

## SEO and Local Discovery

For a small restaurant, local SEO matters more than advanced features.

Prioritize:

- Page title with "Sushi Bar Osaka Dobrich"
- Meta description with sushi + Dobrich + delivery
- Proper heading hierarchy
- Address and phone in text, not just image
- Embedded Google Map
- Schema markup for local business if you want an extra polish layer

## Technical Recommendation

Best build path:

- Static frontend
- HTML/CSS/JS or a lightweight framework only if it speeds you up
- Deploy on Vercel or Netlify

Good implementation options:

1. Plain HTML/CSS/JS for maximum simplicity
2. Astro if you want cleaner component structure
3. Next.js only if you already know it well

For this project, plain HTML/CSS/JS or Astro is the safest choice.

## Suggested Build Order

### Phase 1: Foundation

1. Extract the menu into structured text
2. Define colors, fonts, spacing, and decorative motifs from the reference images
3. Collect missing business info

### Phase 2: Core Frontend

1. Build hero
2. Build menu navigation
3. Build structured menu sections
4. Add contact, map, and CTA buttons

### Phase 3: Polish

1. Add gallery
2. Add subtle motion
3. Optimize for mobile
4. Compress images
5. Add SEO metadata

## Success Criteria

The website is successful if:

- It looks recognizably tied to the printed menu brand
- It works beautifully on mobile
- A visitor can access the menu and phone number immediately
- The restaurant can share one clean link on Instagram, Maps, and messages
- The owner does not need technical knowledge to benefit from it

## Recommended Final Scope

Build a one-page premium brochure-style restaurant website with:

- Editorial hero
- Structured digital menu
- Delivery/contact CTA
- Map and hours
- Social/gallery section
- Visual style directly derived from the provided menu sheets

That scope is strong enough to sell, quick enough to finish, and realistic for a first paid local-business project.
