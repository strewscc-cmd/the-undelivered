# 08 — Interaction and Hint Specification

## Interaction model

The game is an immersive website styled as an investigative application. The player explores locations, opens artifacts, reads and inspects documents, records observations, and connects evidence.

## Core interface elements

- **Location view:** interactive illustration or map with selectable objects.
- **Artifact viewer:** document image/scan with readable text, zoom, highlight, and annotation.
- **Evidence inventory:** lists discovered artifacts and their metadata.
- **Investigator's Journal:** stores observations and evidence-based opinions.
- **Evidence Board:** supports links between people, documents, locations, dates, and theories.
- **Timeline builder:** allows players to sequence events and separate event dates from document dates.
- **Puzzle interface:** focused challenge with clue sources and accessible controls.
- **Hint panel:** offers progressive hints and records hint use for the investigation score.
- **Final Report:** writing area for the 100–150 word report.

## Navigation and language integration

Giving directions is practiced through navigation to the station, locker, archive storage, and other case locations. The directions challenge must use explicit map labels and unambiguous movement instructions.

Expressing opinions is practiced when the player judges whether an artifact is relevant and evaluates theories about the fires. Prompts should ask for a claim and a reason, such as:
- “In my opinion, this document is relevant because…”
- “The evidence suggests that…”
- “I disagree with this theory because…”
- “Although this record supports…, it does not prove…”

## Hint tiers

- Tier 1 — Observation: calls attention to a detail.
- Tier 2 — Connection: suggests a source to compare.
- Tier 3 — Reasoning: clarifies the logical step but does not state the final conclusion.

Hint use may affect the Investigation Score's independence component, but must not reduce the English Proficiency Score simply because a student requested support.

## Evidence model

Every item should store:
- unique ID
- display title
- artifact type
- creator/source
- date written/created
- date processed/received/discovered where applicable
- linked characters, places, and events
- direct observations
- possible inferences
- limitations
- related puzzles
- whether the player has inspected it

## Accessibility and learning design

- All audio must have a transcript or caption.
- Audio must not contain indispensable information unavailable to students with hearing impairments.
- Body text must remain readable when zoomed.
- Do not rely on color alone to communicate evidence status.
- Keyboard navigation and clear focus states should be supported when implementation begins.
- Students should be able to revisit evidence and review prior hints.

## No-code status

This is an interaction specification only. No implementation or gameplay code should be added until content and continuity are approved.
