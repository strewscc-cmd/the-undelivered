# THE UNDELIVERED

*A literary mystery about missing letters, a mayor's death, and three fires separated by twenty-eight years.*

## Project overview

**THE UNDELIVERED** is an immersive, website-styled mystery investigation designed for Advanced English learners around CEFR B2. Set in the fictional town of Bellwether, the game asks players to investigate three fires (1998, 2023, and 2026), the death of Mayor Thomas Wren, and the 1998 disappearance of his daughter, Evelyn Wren.

Players inspect letters and official records, compare timelines, navigate locations, evaluate competing theories, and write an evidence-based investigative report.

## Current status

**Phase:** Story and game design.  
**Gameplay code:** Not started.  
**Canon version:** Master Canon v3.0.

The repository is deliberately documentation-first. Do not begin implementation until story continuity, all evidence texts, puzzle solutions, audio scripts, and asset requirements have been reviewed.

## Core canon

- In 1998, a fire in the Bellwether area killed Mayor Thomas Wren. Thomas had opposed a land-development project after finding discrepancies in its documents.
- The fire may have been deliberately set, but the evidence does not definitively establish arson or connect it to Thomas's death.
- Evelyn Wren, Thomas's 19-year-old daughter and a first-year journalism student, investigated the documents and disappeared in October 1998.
- Further fires occurred in nearby areas in 2023 and 2026.
- Ashbourne Land & Development benefited from changes in land status or use, but its involvement in any fire has not been proven.
- Evidence suggests Evelyn may have been targeted to silence her investigation. Her ultimate fate remains unknown.
- A box of undelivered correspondence is discovered during the 2026 investigation.
- **Do not present suspicion as established fact.** Players must distinguish confirmed facts, supported inferences, and unresolved questions.

## Design documents

1. [Game Design](docs/01-game-design.md)
2. [Story Bible / Master Canon](docs/02-story-bible.md)
3. [Master Timeline](docs/03-master-timeline.md)
4. [Master Evidence Matrix](docs/04-master-evidence-matrix.md)
5. [Master Letter Register](docs/05-master-letter-register.md)
6. [Document Register](docs/06-document-register.md)
7. [Puzzle Blueprint](docs/07-puzzle-blueprint.md)
8. [Interaction and Hint Specification](docs/08-interaction-and-hint-specification.md)
9. [Learning Objectives and Assessment](docs/09-learning-objectives-and-assessment.md)
10. [UI/UX and Visual Direction](docs/10-ui-ux-and-visual-direction.md)
11. [Audio and Asset Plan](docs/11-audio-and-asset-plan.md)
12. [Testing and Continuity Checklist](docs/12-testing-and-continuity-checklist.md)

## Repository map

- `docs/` — design specifications and production planning.
- `story/` — characters, timeline, letters, official documents, and ending boundaries.
- `puzzles/` — solutions, progressive hints, and scoring rubric.
- `assets/audio/` — future recorded voice lines and ambient audio.
- `assets/newspaper/` — fictional newspaper clippings.
- `assets/images/` — maps, photographs, evidence props, and visual references.
- `assets/reference/` — reference material and visual direction.
- `planning/` — checklists and production tracking.
- `src/` — reserved for later; no gameplay code until design approval.

## Spoiler and publication note

This is a public repository. Story canon, puzzle answers, and investigation solutions are therefore visible to anyone. If spoiler protection becomes important, move the authoring/answer-key materials to a private repository before publishing player-facing game assets.

## Working principles

1. Maintain a single source of truth for dates, names, reference numbers, and evidence.
2. Every puzzle must be solvable from information available to the player.
3. Every conclusion must be supported by traceable evidence.
4. Preserve uncertainty where the canon leaves questions unresolved.
5. Keep the Investigation Score separate from the English Proficiency Score.
6. Audio recordings and newspaper assets will be prepared only after scripts and requirements are finalized.
