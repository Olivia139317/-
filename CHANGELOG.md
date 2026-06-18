# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased]

### Added

- Added second-round polished submission answers in `比赛资料/提交信息二轮润色版.md`.
- Added root `index.html` entry for static site deployment.
- Added sanitized static publish package under `发布包/`.
- Added Vercel demo URL to project context.
- Added portfolio outline in `比赛资料/作品集框架.md`.
- Added first draft portfolio write-up in `比赛资料/别再收藏了-作品说明书.md`.
- Added stable screenshot-mode URLs in the demo via `step`, `scene`, `saved`, and `capture` query parameters.
- Added `比赛资料/作品集截图清单.md` with recommended portfolio screenshot links and captions.

### Changed

- Reworked the demo into a stronger v2 prototype with a more realistic Douyin-style feed, status bar, top tabs, interaction rail, and in-feed AI action card.
- Changed the AI card behavior from a modal-like overlay into a feed-native card that slides up as if it was just swiped into view.
- Strengthened the saved-content pain point with a clearer "collected but not started" insight.
- Simplified the right-side explanation panel so the phone experience carries the concept.
- Slowed the automatic demo timing so each key state is readable during judging or screen recording.
- Synchronized `原型Demo/index.html`, `发布包/index.html`, and root `index.html` so local preview and deployment use the same version.
- Improved the demo workflow for portfolio production by making key states directly addressable through URLs.

## [0.1.0] - 2026-06-18

### Added

- Initialized project Git repository.
- Added `.gitignore` to exclude `node_modules/`.
- Created project context in `AGENTS.md`.
- Added competition materials and submission draft under `比赛资料/`.
- Added first clickable static prototype under `原型Demo/`.
