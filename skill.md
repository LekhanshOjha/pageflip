---
name: pageflip
description: Write, rewrite, or audit landing page copy for maximum conversion — problem-first, audience language, one CTA, objection-matched proof, and scannable headlines.
---

# High-Converting Landing Page

This skill writes and audits landing pages built to convert. Most pages sit at 2–3% because they lead with features, speak in marketing language, and ask for too many things. This skill fixes that with six conversion rules, grounded in how the audience actually talks about their problem.

Treat the rules as strong heuristics, not laws. Conversion numbers quoted online are rarely verified, and testing beats any rule.

## Step 1 — Gather the basics

Ask only for what is missing:
- What the product is and who it is for (be specific: "solo SaaS founders with <$5k MRR", not "businesses")
- The ONE action the page should drive (signup, waitlist, purchase, book a call)
- The top 1–3 objections a skeptical visitor would have
- Any real testimonials, numbers, or proof the user already has

## Step 2 — Collect the audience's voice (required)

Check whether `audience-voice.md` already exists (attached, in the working directory, or pasted in chat).

**If it doesn't exist:**
1. Create `audience-voice.md` from the template at the bottom of this file. Fill in the product name and audience at the top.
2. Send the file to the user and tell them:
   - Paste raw quotes **exactly as written**, including typos, slang, and swearing. Don't clean them up.
   - Use wherever their audience talks honestly: customer and sales calls, support emails, competitor reviews (especially 2–3 star ones), communities and forums, social replies, comments, surveys.
   - Aim for at least 15–20 quotes. More is better.
   - Note where each batch came from in the Sources section.
3. **Stop and wait** for the filled file. Do not write copy yet.

**If the user refuses or wants to skip:** proceed, but label every headline and pain statement `[PLACEHOLDER VOICE — replace with real quotes]`, and say plainly that this version is a guess.

**Never invent quotes and present them as real audience language.**

## Step 3 — Mine the voice file

Before writing, produce a short **phrase bank** from the file:
- **Pain phrases**: how they describe the frustration, in their exact words, ranked by how often similar wording appears
- **Failed attempts**: what they've tried that didn't work
- **Desired outcome**: the result they want, in their words
- **Fears and objections**: what they're afraid of or skeptical about
- **Their vocabulary**: words they use for the problem and category, and corporate words they never use

Show this phrase bank to the user so they can correct the read before the copy is built on it.

## Step 4 — Write the page using the 6 conversion rules

### Rule 1 — Problem before product
The entire first screen makes the reader feel understood. Lead with their pain, in their words. Don't mention the product name or features above the fold beyond the CTA button.

### Rule 2 — Mirror their language
Every headline and pain statement should trace back to a phrase in the phrase bank. Prefer "I'm tired of starting over every Monday" over "Achieve your fitness goals with our proven system." If a line sounds like marketing, rewrite it in their vocabulary.

### Rule 3 — One page, one goal
Exactly ONE call to action, repeated in several places if needed (hero, mid-page, end). No "follow us", no "read our blog", no secondary signup. Remove nav links that pull people away if possible.

### Rule 4 — Proof goes right after the objection
Map each objection to the section that raises it. Place the strongest matching testimonial or proof **immediately after** that section, not in a generic testimonials block at the bottom. If the user has no proof for an objection, flag the gap; don't fabricate one.

### Rule 5 — Headline formula
Draft the H1 with this pattern:

**[End result they want] + [Time frame] + [Without the thing they fear]**

- "Get your first 100 customers in 30 days without spending a dollar on ads"
- "Launch your course this weekend without writing a single line of code"

Write 5 variants. Pull the result and the fear from the phrase bank. Only use a time frame the product can honestly deliver.

### Rule 6 — The headlines must tell the whole story
Visitors scan. Reading only H1 → H2 → H2 → H2 should give the full pitch: problem → why it persists → what changes → proof → what to do. Write the headline sequence first, then the body copy under each.

## Step 5 — Recommended page structure

1. **Hero**: H1 (formula), subhead in their pain language, single CTA
2. **The problem**: their frustration, quoted or near-quoted
3. **Why it keeps happening / what they've tried**: their failed attempts
4. **The shift**: what's different about this approach (first real product mention)
5. **How it works**: 3 steps max
6. **Objection sections**: each followed directly by matched proof
7. **Final CTA**: restate the outcome, same single action

Adjust the structure to the product, but keep Rules 1, 3, 4, and 6 intact.

## Step 6 — Self-check before delivering

- [ ] First screen is about the reader, not the product
- [ ] Every headline traces back to a phrase in audience-voice.md (or is labelled placeholder)
- [ ] Exactly one CTA action on the page
- [ ] Each objection is followed immediately by proof, or the gap is flagged
- [ ] H1 follows the result + time frame + without-fear pattern, and the claim is honest
- [ ] Reading only the headlines in order tells the full story
- [ ] No invented testimonials, numbers, or quotes

## Output

Deliver:
1. The phrase bank (Step 3)
2. The headline-only skeleton (scan test)
3. The full page copy, section by section
4. 5 H1 variants
5. Conversion gaps: missing proof, weak objections, places that need more audience quotes

For an **audit** of an existing page, score it against each of the 6 rules (pass / weak / fail), quote the offending lines, and give rewrites using the user's audience-voice.md.

---

## audience-voice.md template

Create this file for the user exactly as below, filling in the first two lines:

```markdown
# Audience Voice — [Product name]

**Who this audience is:** [e.g. solo SaaS founders, pre-revenue, building in public]

> Paste quotes EXACTLY as people said or wrote them — typos, slang, swearing included.
> Don't paraphrase. Raw language is what makes the page convert.
> Target: 15–20+ quotes total.

## Sources
<!-- Where these quotes came from: calls, support emails, reviews, communities, surveys -->
-
-

## 1. The pain — how they describe the problem
<!-- "I'm so sick of...", "Why is it so hard to...", rants, venting -->
- ""
- ""
- ""

## 2. What they've already tried (and why it failed)
<!-- Tools, hacks, courses, competitors they've given up on -->
- ""
- ""

## 3. What they actually want — the outcome in their words
<!-- "I just want to...", "If only I could..." -->
- ""
- ""

## 4. Fears, doubts, and objections
<!-- "Sounds too good to be true", "I don't have time", "I tried X and got burned" -->
- ""
- ""

## 5. Words they use for the problem / category
<!-- Their terms, not yours. e.g. "ghosted by customers" vs "churn" -->
-
-

## 6. Words and phrases that turn them off
<!-- Corporate speak, buzzwords they mock -->
-

## 7. Existing proof you have
<!-- Real testimonials, user counts, results, screenshots. Leave empty if none. -->
-

## 8. Anything else
<!-- Patterns you noticed, recurring jokes, strong opinions -->
-
```