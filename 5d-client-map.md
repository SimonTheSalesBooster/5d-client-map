---
description: "Build your 5D Client Map (Define, Desire, Deficit, Deliver, Delight), then check any post, email, DM or page against it before it goes out. PASS/FIX per dimension + a rebuilt draft. By Strategy Sprints."
---

# /5d-client-map

Two modes. **Build** your map once. **Check** every draft against it before anything goes out.

Why it runs first: copywriting checks tell you if the copy is *good*. This one tells you if it is about *the right things for your client*. Polish copy that's off-map and you just get better copy about the wrong things.

## Where the map lives

Look for the map in this order: `./5d-client-map.md` filled in from the template, then `~/.claude/5d-client-map.md`, then any `me.md` / `CLAUDE.md` section titled "5D Client Map". If none exists, run **Build** first.

## Mode 1: BUILD (`/5d-client-map build`)

Interview the user one question at a time. Push for specifics in the client's own words, never category labels.

1. **Define:** Who signs the deal? What industry and size? What is happening in their business *right now* that makes them buy (a trigger you could spot from the outside)? Who is it NOT for?
2. **Desire:** What do they say they want, in the sentence they would actually use? (Hooks and subject lines get built from these.)
3. **Deficit:** What is really missing that stops them getting it? Which ONE deficit matters most? Mark it as the **yellow marker**.
4. **Deliver:** For each thing you sell or teach, which deficit does it close? Anything that closes no deficit gets flagged.
5. **Delight:** What do clients remember and tell friends about? Moments, not features.

Write the result to `./5d-client-map.md` using the template structure.

## Mode 2: CHECK (`/5d-client-map` + a draft)

Score six checks, PASS or FIX:

1. **Define:** would someone inside Define see themselves in this, and does it avoid the NOT FOR group? For broad content, never state a fact about the reader you don't know (revenue, team size). Build identification through a situation they recognise. For a 1:1 message to someone in NOT FOR: **FAIL-STOP**, don't send.
2. **Desire:** does the hook (headline, first line, subject) hit one Desire, in the client's words? FIX if it opens on you, your product, or the deficit.
3. **Deficit:** does the body surface a Deficit, ideally the yellow marker, as a situation they recognise? Indict the old way or the market, never the reader.
4. **Deliver:** does the offer or next step close the deficit the body raised? FIX on a mismatch.
5. **Delight:** is the proof real, specific and memorable? No invented clients, quotes or numbers.
6. **Stage:** which ONE buyer's-journey stage does it move (attention, start a conversation, continue it, give more value, close, upsell, referral, retention, cross-sell), and what is the reader's next step?

### Output

```
5D CHECK: PASS | FIX | FAIL-STOP
Define   PASS/FIX  <one line>
Desire   PASS/FIX  <the hook's desire, in their words>
Deficit  PASS/FIX  <which deficit; yellow marker yes/no>
Deliver  PASS/FIX  <offer -> deficit it closes>
Delight  PASS/FIX  <proof used>
Stage    <stage> -> <next step>
```

If anything is FIX: output the **rebuilt draft** with every fix applied, in the author's voice. The critique is not the deliverable. The rebuilt draft is.

Then hand the draft to your copy checks (for example `/ogilvy`). After they rewrite it, run the 5D check once more, because rewrites drift off-map.

---
Built by Strategy Sprints · https://www.strategysprints.com · Ready to accelerate now? Book a Discovery Call: https://calendly.com/strategysprint/discovery-call
