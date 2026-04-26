# freespeechapp.com — Single-Page Landing Site Spec

**Document Purpose:** Complete content specification for freespeechapp.com — a single-page, conversion-optimized marketing site for FreeSpeech. This is the link you put in cold emails to SLPs, Facebook posts, conference slides, and App Store developer URL fields. It tells the FreeSpeech story compellingly in one scroll, with prominent download buttons, and links to samartya.com for everything deeper.

**Design Philosophy:** FreeSpeech's core magic is the moment a child drags picture tiles into a grid and watches a grammatically correct sentence appear. The page should make the visitor *feel* that moment as quickly as possible. Lead with the transformation, not the technology. The audience is split roughly 70/30 between professionals (SLPs, special educators, AT specialists) and parents — the tone should be warm and accessible but never simplistic. These are people who take evidence seriously.

**Technical Notes:**
- Single page, no internal navigation (smooth-scroll anchors only)
- Static HTML — no CMS needed, can be hosted free on Cloudflare Pages / Netlify / Vercel
- Must load fast on mobile (many SLPs will open this on a phone between therapy sessions)
- Separate deployment from samartya.com
- Cookie consent banner for compliance

---

## Top Navigation (Minimal)

```
[FreeSpeech logo/wordmark]                         [Download ▾]
```

- "Download" is a dropdown or scrolls to the download section: iOS / Android links
- No other nav items. The page is self-contained. Links to samartya.com appear in context and in the footer.

---

## Section 1: Hero

**Headline:**
Grammar you can see, touch, and hear.

**Subheadline:**
FreeSpeech is the only app that teaches grammar through pictures. Children drag and drop visual tiles to build sentences — and FreeSpeech converts them into grammatically correct English, spoken aloud. No rules to memorize. No worksheets. Just language, made visible.

**CTA Buttons:**
[Download Free on iOS] [Download Free on Android]

**Supporting text below CTAs:**
Free to download. Full 14-day trial. No credit card required.

**Visual:** A short looping video (10–15 seconds, autoplaying, muted) or an animated GIF showing the core interaction: a child (or a pair of hands) dragging a picture tile onto the grid, a sentence updating in real time, and the sentence being spoken. If video isn't ready, use a high-quality screenshot of the picture grid mid-sentence-build, with a completed sentence visible below the grid.

---

## Section 2: The Problem (Empathy-First)

**Headline:**
For millions of children, the rules of language are invisible.

**Body copy:**
Most of us learned grammar without thinking about it. Subject before verb. Add "-s" when it's "he" instead of "I." Past tense changes "eat" to "ate," not "eated." We absorbed these patterns as toddlers, effortlessly.

But for children with autism, language disorders, or hearing impairments, these rules don't come for free. The patterns are invisible. Grammar workbooks full of abstract rules don't help — they ask children to reason about something they've never been able to perceive.

What if grammar wasn't invisible? What if a child could *see* it?

---

## Section 3: The Solution (Product Introduction)

**Headline:**
FreeSpeech makes the invisible rules of language visible.

**Three-column layout (stacked on mobile):**

**Column 1: Pictures, not rules.**
[Icon: grid/tiles]
Every word is a picture. Every grammatical relationship — tense, number, person, sentence type — is a visual property on a grid. Children manipulate language the same way they'd arrange blocks: by seeing and touching.

**Column 2: Instant, correct sentences.**
[Icon: speech/text]
FreeSpeech doesn't just let children arrange pictures — it understands the grammar behind the arrangement. Swap "I" for "he" and watch "eat" become "eats" automatically. The child sees cause and effect, not a rule to memorize.

**Column 3: Spoken aloud.**
[Icon: sound wave]
Every sentence is spoken in a clear, natural voice. The child hears their own thought — assembled from pictures — expressed as real language. That moment is powerful.

---

## Section 4: Demo (Visual Walkthrough)

**Headline:**
See it in action.

