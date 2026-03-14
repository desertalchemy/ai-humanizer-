
# ai-humanizer

A Claude skill that makes AI writing sound like a human wrote it.

## What it does

This skill runs automatically on everything Claude writes. No prompting required. It catches and fixes 20+ patterns that make AI writing obvious: em dashes, rule of three, sycophantic openings, throat-clearing phrases, promotional inflation, synonym cycling, and more.

It also adds what most AI writing lacks: actual personality. Varied rhythm. Opinions. Specificity. The kind of writing that sounds like someone sat down and wrote it, not like it was assembled by a system.

## What it catches

- Em dashes (replaced with periods, commas, colons, or sentence breaks)
- "Great question!" and other sycophantic openings
- "It's worth noting that" and other throat-clearing
- "Pivotal," "crucial," "groundbreaking," "vibrant," and other AI vocabulary
- "It's not just X, it's Y" negative parallelisms
- Groups of three (AI defaults to three because it's statistically safe)
- "Serves as," "stands as," "represents" when "is" works fine
- "From X to Y, from A to B" false ranges
- Boldface overuse
- Emoji decoration
- Generic positive conclusions ("The future looks bright")
- Excessive hedging ("It could potentially possibly be argued")
- Filler phrases ("In order to," "Due to the fact that," "At this point in time")
- And more. Full list is in the SKILL.md.

## How to install

1. Download the **humanizer-public.skill** file from this repo
2. In Claude, go to **Settings > Customize > Skills**
3. Upload the .skill file
4. Done. It runs automatically on everything.

Note: Skills require a paid Claude plan (Pro, Max, Team, or Enterprise).

## How it works

Claude reads the skill instructions and applies them silently before showing you any output. You never have to say "humanize this" or "make this sound human." It just writes better from the start.

If you want to read the full instructions, open SKILL.md.

## Based on

The pattern detection is built from Wikipedia's "Signs of AI writing" guide, maintained by WikiProject AI Cleanup. The patterns come from observations of thousands of instances of AI-generated text.

## License

Free to use, share, and modify. Do whatever you want with it.
