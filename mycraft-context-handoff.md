# MyCraft — Project Context Handoff

_Generated 16 Aug 2026. Give this file to Claude at the start of a Cowork session so it has full context without re-explaining._

---

## 1. Who I am

- **Tanmay**, based in **Rajkot, Gujarat**. Undergraduate student, 4th semester.
- Co-founder of **ScholarNode** (in-person AI workshops for schools across Gujarat).
- Building **MyCraft** — a small web design/build studio (me + at least one partner), targeting local Rajkot businesses as side income.

**How I want to be worked with:**
- Be brutally honest. Don't sugarcoat. Flag when something is cosmetic vs. genuinely useful.
- Give complete, ready-to-use outputs — full files, not partial diffs or "here are 5 options".
- Build understanding before implementation; explain the reasoning, then ship.

---

## 2. What MyCraft is

A two-person web studio selling websites to Rajkot SMBs. Offer shape decided so far:

- **Fixed packages, no custom quotations** (Starter / Business / monthly Care plan)
- **7-day delivery** from content handover
- **Recurring monthly retainer** is the actual business model — one-time builds are not income
- Stack kept deliberately boring and maintainable: **Next.js + Tailwind, deployed on Vercel/Netlify**
- Rule I agreed to: **never ship anything I couldn't rebuild by hand**

**Positioning honesty:** we are a small, new team. We do not pretend to be an established agency. Being small and fast is the story.

---

## 3. Current state of the portfolio site

Two versions built so far. **v2 is the current one.**

- File: `mycraft-portfolio-v2.html` — single self-contained HTML file
- Design language: dark ink-green (`#111815`) + marigold (`#E9A227`) + sage accent
- Fonts: Bricolage Grotesque (display), Instrument Sans (body), JetBrains Mono (labels)
- **Signature element: a "work order" card** — the hero shows a blank work order addressed to the visitor's business (client / scope / delivery / includes / after). Fits the "MyCraft" workshop metaphor and front-loads delivery time and inclusions.
- Sections: Hero → Selected work (6 projects) → For coaching classes → Process (7 days, 4 steps) → Pricing (3 packages) → Contact

**STILL UNFILLED — must be replaced before sending to anyone:**
| Placeholder | Replace with |
|---|---|
| `9999999999` (×3) | real 10-digit phone |
| `hello@mycraft.in` | real email |
| `PRICE_STARTER` | e.g. 6,000 |
| `PRICE_BUSINESS` | e.g. 12,000 |
| `PRICE_CARE` | e.g. 1,500 |

**Also missing:** no screenshots/images anywhere. Every project card is text-only. This is the biggest weakness of the current site.

---

## 4. Projects listed in the portfolio (all real)