**Option A (preferred):** Embedded product demo video, 60–90 seconds. The video should show:
1. The picture grid, empty
2. A child (or therapist's hand) dragging picture tiles: a person, an action, an object
3. The sentence forming in real time below the grid
4. Changing one tile (swapping "I" for "she") and the sentence automatically adjusting ("eat" → "eats")
5. Tapping "speak" and hearing the sentence read aloud
6. A brief flash of a therapist creating a challenge set (showing the professional workflow)

Voiceover or text captions. Keep it real and warm.

**Option B (if video isn't ready):** A horizontal scroll of 4–5 annotated screenshots walking through the same flow. Each screenshot has a one-line caption.

---

## Section 5: The "Aha" Moment

**Headline:**
Watch what happens when you change one picture.

**Body copy:**
This is the moment that makes FreeSpeech different from every other language app.

A child has built a sentence: **"I eat lunch."**

Now they drag the "he" tile to replace "I." Instantly, the sentence becomes **"He eats lunch."** The child didn't learn a rule about third-person singular conjugation. They *saw* it happen.

They drag the "past" marker onto the grid. The sentence becomes **"He ate lunch."** Irregular past tense — one of the hardest things to teach — demonstrated in a single gesture.

This is what we mean by "grammar made visible." The child isn't memorizing rules. They're discovering patterns by playing with pictures.

**Visual:** A before/after or animated comparison showing the sentence transformation described above. Two states side by side, or an animated transition between them.

---

## Section 6: Key Features (Scannable)

**Headline:**
Built for therapy sessions. Loved by kids.

**Feature grid — two-column, compact cards with icon + bold title + one sentence each:**

🧩 **Picture-Based Sentence Building**
Drag and drop picture tiles onto a visual grid. FreeSpeech handles the grammar automatically.

🎯 **Therapy Challenges**
Create custom challenge sets aligned to IEP goals. Assign them to students. Review their completed sentences.

📊 **Adjustable Scaffolding**
Control how much grammatical support the app provides — from fully guided sentence frames to open-ended creation. Reduce scaffolding as the child progresses.

📚 **Vocabulary Levels**
Adjust the available vocabulary from basic everyday words to advanced concepts, tenses, and abstract language. Match each student's current level.

✏️ **Writing Support**
Import any image as a writing prompt. Students build sentences describing the image using picture tiles — bridging the gap between visual comprehension and written expression.

🌍 **Multi-Language**
Generate sentences in English, Spanish, and Arabic from the same visual grammar system. The picture-based approach transcends specific languages.

🔇 **Works Offline**
No internet required after download. Use FreeSpeech in a therapy room, a classroom, at home — anywhere.

👥 **Multiple Profiles**
Set up profiles for different students, each with their own vocabulary level, scaffolding settings, and challenge sets.

---

## Section 7: Who FreeSpeech Is For

**Headline:**
Made for the people who never give up on a child's voice.

**Four audience cards:**

**Children with Autism & Language Disorders**
Many children with autism understand far more than they can express. FreeSpeech gives them a way to build complex sentences they couldn't produce through speech or writing alone — revealing a language ability that was always there, just waiting for the right tool.

**Children Who Are Deaf or Hard of Hearing**
English grammar and ASL grammar are structurally different. FreeSpeech represents English grammar visually, allowing Deaf students to learn English literacy without filtering through spoken language first.

**English Language Learners**
FreeSpeech's picture-based system works independently of the child's first language. Students explore how English grammar works by seeing and manipulating it — not by translating from another language.

**Speech-Language Pathologists & Therapists**
FreeSpeech fits into your clinical workflow. Create challenges aligned to IEP grammar goals. Adjust scaffolding per student. Use it in individual or group sessions. The app does the grammar; you do the therapy.

[See how schools use FreeSpeech →] (links to samartya.com/for-schools)

---

## Section 8: The TED Talk

**Headline:**
The idea that started it all.

[Full TED talk embed — Ajit Narayanan, "A word game to communicate in any language"]

**Body copy below the video:**
In 2013, Ajit Narayanan took the TED stage to share a radical idea: what if we could represent grammar as pictures — not as rules, but as spatial relationships that anyone could see and manipulate? What started as a research insight became FreeSpeech, now used by therapists, educators, and families worldwide.

The talk has been viewed over 1 million times and translated into dozens of languages.

FreeSpeech was originally developed as Avaz FreeSpeech. It is now part of Samartya Apps, and continues to be developed by the same team that brought it from a TED stage to your child's hands.

---

## Section 9: Evidence & Recognition

**Headline:**
Trusted by experts. Recognized worldwide.

**Horizontal badge/logo row:**

🏆 **Apple Best New App** — Featured on the App Store
🎤 **TED Talk** — 1M+ views, translated into 30+ languages
🧪 **MIT Technology Review TR35** — Named top innovator under 35
🏅 **National Award** — From the President of India for disability empowerment
🤝 **Used in schools** across the United States and India

**Body copy:**
FreeSpeech's visual grammar system was developed through original research into how the brain processes language. It has been validated with children with autism and language impairments, and its underlying methodology has been recognized by MIT Technology Review, TED, and the Government of India.

[Read more about our research →] (links to samartya.com/research)

---

## Section 10: Testimonials

**Headline:**
What therapists, teachers, and parents say.

**Testimonial cards (3–4):**

"I use this with my kids who have language disorders and this app goes very far in helping them expand their language. I love it and it is a very well designed app! Well worth any price!"
— Speech-Language Pathologist

"Language structure made visual. What a wonderful way to help kids really 'see' language structure."
— Educator

"It is probably the only app I've seen that actually makes it fun and stress-free to work with English sentences."
— Therapist

"My son has autism and struggles with sentence structure. This app has been a game changer for his therapy sessions. He actually enjoys building sentences now."
— Parent

[Note: Use actual reviews. Replace or supplement with direct testimonials as they are collected.]

---

## Section 11: Pricing

**Headline:**
Free to try. Built to be affordable.

**Body copy:**
FreeSpeech is free to download with a full 14-day trial. After the trial, choose the plan that fits.

**Pricing table:**

| Plan | USA | India |
|------|-----|-------|
| Monthly | $9.99/month | ₹99/month |
| Annual | $99.99/year | ₹999/year |
| Lifetime | [one-time price] | [one-time price INR] |

**For Schools & Districts:**
Lifetime licenses are available through Apple's Volume Purchase Program (VPP) with 50% off for purchases of 20 or more licenses. We also support purchase orders and institutional invoicing.

[See school pricing and request a free evaluation →] (links to samartya.com/for-schools)

**Design note:** Show India pricing only to Indian visitors via geolocation, or provide a USD/INR toggle. Don't show both by default.

---

## Section 12: Comparison (Optional — Include If Space Allows)

**Headline:**
FreeSpeech is not an AAC app. Here's the difference.

**Body copy:**
People sometimes ask how FreeSpeech compares to AAC (augmentative and alternative communication) apps like Proloquo2Go or TouchChat. The answer: they solve different problems.

AAC apps help children who cannot speak to communicate in the moment — selecting pictures or symbols to express immediate needs and thoughts. They're essential communication tools.

FreeSpeech is a *language learning* tool. It teaches the *structure* of language — grammar, sentence building, tense, word order — through visual manipulation. The goal isn't to replace speech in the moment, but to build the underlying language competence that supports speech, writing, and reading over time.

Many therapists use both: an AAC app for daily communication and FreeSpeech for language therapy sessions focused on grammar goals.

**Design note:** This section addresses the most common misconception about FreeSpeech and is important for SEO (people searching for "AAC apps" may find FreeSpeech and need to understand the distinction). However, if the page feels too long, this section can be moved to a FAQ item or to the samartya.com/freespeech page instead.

---

## Section 13: Download / Final CTA

**Headline:**
Start building sentences today.

**Two CTA options, presented prominently:**

[Download Free on iOS] → App Store link
[Download Free on Android] → Google Play link

**Subtext:**
Free 14-day trial. No credit card required.

**Secondary CTA (smaller, below):**
Are you evaluating FreeSpeech for your school or district?
[Request a free evaluation with extended access →] (links to samartya.com/for-schools/request-trial)

---

## Section 14: FAQ (Collapsed/Accordion)

**Headline:**
Common questions.

**Q: What age range is FreeSpeech designed for?**
A: FreeSpeech is used with children from age 4 through to teenagers, and even adults. The adjustable vocabulary levels and scaffolding settings allow it to serve a wide range of language abilities. Most commonly, it's used with children ages 5–14 in speech therapy and special education settings.

**Q: Does my child need to know how to read to use FreeSpeech?**
A: No. FreeSpeech is picture-based — children interact with visual tiles, not text. The app speaks the sentences aloud, so reading ability is not a prerequisite. As the child progresses, they begin to associate the pictures with written words naturally.

**Q: Is this an AAC app?**
A: No. AAC apps (like Proloquo2Go or Avaz AAC) help non-speaking children communicate in the moment. FreeSpeech is a language *learning* tool that teaches grammar and sentence structure. Many therapists use both — an AAC app for daily communication and FreeSpeech for grammar intervention.

**Q: Can I use FreeSpeech in therapy sessions?**
A: Absolutely — that's what it's designed for. You can create custom challenge sets aligned to IEP goals, adjust vocabulary and scaffolding levels per student, and review completed work. FreeSpeech fits naturally into individual and group therapy sessions targeting grammar objectives.

**Q: What devices does FreeSpeech work on?**
A: FreeSpeech is available on iPad and iPhone (iOS) and Android tablets and phones. It works offline after download.

**Q: Does FreeSpeech support languages other than English?**
A: Yes. FreeSpeech can generate sentences in English, Spanish, and Arabic. The visual grammar system is language-independent at its core — the same picture arrangement produces correct grammar in each supported language.

**Q: How much does it cost?**
A: Free to download and try for 14 days. Plans start at $9.99/month, with annual and lifetime options. Schools get 50% off lifetime licenses through Apple VPP for 20+ licenses.

**Q: What's the relationship between FreeSpeech and Avaz?**
A: FreeSpeech was originally developed by Avaz Inc. as "Avaz FreeSpeech." In 2025, it was acquired by Samartya Apps, which now develops and supports it. The same team and research vision continue under the Samartya Apps brand. Avaz Inc. continues to develop Avaz AAC, which is a separate product.

**Q: Is FreeSpeech backed by research?**
A: Yes. FreeSpeech's visual grammar system is based on original research into how the brain processes language, and was the subject of a TED talk viewed over 1 million times. Its creator was named an MIT Technology Review TR35 innovator. [Learn more about the research →] (links to samartya.com/research)

---

## Footer

```
FreeSpeech is a product of Samartya Apps.

Products                Company                 Legal
FreeSpeech              About Samartya Apps      Privacy Policy
Dyslexia Reader         Research & Evidence      Terms of Use
For Schools             Blog
                        Contact

Download
[App Store badge]  [Google Play badge]

Follow Us
[Facebook] [Instagram] [LinkedIn] [YouTube]

© 2026 Samartya Apps. All rights reserved.
```

All "Company" links go to samartya.com.
"Dyslexia Reader" links to dyslexiareader.com.
"For Schools" links to samartya.com/for-schools.

---

## SEO & Technical Specification

**SEO Title:** FreeSpeech — Teach Grammar Through Pictures | Language App for Autism & Special Needs
**Meta Description:** FreeSpeech is the only app that teaches grammar visually. Children drag and drop picture tiles to build sentences — the app handles the grammar automatically. Based on a TED talk with 1M+ views. Used by SLPs and educators. Free to try.
**Canonical URL:** https://freespeechapp.com

**Target Keywords (primary):**
- grammar app for autism
- visual grammar app
- picture sentence builder app
- language app for special needs
- speech therapy grammar app

**Target Keywords (secondary):**
- teach grammar to autistic child
- language learning app autism
- SLP grammar intervention app
- visual language therapy
- ESL grammar app for kids
- sentence building app special education

**Open Graph / Social Sharing:**
- og:title — "FreeSpeech — Teach Grammar Through Pictures"
- og:description — "The only app that makes grammar visible. Drag and drop pictures to build sentences. Based on a TED talk with 1M+ views. Free to try."
- og:image — Product screenshot or hero image (1200×630px) showing the picture grid with a sentence
- og:url — https://freespeechapp.com
- twitter:card — summary_large_image

**Schema Markup:**
```json
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "FreeSpeech",
  "operatingSystem": "iOS, Android",
  "applicationCategory": "EducationApplication",
  "offers": [
    {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "USD",
      "description": "Free 14-day trial"
    },
    {
      "@type": "Offer",
      "price": "9.99",
      "priceCurrency": "USD",
      "description": "Monthly subscription"
    },
    {
      "@type": "Offer",
      "price": "99.99",
      "priceCurrency": "USD",
      "description": "Annual subscription"
    }
  ],
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "[actual rating]",
    "ratingCount": "[actual count]"
  },
  "author": {
    "@type": "Organization",
    "name": "Samartya Apps",
    "url": "https://samartya.com"
  }
}
```

**Analytics:**
- Google Analytics 4 (same property as samartya.com, separate data stream)
- Event tracking on:
  - App Store download clicks (iOS)
  - Google Play download clicks (Android)
  - "For Schools" link clicks (to samartya.com)
  - TED talk video plays (this is a key engagement signal)
  - Demo video plays
  - FAQ accordion opens (which questions do visitors read most?)
  - Scroll depth
  - Time on page

**Performance:**
- Target: <2 second load on mobile (3G connection)
- Lazy load all images and video embeds below the fold
- Inline critical CSS
- Pure HTML/CSS with minimal JS (FAQ accordion, optional animation)
- Host on CDN (Cloudflare Pages, Netlify, or Vercel — free tier)

---

## Key Differences from dyslexiareader.com

While both landing pages follow the same structural pattern (hero → problem → solution → demo → features → audiences → credibility → testimonials → pricing → download → FAQ), the FreeSpeech page has several important distinctions:

**1. The "Aha Moment" section (Section 5) is unique to FreeSpeech.** The tile-swapping interaction ("I eat" → "He eats" → "He ate") is FreeSpeech's most compelling demo moment and deserves its own section with a visual. Dyslexia Reader's equivalent is the scan-and-read flow, which is covered in the How It Works section.

**2. The TED talk gets a full section.** The TED talk is FreeSpeech's single most powerful credibility asset. It earns a dedicated, prominent section — not just a mention. On dyslexiareader.com, the MDA partnership fills this role.

**3. The AAC clarification (Section 12) addresses FreeSpeech's most common positioning confusion.** People who find FreeSpeech through search often conflate it with AAC apps. This section (or FAQ item) draws the line clearly. Dyslexia Reader doesn't have this confusion — it's clearly a reading tool.

**4. No web version section.** FreeSpeech currently has no web version, so there's no waitlist or "Try on Web" CTA. If a web version is ever developed, this page would gain a section similar to dyslexiareader.com's Section 9.

**5. The ESL angle is mentioned but not featured.** ESL is a secondary market for FreeSpeech. It's mentioned in the "Who It's For" section but doesn't get top billing. If Samartya decides to pursue the ESL market more aggressively in the future, a dedicated ESL landing page (or a modified variant of this page) would be appropriate.

---

## Page Variants

### Variant: Autism Acceptance Month (April)

During April, modify the hero section:

**Badge above headline:** 💙 April is Autism Acceptance Month

**Modified headline:**
Every child has something to say. FreeSpeech helps them build the sentences to say it.

**Additional CTA:**
[Share FreeSpeech with a therapist or teacher →] (pre-composed sharing link)

### Variant: Better Speech and Hearing Month (May)

**Badge above headline:** 🗣️ May is Better Speech and Hearing Month

**Modified subheadline addition:**
This month, we're offering extended 30-day trials for SLPs. [Claim yours →]

### Variant: Back to School (August–September)

**Additional banner or section:**
Starting the school year? FreeSpeech integrates into IEP grammar goals. Free evaluation copies for schools.
[Request a school evaluation →] (links to samartya.com/for-schools/request-trial)

---

## Relationship to Other Sites (Summary)

```
freespeechapp.com (THIS PAGE)
│
├── Links OUT to:
│   ├── App Store — iOS download
│   ├── Google Play — Android download
│   ├── samartya.com/for-schools — school pricing, trial requests
│   ├── samartya.com/for-schools/request-trial — evaluation form
│   ├── samartya.com/research — evidence, TED talk, awards
│   ├── samartya.com/about — company info
│   ├── samartya.com/blog — articles and resources
│   ├── samartya.com/contact — inquiries
│   ├── dyslexiareader.com — sister product (footer only)
│   └── ted.com/talks/ajit_narayanan... — TED talk page
│
├── Links IN from:
│   ├── Email campaigns (cold outreach to SLPs, AT specialists)
│   ├── Facebook/Instagram posts and ads
│   ├── Conference slides and handouts
│   ├── TED talk description (if updated with current URL)
│   ├── App Store / Google Play developer website field
│   ├── SLP blogs and review sites
│   ├── samartya.com/freespeech (cross-link)
│   └── QR codes on printed materials
│
└── Does NOT duplicate:
    └── samartya.com/freespeech (which has sub-pages for
        therapists and parents, and sits within the broader
        Samartya brand context)
```

---

## Build Priority and Timeline

**Build now (Month 1):**
- Full page as specified
- All sections live
- iOS and Android download buttons
- TED talk embed
- FAQ

**Month 2–3 iteration:**
- Replace placeholder testimonials with real collected quotes
- Add demo video when recorded
- Add "Aha Moment" animation/visual if an animated version can be produced
- Link to published blog posts and case studies on samartya.com

**Seasonal updates (ongoing):**
- Swap in Autism Acceptance Month variant (April)
- Swap in Better Speech and Hearing Month variant (May)
- Swap in Back to School variant (August–September)
- Update pricing if it changes
- Add new testimonials as collected

---

*End of freespeechapp.com specification.*
