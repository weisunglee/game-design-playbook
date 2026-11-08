---
name: game-design-playbook
description: Help unblock game development with gameplay ideas, first-five-minute experience reviews, or seasonal update planning. Turn player experience goals into scoped playable experiments.
---

# Game Design Playbook

Help developers identify bottlenecks in the player experience and define a playable next step.

## Response language

Respond in the user's language, following any explicit language preference. Otherwise, use the language of their current request. Apply this to explanations, tables, questions, and deliverables. The English language of these instructions does not determine the response language.

For the source and talk timestamps, see the [README](https://github.com/weisunglee/game-design-playbook#talk-takeaways). The talk uses PoE's seasonal ARPG model as its example. The workflow below adapts its ideas into design methods; it is neither a transcript nor a guarantee of success.

## 1. Identify the bottleneck to test

Extract the genre, target players, core loop, development stage, specific sticking point, team size, and time constraints from the available context. When information is missing, state provisional assumptions and continue. Ask only for information that would materially change the recommendation.

Describe the bottleneck as one player situation, such as: "On their second expedition, players make the same choices and have little reason to look forward to another run." Identify whether the issue involves repetitive play, unclear goals, weak feedback, a slow opening, excessive scope, or difficulty communicating value. Distinguish evidence supplied by the user from inference.

Completion criterion: one concrete player problem, one hypothesis to test, and an explicit resource limit.

## 2. Propose three distinct experience directions

For each direction, describe the player fantasy, repeated actions and choices, a playable difference within five minutes, the purpose of rewards, a short-term goal, and an endpoint.

Make the directions change different decisions or behaviors rather than only their story framing. Prefer combinations of existing assets and rules. Expand scope only when the added content addresses the identified problem.

Compare player experience, new assets, technical dependencies, production cost, and the largest unknown in a table. Estimate cost using relative categories or explicit assumptions. Recommend the direction that best fits the constraints, explaining the reasoning and tradeoffs.

Completion criterion: three distinguishable directions and a recommendation that addresses the hypothesis from step 1.

## 3. Check whether the design forms a complete experience

Mark each item as "designed," "gap," or "not applicable," with a reason:

| Check | Questions to answer |
| --- | --- |
| Fresh start | How do new or returning players enter? Consider progression resets only where a seasonal economy fits the game; explain what is retained and transferred. |
| New mechanic | How is it playable within five minutes? How does it keep varying throughout the experience rather than appearing once? |
| Theme and motivation | Who are players acting for, and why? How do story, characters, and presentation support play? Evaluate voice acting against available resources. |
| Distinct rewards | What choices do rewards unlock? Do they only increase numbers? Do they remove the reason to play older content? |
| Actions and strategy | Which repeated actions or build decisions change? |
| Long-term goal | What visible progression track can players pursue? A prototype needs to validate only its shortest meaningful segment. |
| Completion | What challenge or outcome marks the end of this run? Depending on the genre, use a boss, puzzle, creation, or exploration milestone. |

For an existing audience, assess how changes affect mastery, control habits, and prior investment. Where useful, propose a reversible prototype or a comparison with a separate mode.

For single-player games or early prototypes, preserve the relevant design purposes. Add seasons, builds, or economy systems only when they serve the project.

Completion criterion: every item has a conclusion, and the prototype will test the largest experience gap.

## 4. Write a testable demonstration, then scope the prototype

Explain in one sentence what players will do and why it is worth anticipating. Then outline a short demonstration: lead with the most interesting actual interaction, and follow the player's journey through choices, consequences, and the next goal.

Treat promotional wording as an experience promise to test. If it relies on vague phrases such as "rich content," make the gameplay more concrete. Preserve work on stability, readability, accessibility, and essential onboarding even when it is not a promotional highlight.

List the minimal prototype's scenes, interactions, feedback, reusable or placeholder assets, and explicitly deferred features. Describe the first five minutes so the core difference is playable. Implement only when code changes are within the user's authorization; a planning request calls for a plan.

Completion criterion: the prototype tests the main hypothesis and contains a complete loop from entry to outcome within the resource limit.

## 5. Use playtesting to choose the next step

Define observations and decision criteria before proposing a playtest milestone with an actual audience. Use a relative schedule when dates are unknown. Publish, invite people, or send messages only within the user's actual authorization.

Specify at least three observable signals, such as time to understand the core choice, voluntarily trying another strategy, or being able to name the next goal. Propose explicitly provisional success thresholds for this prototype, rather than presenting them as universal industry standards.

State which results support continuing, which call for revision, and which suggest reducing scope or stopping this direction. Until playtesting happens, label it as a plan and keep claims of validated enjoyment pending.

When planning an existing game's announcement, optionally propose a teaser, gameplay demonstration, rehearsal, and Q&A. Adapt timing and spoiler boundaries to the audience. For seasonal games, observe return visits and satisfied departures; select appropriate goals for other genres.

## Deliverable format

1. Bottleneck and hypothesis: distinguish known facts, inferences, and constraints.
2. A comparison of three directions and one recommendation.
3. An experience check covering gaps and reasons for items marked not applicable.
4. A one-sentence experience promise, a first-five-minute flow, a minimal prototype, and a deferred-feature list.
5. Playtest observations, provisional thresholds, an external milestone, and criteria to continue, revise, or stop.

Distinguish the speaker's views from project-specific adaptations. On completion, the developer should know which playable segment to build next and which question it will answer.