| Project | What it is | Honest status |
|---|---|---|
| **ScholarNode** | AI workshops in Gujarat schools; enrolment, school portal, payments, certificates. Next.js + Supabase + Razorpay + Vercel | Our own venture, not a client |
| **VidyaVani** | Gujarati-medium AI education platform, Google Gemini API | Built for an AI Summit hackathon |
| **Property valuation reports** | Flask web app for a Rajkot valuer — form in, formatted DOCX report out | Real external-ish user (family member's business) |
| **Tally** | Mobile-first shared expense tracker, static site + service worker, live on Netlify | Built for a friends' trip |
| **Aadita Fashion Jwellery** | AI-generated product video ads (Higgsfield); prompt work for jewellery fidelity — flat lighting, no light-sweep, slow camera moves | Family-connected business |
| **AIdeaForge** | Gujarati sign transliteration app, FastAPI on Railway | Hackathon/self-built |

**Important:** none of these are paid client websites. If a prospect asks, say so plainly — "these are our own products plus one Rajkot business tool; you'd be our first coaching class client."

---

## 5. Sales situation

### Niche decision
Chose **game zones / gaming cafés** as the stated niche. Was offered kids play areas + preschools as a higher-volume alternative and declined. Currently also warm on **coaching classes**, which is where the first real call happened.

### Live lead: Success Educational Services ← ACTIVE
- **Owner:** Brijesh Mehta (personally follows up with parents — he is the decision maker)
- **Phone:** +91 93270 01792
- **Address:** 310 Golden Space, Sardar Nagar Main Rd, opp. ABC Medical Store, nr. Jagnath Temple, Rajkot 360001
- **Hours:** 10 AM–8 PM Mon–Sat, closed Sunday
- **Google:** 5.0 · 70 reviews. No website. Operating since at least 2018.
- **Offering:** personal + group tuition, CBSE + ICSE + GSEB, plus home tuition. Two-teacher model (Brijesh + Deepraj sir).
- **Status:** cold-called; they asked us to send details. **Follow-up message drafted but NOT YET SENT** — waiting on portfolio being fill-in-complete and hosted.
- **The pitch angle:** he has no acquisition problem, he has a *proof* problem. Three boards + home tuition are real differentiators that are completely invisible online. Word of mouth only reaches people who already know him.

### Game zone leads (called: none)
| Business | Phone | Notes |
|---|---|---|
| Murlidhar Game Zone | +91 99795 48743 | PS5, 14 reviews, owner on-site. Easiest yes, smallest budget |
| Galaxy Game Zone | +91 63519 79750 | New, 29 reviews, no rates published |
| Play zone | +91 75730 08383 | Goldwings Cinemas |
| Infinity Game Zone | +91 99245 26461 | "Cheapest in city" positioning, 2nd floor, no walk-in visibility |
| GameXL | +91 82383 61246 | 5.0 · 110. Healthiest. Pitch = retention/tournaments, not discovery |
| Whoopeee World | +91 98242 41451 | 502 reviews at 4.2 — has a site, has a reputation problem, has money |
| FunBlast | +91 99791 73000 | Has a site |
| **Knockout Bowling** | no phone listed | 571 reviews, no site. Customers explain the pricing to each other in reviews. Biggest opportunity. Open 24h — walk in |
| Dazzlers Den | no phone listed | Walk-in |
| AAA Gaming Lounge | no phone listed | Walk-in |
| Crazy World Fun Zone | no phone listed | Reliance Mall |

### Coaching class leads (Tier 1, independent, no website)
Success Educational Services (+91 93270 01792) · St. Xavier's Academy (+91 97231 30569) · Soneev Academy (+91 98798 38405) · H N Learning Center (+91 90336 50935) · I.I.T Academy (+91 74052 43752) · Ambica Classes (+91 98989 82996) · Unique Tuition (+91 85307 39614) · ABC Classes (+91 98248 63454) · Account's Academy (+91 81281 72251) · Talent Education (+91 76000 59059) · Eklavya Academy (+91 93133 29074) · Bhoraniya Guidance (+91 94260 26356)

**Three pains that sell in this category:** (1) fee opacity — parents distrust unpublished fees; (2) results are their only marketing and nobody has a results page; (3) batch/timing confusion drives constant phone calls.

### Other domains evaluated
- **Banquet halls / party plots** — strong: high-value bookings, no published capacity or pricing anywhere
- **Travel agencies** — already SEO-conscious (stuffed Google listing names) = they believe in online visibility
- **Wedding photographers** — pay well, will judge design harshly. Not a beginner niche
- **Skip:** dental (2,000+ review saturation), gyms, cafés, CAs, salons

### Sales rules I agreed to
- No fake stories or invented customers (rejected a "my uncle wanted furniture" pretext — dishonest and doesn't survive a follow-up question)
- Send follow-ups on **WhatsApp**, not email. No PDF company profiles — a tappable link or nothing
- No pricing over WhatsApp before they've seen something
- 3 follow-up touches maximum, then stop
- Track every call in a sheet: name, number, date, outcome, next action
- **Standing critique:** I over-research and under-call. ~60 named leads gathered, 1 call made. Research feels like work and isn't.

---

## 6. What I want to build next (Cowork session)

**Goal:** rebuild the MyCraft portfolio as a **3D, interactive, game-like website** — users can move through/interact with it rather than scroll a normal page.

**Claude's honest concerns to raise at the start of that session:**
1. My buyers are 40–55 year old Rajkot business owners on mid-range Android phones over 4G. A WebGL site is slow to load, confusing to navigate, and signals "student showing off" rather than "reliable vendor who'll still be around in six months."
2. A 3D portfolio proves I can build a 3D portfolio. It does not prove I can build a fee-structure page for a tuition class. Prospects hire based on seeing work that resembles their own problem.
3. Opportunity cost: the same weekend spent building a spec page for Success Educational Services is worth more than a 3D site.
4. Violates my own rule — "never ship anything I couldn't rebuild by hand" — if it's vibecoded Three.js I don't understand.

**Where a 3D build genuinely does make sense:** as a *separate* showcase page (`/lab` or similar) linked from the normal portfolio, aimed at the gaming-café niche specifically, and as an actual product I could sell to a game zone. Not as the front door for coaching classes.

**If building it anyway:** Three.js r128 constraints apply in artifact contexts (no OrbitControls, no CapsuleGeometry). In a real Vercel/Next.js project use current three + @react-three/fiber + drei. Must have: a plain-HTML fallback route, a "skip to normal site" link visible immediately, and mobile perf tested on a real mid-range Android before it goes anywhere near a prospect.

---

## 7. Immediate to-do (before any new building)

1. Fill the 5 placeholders in `mycraft-portfolio-v2.html`
2. Host it (Netlify drop / GitHub Pages) — get a real link
3. Add screenshots for Tally, ScholarNode, VidyaVani
4. **Send the WhatsApp follow-up to Brijesh Mehta** — this is 12+ hours overdue and is the only thing on this list that can produce revenue
5. Build a spec page for Success Educational Services (results + batch timings + fees + enquiry form) — reusable as the demo for all 12 coaching leads
6. Start the call-tracking sheet
