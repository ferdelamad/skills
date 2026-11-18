# storytelling-hooks

Write the opening line people stop scrolling for. This skill interviews you briefly to find the real story, then writes hooks for a short video (Reels, TikTok, Shorts) or a written post (X, Threads, LinkedIn, Instagram caption).

Built for creators and small-business owners in any niche: the florist, the trainer, the baker, the esthetician. You bring the story; the skill finds the angle.

## How it works

1. **A short interview.** A few quick questions, each with an example answer, to pull out the moment that matters: what happened, a real detail, what almost went wrong, and where you'll post. Already told your story? It asks one or two follow-ups. Say "just give me hooks" and it stops asking.
2. **Category suggestions.** It picks the 2–3 hook categories that fit your story and tells you why. You can also choose from the full menu below or ask for one by name ("give me contrarian hooks").
3. **4–6 hooks**, each labeled with its category, in the right shape for where you're posting.
4. **A quality check** before you see anything. Every hook has to use a real detail from your story, carry some tension, fit the format, and make a promise your story can keep. Hooks that fail get rewritten.
5. **A creator profile** you can paste next time (niche, audience, voice, signature stories) to skip half the questions.

## What you get

**Video hooks**
- **Hook**: the opening line, said out loud and shown as big text over the first frame, so it works with or without sound. About 12 words or fewer.
- **On screen** (when needed): a shorter version of the same line if the full one is too long to read.
- **Opening shot**: what's on camera in the first second, something you can actually film.
- **Then**: your next line, so the video delivers what the hook promised.

**Post hooks**
- **Line 1**: lands before the "...more" cutoff (about 125 characters).
- **Line 2** (optional): deepens the pull.
- **Then**: the line that starts paying it off.

## Example

> **You:** Write me a hook for a reel. A client cried in my chair last week. She'd been hiding her skin under her hair for years.
>
> **Skill:** Two quick things. What did she say or do that told you something had changed? And is this for Instagram Reels or TikTok?
>
> **You:** She asked me to take her photo. Instagram.
>
> **Skill:** This fits **Client/Customer** (her photo request is the whole story) and **Turning Point** (the moment she stopped hiding).
>
> **1. Client/Customer · Reel**
> - **Hook**: "She kept her hair over her cheeks the entire first appointment."
> - **On screen**: "Hair over her cheeks. The whole appointment."
> - **Opening shot**: your hands tucking a client's hair back with a clip
> - **Then**: "Last week she asked me to take her photo."

## The 15 hook categories

| Category | Use it when | Example |
| --- | --- | --- |
| **Transformation** | You're sharing a journey: where you started, where you are, what moved you. | "Two years ago I baked from my apartment kitchen. Today we sell out by 10 a.m." |
| **Mistake** | A failure, a wrong call or an expensive lesson. | "I saved $90 on flour and threw away 60 loaves." |
| **Turning Point** | Something changed your thinking, your business or your approach. | "I almost closed the studio in March. Then one client sent a voice note." |
| **Behind-the-Scenes** | You're showing the work, decisions and details people never see. | "This bouquet took four minutes to sell and three days to make." |
| **Contrarian** | Your experience goes against the usual advice in your field. | "Every gym I worked at sold 6-day plans. I cap my clients at three." |
| **Relatable** | You want to connect through a struggle your audience knows too well. | "Ever rebooked the same no-show three times and still felt bad charging her?" |
| **Client/Customer** | A real moment, result or lesson from working with someone. | "He'd been married 12 years and had never bought her flowers." |
| **Curiosity** | You want to open a loop that makes people need the next line. | "There's one question I ask every client before I touch their skin." |
| **Lesson** | You're turning experience into one piece of useful advice. | "After 19 years of facials, here's what I know for sure about sunscreen." |
| **Decision** | A hard choice, a risk, or the moment you chose differently. | "I turned down a $4,000 wedding order for one reason." |
| **Myth-buster** | You're correcting a belief people in your niche get wrong. | "Your sourdough isn't sour because of the starter. It's the clock." |
| **Number/List** | Your story packs into a count or a timeframe. | "3 things I ask every first-time client before we book." |
| **Question** | You want your audience to answer, especially in written posts. | "Would you pay $14 for a loaf that took two days to make?" |
| **Origin** | You're telling why you started, or why you do it your way. | "I opened a flower shop because of a funeral bouquet I couldn't stand." |
| **Credibility** | Your experience, volume or milestones are the hook. | "1,200 weddings later, here's the bouquet question nobody asks." |

Each category has 9 fill-in-the-blank templates in [`hooks.en.md`](hooks.en.md). The skill uses them as starting points and rewrites them around your story, so you never get a hook with a blank left in it.

## Install

**Claude Code (plugin):**

```bash
claude plugin marketplace add ferdelamad/skills
claude plugin install ferdelamad-skills@ferdelamad
```

**Claude Code (manual):** copy this folder into `~/.claude/skills/` (all projects) or `.claude/skills/` (one project).

**Claude app and other apps that support Agent Skills:** zip this folder so `storytelling-hooks/` is at the root of the zip, then upload it in the app's skills settings. The skill uses only plain instructions and markdown files, so it doesn't need Claude Code.

## Try it

> Write me a hook for a reel about our sourdough.

> I need a first line for a LinkedIn post about the client I almost turned away.

> Give me contrarian hooks about meal prep.

## Files

- [`SKILL.md`](SKILL.md): the workflow the agent follows.
- [`hooks.en.md`](hooks.en.md): the hook library, 15 categories with 9 templates each.

Other languages: if you write in Spanish (or any language), the skill writes natural hooks in that language. A native Spanish library (`hooks.es.md`) can be added alongside the English one.
