---
name: pageflip
description: Write, rewrite, or audit landing page copy for maximum conversion. Problem first, audience language, one CTA, objection-matched proof, and scannable headlines.
---

# Pageflip — High-Converting Landing Pages

This skill writes and audits landing pages built to convert. Most pages sit at 2–3% because they lead with features, speak in marketing language, and ask for too many things. This skill fixes that with six conversion rules, grounded in how the audience actually talks about their problem.

Treat the rules as strong heuristics, not laws. Conversion numbers quoted online are rarely verified, and testing beats any rule.

## Step 1 — Gather the basics

Ask only for what is missing:
- What the product is and who it is for (be specific: "solo SaaS founders with <$5k MRR", not "businesses")
- The ONE action the page should drive (signup, waitlist, purchase, book a call)
- The top 1–3 objections a skeptical visitor would have
- Any real testimonials, numbers, or proof the user already has

## Step 2 — Collect the audience's voice (required)

Check whether `audience-voice.md` already exists in the project root (or was attached or pasted in chat).

**If it doesn't exist:**
1. Create `audience-voice.md` in the project root containing only this:

   ```markdown
   # Audience Voice — [Product name]

   <!-- Paste anything raw below: Reddit/forum posts and comments, reviews, support emails,
   call notes, tweets, survey answers. No format needed. Don't clean it up.
   More is better. -->
   ```

2. Point the user to the file and tell them to dump raw material into it: reddit posts, comments, threads No structure, no editing. Typos and slang stay.
3. **Stop and wait** until they've added material. Do not write copy yet.

**If the user refuses or wants to skip:** proceed, but label every headline and pain statement `[PLACEHOLDER VOICE — replace with real audience data]`, and say plainly that this version is a guess.

**Never invent quotes and present them as real audience language.**

## Step 3 — Find the patterns and save them

Read everything in `audience-voice.md` and work out the patterns yourself. Don't expect the data to be sorted.

Write your findings to `audience-insights.md` in the project root, keeping `audience-voice.md` untouched as the raw source. Organize it however the data suggests, but cover at least:
- **Pain phrases**: how they describe the frustration, in their exact words, ranked by how often similar wording appears
- **Failed attempts**: what they've tried that didn't work
- **Desired outcome**: the result they want, in their words
- **Fears and objections**: what they're afraid of or skeptical about
- **Their vocabulary [THE MOST IMPORTANT]**: words they use for the problem and category, and corporate words they never use

Quote exact snippets from the raw data for each finding. Show the user a short summary so they can correct the read before copy is built on it. If they add more raw data later, update `audience-insights.md`.

## Step 4 — Write the page using the 6 conversion rules

### Rule 1 — Problem before product
The entire first screen makes the reader feel understood. Lead with their pain, in their words. Don't mention the product name or features above the fold beyond the CTA button.

### Rule 2 — Mirror their language
Every headline and pain statement should trace back to a finding in `audience-insights.md`. Prefer "I'm tired of starting over every Monday" over "Achieve your fitness goals with our proven system." If a line sounds like marketing, rewrite it in their vocabulary.

### Rule 3 — One page, one goal
Exactly ONE call to action, repeated in several places if needed (hero, mid-page, end). No "follow us", no "read our blog", no secondary signup. Remove nav links that pull people away if possible.

### Rule 4 — Proof goes right after the objection
Map each objection to the section that raises it. Place the strongest matching testimonial or proof **immediately after** that section, not in a generic testimonials block at the bottom. If the user has no proof for an objection, flag the gap; don't fabricate one.

### Rule 5 — Headline formula
Draft the H1 with this pattern:

**[End result they want] + [Time frame] + [Without the thing they fear]**

- "Get your first 100 customers in 30 days without spending a dollar on ads"
- "Launch your course this weekend without writing a single line of code"

Write 5 variants. Pull the result and the fear from `audience-insights.md`. Only use a time frame the product can honestly deliver.

### Rule 6 — The headlines must tell the whole story
Visitors scan. Reading only H1 → H2 → H2 → H2 should give the full pitch: problem → why it persists → what changes → proof → what to do. Write the headline sequence first, then the body copy under each.

## Step 5 — Self-check before delivering

- [ ] First screen is about the reader, not the product
- [ ] Every headline traces back to a finding in `audience-insights.md` (or is labelled placeholder)
- [ ] Exactly one CTA action on the page
- [ ] Each objection is followed immediately by proof, or the gap is flagged
- [ ] H1 follows the result + time frame + without-fear pattern, and the claim is honest
- [ ] Reading only the headlines in order tells the full story
- [ ] No invented testimonials, numbers, or quotes

## Output

Deliver:
1. `audience-insights.md` (Step 3)
2. The headline-only skeleton (scan test)
3. The full page copy, section by section
4. 5 H1 variants
5. Conversion gaps: missing proof, weak objections, places that need more audience data

For an **audit** of an existing page, score it against each of the 6 rules (pass / weak / fail), quote the offending lines, and give rewrites using `audience-insights.md`.

