# Cohort #4 Landing Page - Implementation Guide

> Backend reference for building, launching, and optimizing the Cohort #4 landing page

---

## 📊 VALUE STACK (Optional Section - Place Above FAQ)

### Section Header
**"What you're really getting for $500"**

### Value Breakdown

| What's Included | Value |
|----------------|-------|
| 5 Monday Workshops (expert-led frameworks) | $500 |
| 5 Wednesday Coworking Sessions (live accountability) | $250 |
| 5 Friday Personal 1:1s with Nik (30min each) | $750 |
| Momentum Builders Platform (5-week access) | $200 |
| 24/7 Community Support (WhatsApp + platform) | $150 |
| Participant Perks (Lovable credits + more) | $300 |
| Grand Prize Eligibility ($500+ prize pool) | $500+ |
| Lifetime Alumni Access | Priceless |
| **Total Value** | **$2,650+** |
| **Your Investment** | **$500 CAD** |

**ROI:** If you ship one product, land one client, or make one career move from this—the $500 pays for itself 10x over.

---

## 🎨 DESIGN NOTES & VISUAL ELEMENTS

### Color Palette
- **Primary:** Orange (#FF8C00)
- **Secondary:** White
- **Accent:** Black text
- **Background:** White/Light gray sections

### Typography
- **Headlines:** Bold, large sans-serif (e.g., Inter, Poppins)
- **Body:** Medium weight, readable (16-18px)
- **CTAs:** Bold, high contrast

### Visual Style
- Rounded corners throughout (buttons, cards, images, video player)
- Clean, modern, minimal
- Heavy use of real product screenshots and platform mockups
- Founder photos for social proof (past participants)
- Icon-based benefit communication (simple, clear icons)

### Layout Pattern
- Single column, mobile-first design
- Clear visual sections with breathing room (white space)
- Repetition of key CTAs (top + bottom)
- Progressive disclosure (introduce features section by section)

### Mobile Optimization
- Video: Full-width, tap-to-play
- CTA buttons: Thumb-friendly size (min 44px height)
- Platform screenshots: Optimized for small screens (zoom-in feature?)
- FAQ: Accordion/collapsible format

---

## 🔧 TECHNICAL IMPLEMENTATION NOTES

### Video Embed
- Host on: YouTube, Vimeo, or self-hosted?
- Autoplay (muted) on desktop, tap-to-play on mobile
- Add captions/transcript for accessibility
- Thumbnail: First frame should be compelling (Nik looking at camera)

### Stripe Integration
- CTA button links to: [Stripe checkout URL]
- Pre-fill checkout with: Cohort #4, $500 CAD, Nov 17-Dec 19
- Post-purchase: Redirect to confirmation page + welcome email
- Test flow on mobile + desktop before launch

### Spot Counter
- If real-time: Integrate with Stripe API or manual update
- If static: Update manually as spots fill ("8/12 spots filled")
- Creates urgency—update frequently during launch week

### Platform Screenshots
- Generate Figma mockups before Nov 17
- Show: OKR dashboard, action items list, progress tracker, reflection prompts
- Make it look real (not vaporware)—build trust

### Date Updates
- Find/replace all instances: Ensure consistency
- Nov 17 - Dec 19, 2025 (5 weeks)
- Remove any old cohort dates (Sep 20-Nov 7)

---

## 📝 COPY TONE NOTES

### Tone for Cohort #4

- **Energetic but elevated:** Keep the "togetherness" vibe, but signal this is a serious investment
- **Vulnerable + confident:** Share struggles (solo building = stuck) but position MOMENTUM as proven solution
- **Community-first, not guru-y:** Nik builds *alongside* you, not above you
- **Action-oriented:** Lots of verbs—"Lock in," "Build," "Ship," "Win"
- **Specific over vague:** Numbers, outcomes, dates (not "transform your life")

### Avoid

- Corporate jargon ("synergy," "thought leader")
- Over-the-top hype ("revolutionary," "game-changing")
- Guru positioning ("I'll teach you the secrets")
- Vague promises ("achieve your dreams")
- **Hyphens in copy** (user preference)

### Embrace

- Real founder struggles (stuck, deferred dreams, excuses)
- Concrete outcomes (shipped products, OKR completion)
- Community language ("we," "together," "alongside")
- Personal stakes ("$500 investment," "most progress wins")

---

## ✅ PRE-LAUNCH CHECKLIST

**Before going live:**

- [ ] Announcement video edited and uploaded
- [ ] All dates updated to Nov 17 - Dec 19, 2025
- [ ] Stripe checkout page created and tested
- [ ] CTA buttons linked to Stripe (test on mobile + desktop)
- [ ] Platform mockups generated (Figma)
- [ ] Platform screenshots added to "Mission Control" section
- [ ] Perks finalized (Lovable credits + 2-3 others)
- [ ] Grand prize details confirmed ($500 + service value)
- [ ] Testimonials pulled from testimonials.md (outcome-focused)
- [ ] FAQ answers reviewed for accuracy
- [ ] Spot counter mechanism decided (real-time or manual)
- [ ] Mobile optimization tested (video, CTA buttons, platform images)
- [ ] Typos/grammar check (run through Grammarly or similar)
- [ ] Social proof stats verified (38/40 accuracy)
- [ ] Value stack calculations accurate
- [ ] Email/DM follow-up flow ready for post-checkout
- [ ] LinkedIn launch post drafted (announce cohort opening)

---

## 🚀 LAUNCH STRATEGY INTEGRATION

### How this page fits into the Cohort #4 launch

1. **Week 1 (Pre-launch):** Tease announcement video on LinkedIn, drive traffic to landing page in "coming soon" mode
2. **Week 2 (Launch week):** LinkedIn post series (see strategy.md Pillar 2), all CTAs → landing page
3. **Week 3-4 (Urgency phase):** Update spot counter, share testimonials, "X spots left" posts
4. **Week 5 (Final push):** "Last 2 spots" urgency, close applications Nov 15

**Landing page goal:** Convert 12-16 qualified applicants from LinkedIn traffic + DMs

---

## 📈 SUCCESS METRICS TO TRACK

Post-launch, track these metrics:

- **Page visits** (from LinkedIn, DMs, other sources)
- **Video play rate** (% who watch announcement video)
- **Scroll depth** (do people reach FAQ? Testimonials?)
- **CTA click rate** (how many click "Join Cohort #4"?)
- **Stripe checkout completion rate** (clicks → payments)
- **Time on page** (engagement signal)
- **Bounce rate** (are people leaving immediately?)
- **Traffic sources** (LinkedIn post? DM link? Profile link?)

**Goal:** 12 paid spots filled by Nov 15 (2 days before start)

---

## 🔄 NEXT STEPS FOR NIK + CLAUDE

1. Review mockup—what's missing? What needs tweaking?
2. Finalize perks (beyond Lovable credits)
3. Confirm grand prize service/package value
4. Create Figma mockups for platform screenshots
5. Edit announcement video (in progress)
6. Set up Stripe checkout page ($500 CAD, Cohort #4)
7. Build the actual landing page (HTML/CSS or no-code tool?)
8. Draft LinkedIn launch post series (5-7 posts over 2-3 weeks)

---

**END OF IMPLEMENTATION GUIDE**
