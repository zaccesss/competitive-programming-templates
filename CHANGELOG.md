# Changelog

All notable changes to this project are documented here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

---

## [Unreleased]

### Fixed

- The README stack icons load from the icon project's own repository at a fixed commit. The old host refuses every request.

## [0.1.0] - 2026-11-03

### Added

- A release badge.

### Changed

- Community files follow the [AI policy](https://github.com/zaccesss/ai-policy): pull requests declare AI use and issue forms ask whether AI helped. Security reports go to security@isaacadjei.me.
- The contact address in the README, `SUPPORT.md` and the issue template config is contact@isaacadjei.me.
- Routine tidy-up.

## [0.0.1] - 2026-10-22

### Added

- `CODEOWNERS`, `CODE_OF_CONDUCT.md`, `SECURITY.md` and `SUPPORT.md`, matching the rest of the fleet
- `.markdownlint.json` and a markdownlint CI workflow, with its own `.github/workflows/README.md`
- YAML issue forms for bug reports and enhancements plus a pull request template
- This changelog
- `.github/ISSUE_TEMPLATE/config.yml` disabling the blank issue option, pointing to the security policy and code@isaacadjei.me instead

### Changed

- The README's Contact and Support section now links out to `SUPPORT.md` and `SECURITY.md` as callouts instead of plain prose
- The top badge row and footer now use flat Markdown Lint and licence shields instead of the old chunky Portfolio/LinkedIn/Email badges, matching the rest of the fleet
