# Los Compas Landscape LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/losCompasLandscape/ · **Repo:** https://github.com/10elizabethbell/losCompasLandscape · **Built:** 2026-10-18 from Muse brief (run 2026-10-18, Hunterdon County Small Business group post)

## What's built
- One page, `index.html` (CSS and JS inline; logo, icons and og image in `assets/`). Sections: header (badge + LOS COMPAS wordmark, tap-to-call 732-527-2548 top right) → hero → What we do (Build / Care rows + Facebook card) → How it works (3 steps) → Get a free estimate (area, hours, form) → footer (name, area, hours, phone, email, Facebook).
- **World:** the logo's own colors. Pine green ground (#133a22), cream slab lettering (Alfa Slab One, inlined, 11.5 KB, chosen to match the logo's lettering), sunset gold for actions, blue (#2563a8) for form focus.
- **Signature:** the hero is a top-down herringbone paver patio with a soldier-course border on a mowed, striped lawn, covered in fall leaves (maple, oak and elm in six autumn colors).
  - Until someone touches it, an invisible "blower" works back and forth across the patio, cutting swept paths. It rests once about a quarter of the patio's leaves are gone, so a visitor always finds leaves left to clear (`AUTO_REST_AT` / `AUTO_RESUME_AT` in `CFG`).
  - A finger or mouse blows leaves away in any direction, including vertical drags on phones. A fast flick throws them into the air.
  - Leaves drift back in from the upwind side, and a few are always in the air.
- **Carried down the page:** every section edge is a strip of swaying grass in the lower section's color. A wind gust rolls along it. Leaves are caught in the blades and flick up when your finger or mouse passes.
- **Contact:**
  - Hero buttons: "Free estimate" scrolls to the form; "WhatsApp us" opens wa.me/17325272548 with a greeting.
  - Tapping a service row ticks that service in the form.
  - The form validates name plus a service or details, then opens Messages with a pre-written text to +17325272548. If Messages doesn't open within 1.5s, a "Send it on WhatsApp instead" link appears with the same text.
- **Tested headlessly:**
  - A vertical touch drag clears the leaves in its path; so does a mouse sweep.
  - No sideways scroll at 360/390/414/430.
  - Tap targets are at least 44px.
  - The SMS body is correctly encoded (`&`, quotes, `#`).
  - Ran Impeccable in every mode except live and onboard, plus a finish review.
- Tunables are in the `CFG` object at the top of the script: leaf counts and sizes, regrow rate, blower reach and force, self-sweep speed and idle time, grass sway.

## Assumptions I made
- **"We" voice.** The name means "the buddies", the logo shows two workers, and their caption says "we are professionals".
- **Headline "We treat your yard like a friend's."** It plays on *compas* (buddies). The hero line paraphrases their caption: "We're professionals, our prices are fair, and every estimate is free."
- **Email loscompaslandscapellc@gmail.com.** Muse found none. It's printed in the header of their current website, so I used it in the footer only.
- **WhatsApp.** Their current site runs a WhatsApp "Message us" widget configured to +17325272548, so I made it the second hero button.
- **Texts.** Whether they accept texts is unknown. The number is on WhatsApp, so it's a mobile, but the form's text handoff is still an assumption. WhatsApp is the fallback, and the number is in the header and the footer. I removed a call link under the form button because it sat on the same screen as the footer number.
- **Facebook label: "Follow our work on Facebook".** Their timeline couldn't be read (403), so I didn't promise "see our jobs". Once you've confirmed job photos are public there, Ellie's usual "Click to see more of our work." fits.
- **Area.** "North Brunswick, NJ, working the towns nearby", per the brief's note. Their Facebook post ran in a *Hunterdon* County group, but the Google listing is in North Brunswick (Middlesex). I didn't name any other towns.
- **Street address.** I left out 1232 Hudson Dr. It looks like a home address; the town is enough.
- **Service groups and names.** I split the services into Build (pavers & patios, driveways, retaining walls, fences, garden design) and Care (lawn mowing, lawn care, mulching, spring & fall cleanup, snow removal). The names are shortened from their caption.
- **Step 3: "We show up on the day we agreed with you."** This is inferred, not stated by them.
- **"Since 2023"** stays only inside the logo. I didn't state it as a fact anywhere.

## Placeholders and gaps
- **No photos of their work.** There are none on the brief, their old site (all template stock) or their reachable Facebook. The Facebook card under the services stands in for proof. As soon as photos exist, a gallery (or before/after sliders) belongs right above it.
- **No reviews.** The Google rating wasn't established, so nothing is shown.
- **Sunday hours** unknown; the page says Monday to Saturday only.
- **Owner's name** unknown.
- **Template claims not used.** I didn't use the old site's "15 years", "1000+ projects" or "Licensed, Bonded, Insured" claims; they're template text.
- **Logo is low-res.** It's only 359×278 (from their old site). Ask for the original file; the header uses a 112px square crop of the badge.
- **No branded Facebook preview image.** The og image is a render of the hero; Facebook's own page image couldn't be fetched (403).

## Questions for the owner
1. Do you take text messages on 732-527-2548, or is WhatsApp better? (This decides what the form's button sends.)
2. Can you send 6–10 photos of patios, driveways, walls and lawns you've done, especially before/after pairs?
3. Which towns do you cover? Hunterdon County too, or mainly around North Brunswick?
4. Are you open Sundays? Any emergency or storm snow service?
5. Your first names for the page (crews that show faces and names get more calls)?
6. Are you licensed and insured in NJ (HIC number)? If so, we can say it.
7. Any Google reviews you'd like quoted?
8. Should the page also be in Spanish?

## Ideas not built (yours to pick)
- **Winter swap (the runner-up world, and the concept seed's roll):** from December, the same hero becomes a snow-covered paver driveway you plow clear, with snowflakes on the grass edges. Same engine; swap the leaf sprites for snow and the patio for a driveway. Switch it by date.
- English/Spanish toggle in the header.
- Photo gallery inside the yard world, e.g. photos laid like pavers or resting on the lawn under the leaves, once photos exist.
- Delight: a few leaves tumble off a form chip when it's ticked (like the splash Ellie liked on Sunny Side).
- **Self-sweep tuning.** It plays once on arrival and then rests. Blown leaves pile on the lawn instead of drifting back, so it rarely resumes. If you want it to replay, have regrowth also pull leaves off the lawn piles.
- A seasonal line in the estimate section ("Fall cleanups and snow removal: book now"). I cut it because the reviewers flagged it as a throwaway opener that goes stale; it might work better as a dated banner.
- Other worlds considered:
  - mow stripes cut into shaggy grass
  - laying pavers into sand by tap
  - the logo's sunset garden as an illustrated scene
  - mulch beds with swaying plants
  - a contractor's estimate pad

## Not verified
- Real-device touch, especially that a vertical drag in the yard doesn't scroll the page in Facebook's in-app browser on iOS and Android.
- The real SMS handoff on iOS and Android, and the timing of the WhatsApp fallback in the Facebook in-app browser.
- Frame rate on older phones (≈380 leaves + 5 grass strips on phones).
- WebKit rendering (Chrome headless only).
- The Facebook link preview (og image) as shown inside Facebook itself.
