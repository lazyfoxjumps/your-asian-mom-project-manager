# Changelog

Mommy keep track of everything. Don't try to pretend you don't know what changed.

All notable changes to this skill are documented here. Format loosely follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

Things mommy thinking about for next time. No promises ah, depends if you behave.

- Optional Notion push for the saved plan (currently markdown file only)
- A "mini" mode for smaller projects (one-page quick plan, like the natal-chart-reader-mini pattern)
- Voice toggle command so the user can dial mommy up or down mid-conversation without losing the plan
- Project resume mode (load an existing plan file and continue tracking from where you left off)
- More specialized workflows (thesis defense, wedding planning multi-month, startup fundraising round)

## [0.3.1] - 2026-05-23

### Changed
- Rewrote README to cover the full skill scope, including all 7 workflow steps, execution tracking behavior across the conversation, specialized workflow detection, voice mechanics, and safety notes. The previous version glossed over half of what mommy actually does.

## [0.3.0] - 2026-05-23

### Changed
- **Breaking**: Renamed skill from `your-asian-mom-pm` to `my-asian-mom-pm`. Slash command is now `/my-asian-mom-pm`. Update any saved aliases or muscle memory.
- README title updated to "My Asian Mom Project Manager".
- GitHub repo renamed to `my-asian-mom-project-manager` (old URL still redirects).

## [0.2.0] - 2026-05-23

### Changed
- **Breaking**: Renamed skill folder and frontmatter `name` from `Your Asian Mom Project Manager` to `your-asian-mom-pm` so the slash command actually parses. Spaces in skill names break slash-command lookup.

## [0.1.0] - 2026-05-23

### Added
- Initial release of the skill.
- Full project management workflow: intake (5 questions), define, plan (WBS, milestones, dependencies, effort, timeline, definition of done), risk and contingency (pre-mortem included), communication plan, execution tracking.
- Specialized workflow detection for events, launches, travel, content series, hiring, moves/renovations, and creative projects.
- Plan is saved as a `.md` file in the project folder; chat returns a short summary with the file link, not the full plan inline.
- Voice persists for the entire conversation, including follow-ups, until the user explicitly switches it off.
- Voice rules: gender-appropriate nickname after asking, sparing Singlish, no validation, rotating imaginary higher-achiever comparisons, light comedic Asian-mom threats, real PM substance underneath the voice.
- Safety guardrails: threats stay clearly playful, comparisons stay fictional, voice drops immediately on user request.
- README and public GitHub repo at `lazyfoxjumps/my-asian-mom-project-manager`.

---

Mommy version this thing properly because Auntie Lily's daughter, you know the one in tech, she always say "if you don't have a changelog, you don't have a project". So now we have one. Don't make mommy add too many breaking changes lah, I getting tired.
