# Game Design Playbook

English | [繁體中文](README.zh-TW.md)

An AI agent skill for finding gameplay ideas, reviewing player experience, and turning development roadblocks into testable design hypotheses.

Use it for early prototypes or updates to an existing game. Seasonal advice is adapted to the project's genre and constraints. The skill instructions are written in Traditional Chinese and direct the agent to respond in the user's language.

## Install

With Node.js/npm and Git installed, run this single command in your terminal (Windows, macOS, or Linux):

```bash
npx skills add weisunglee/game-design-playbook
```

Follow the prompts to choose your agent and installation scope. For a global Codex installation without interactive selection:

```bash
npx skills add weisunglee/game-design-playbook --skill game-design-playbook --agent codex --global --yes
```

For a project installation, run the command from the project root and omit `--global`.

Verify installation and check for updates:

```bash
npx skills list --global
npx skills check
npx skills update
```

`skills update` updates installed skills managed by the CLI. See the [official Skills CLI reference](https://github.com/vercel-labs/skills/blob/main/docs/commands.md) for options.

### Invoke

Restart your agent or open a new session if the skill is not yet visible, then ask:

```text
Use $game-design-playbook.
I'm building a single-player exploration game about gathering resources
and returning home to upgrade. Each expedition feels too similar.
I'm a solo developer and have two days for a prototype.
Suggest three distinct directions, recommend one minimal playable experiment,
and describe the player's first five minutes.
```

The skill produces a bottleneck hypothesis, three design directions, a recommendation, a minimal prototype plan, playtest observations, and criteria for the next decision.

## Source

- [Jonathan Rogers' talk on YouTube](https://www.youtube.com/watch?v=GHEBkhT1K7A)
- The speaker introduces himself as the game director of *Path of Exile 2*.
- These notes were prepared from the video's automatically generated English subtitles. Timestamps help locate relevant passages; names and numbers may contain transcription errors.

This is an unofficial summary and practical adaptation, with no affiliation with or endorsement from the speaker or Grinding Gear Games. The full transcript is not included. The takeaways below paraphrase the speaker's views. The skill's prototype experiments, evaluation tables, and small-team workflow are this project's extensions, rather than quotations or guarantees of success.

## Talk takeaways

### 1. Make an update feel different to play (01:36–15:07)

The speaker presents seven elements of a PoE seasonal release:

| Element | What it gives players |
| --- | --- |
| Reset the economy and character progression | A fresh start and room to explore builds again; old characters remain in the previous environment |
| Introduce a mechanic within five minutes and carry it through the experience | An immediate, recurring sense that this release is different |
| Add a voiced character with a story | Someone to engage with and a reason to act |
| Provide a distinct reward system | A reason to participate, often through new crafting possibilities |
| Enable new builds | A change to the actions players repeat |
| Add a new long-term progression track | A different goal to pursue |
| Include a new pinnacle challenge or boss | A clear sense of having completed the content |

The emphasis is on choosing what to build. An entire new act can take substantial effort while remaining hours away from a returning player's first session. A smaller mechanic that appears early and affects the whole journey can communicate freshness sooner. New acts still matter; they serve a different stage of the experience.

### 2. Balance changes affect players' sense of competence (02:56–04:59)

Players invest in habits and mastery as well as equipment. Changing an existing character can make familiar skills feel unreliable. A seasonal fresh start can reset expectations and provide a better moment for major adjustments. This does not mean every game should erase progress.

### 3. Theme and story change how similar mechanics feel (09:13–10:39)

Fighting waves of enemies can feel different when framed as gambling with a dangerous figure or helping a craftsperson investigate ancient ruins. Characters, motives, presentation, and voice work establish the player fantasy. Full voice acting is the speaker's strong recommendation in his production context; small teams can first test whether the motivation and presentation work.

### 4. Give rewards distinct uses instead of only bigger numbers (10:42–12:09)

Increasing drops each release raises expectations. Unique crafting options and build possibilities can create differences beyond quantity. Moving an older activity's exclusive rewards into new content can remove the reason to play that older activity.

### 5. Try explaining the game before deciding what to build (23:27–26:37)

The game directors write the announcement script to test whether features sound exciting, identify gaps, and reduce scope. Treat this as a design check: can you show what players will do and why it matters? It complements playtesting. Stability, accessibility, and other foundational work still have value even when they are not announcement highlights.

### 6. Marketing shapes the player experience (26:41–37:07)

PoE's approach includes a teaser three weeks before release, a main reveal one week before release, and quality-of-life previews in between. A press presentation roughly three days before the reveal helps expose misunderstandings. The reveal gets straight to gameplay, leads with strong material, explains the player's journey, and uses live Q&A to address concerns honestly.

The timing, preserving creators' first reactions, and limiting spoiler protection mainly to the pinnacle boss fight reflect the speaker's product and audience. Story-driven games and small teams should make their own choices.

### 7. External demonstrations help focus development (37:50–39:08)

Finishing this month creates a different focus from knowing that someone will play it this month. A demonstrable, playable milestone pushes a team to connect the whole experience. A small team can start with a short playtest for trusted friends before considering a public showing.

### 8. Your improvement may feel like a different game to existing players (39:10–41:46)

To move beyond repeated use of a single skill, PoE 2 changed interconnected systems: skills, pacing, dodging, and movement. Developers may see these as better execution of the original vision, while established players experience a change to the fundamentals. Test that impact before choosing an integrated update, a separate mode, or a sequel.

### 9. Let players leave satisfied and look forward to returning (41:48–47:22)

The speaker emphasizes seasonal activity over daily activity alone: players can play for a few weeks, achieve their goals, rest, and return next season. Clear endpoints can help them stop before burnout. Every season must earn their interest again.

This distinction describes the speaker's operating model; it is not a universal industry definition of live service.

## When development feels stuck

Start with: **What difference can players experience within five minutes of opening the game again?**

For an exploration game, try a rule such as “each recovered relic changes the routes available on the next expedition.” Test it on one small map. Observe whether players make different decisions before committing to more maps. This is an example developed for this project.
