# Awesome-Automated-Visual-Regression-Testing

# Awesome-Automated-Visual-Regression-Testing

# Top Automated Visual Regression Testing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Pixel-Perfect UI Validation, Visual Diffing & Cross-Browser Screenshot Comparison*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Automated Visual Regression Testing**. These tools capture screenshots of web and mobile interfaces, compare them against approved baselines, and surface visual differences—catching layout shifts, styling regressions, and component inconsistencies before they reach production.

**Examples** include BrowserStack Visual Regression Testing, Applitools Eyes, Chromatic, Percy, Sauce Labs Visual Testing, LambdaTest SmartUI, Argos CI, reg-suit, Happo.io, and Visual Regression Tracker (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted visual testing infrastructure, local screenshot comparison libraries, and CI-native visual diffing—ideal for frontend teams, design system maintainers, QA engineers, and developers building transparent, vendor-neutral visual quality gates.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[BrowserStack Visual Regression Testing (Percy)](https://percy.io/)**  
  Cloud visual testing integrated with BrowserStack, capturing DOM snapshots and rendering across browsers with AI-powered diff noise reduction and scheduled Visual Scanner monitoring for large URL sets [citation:1][citation:4].

- **[Applitools Eyes](https://applitools.com/)**  
  Visual AI platform with deterministic matching engines (Strict, Layout, Content), native Figma baseline mapping, and MCP tools for AI coding agents to inspect pixel-exact diffs directly in IDE workflows [citation:2].

- **[Chromatic](https://www.chromatic.com/)**  
  Visual testing for Storybook and Vitest Browser Mode, uploading test snapshots to a consistent cloud environment for parallel capture, flake reduction, and team-wide diff review directly in pull requests [citation:3][citation:13].

- **[Sauce Labs Visual Testing](https://docs.saucelabs.com/visual-testing/)**  
  Automated visual comparison across browsers, devices, and OSes with side-by-side DOM diff inspection, baseline matching by test metadata, and Figma design export integration for design-to-code validation [citation:5][citation:15].

- **[LambdaTest SmartUI](https://www.lambdatest.com/support/docs/smartui-baseline-management/)**  
  Visual regression platform with flexible baseline management (project, branch, dynamic, build-based), CLI-driven baseline marking, and Git-integrated baseline strategies for feature/hotfix/release workflows [citation:6].

- **[Argos CI](https://argos-ci.com/)**  
  Visual testing service focused on modern JavaScript toolchains, providing Vitest Browser Mode integration with cloud-based screenshot comparison and review workflows to address local baseline limitations [citation:7].

- **[Happo.io](https://happo.io/)**  
  Visual regression and accessibility testing combined in a single review, catching layout shifts, contrast violations, and animation changes with keyboard-friendly approve/reject workflows and GitHub integration [citation:9].

## Open-Source GitHub Projects

- **[Visual Regression Tracker](https://github.com/visual-regression-tracker/visual-regression-tracker)**  
  Open-source, self-hosted visual testing platform with Docker deployment, baseline history tracking, ignore regions, and support for multiple comparison providers including Pixelmatch, Looks-Same, Odiff, and VLM-based human-noticeability analysis [citation:10].

- **[reg-suit](https://github.com/reg-viz/reg-suit)**  
  TypeScript-based visual regression testing workflow tool that stores baselines in cloud storage (S3, GCS), integrates with CI pipelines, and provides GitHub App support for automated diff reporting [citation:8].

- **[Happo (Open-Source Core)](https://github.com/Galooshi/happo)**  
  The original open-source visual diffing library for user interfaces in CI, serving as the foundation for the hosted Happo.io service [citation:11].

- **[AyeSpy](https://github.com/newsuk/AyeSpy)**  
  Performant visual regression testing tool from News UK, designed for CI integration with configurable comparison thresholds.

- **[nightwatch-vrt](https://github.com/Crunch-io/nightwatch-vrt)**  
  Visual regression testing extension for the Nightwatch.js test framework, enabling screenshot comparison within existing Nightwatch test suites [citation:11].

- **[jest-puppe-shots](https://github.com/macku/jest-puppe-shots)**  
  Jest plugin for capturing screenshots of React components with Puppeteer, enabling component-level visual assertions in unit test workflows [citation:11].

- **[ChromeDiff](https://github.com/katat/ChromeDiff)**  
  Node.js visual regression library using headless Chrome and Resemble.js for image comparison, suitable for lightweight custom pipelines [citation:11].

### Additional Strong Open-Source Options

- **[Pixelmatch](https://github.com/mapbox/pixelmatch)** — Lightweight pixel-level image comparison library used as the default comparator in many visual testing tools.
- **[Resemble.js](https://github.com/rsmbl/Resemble.js)** — Image analysis and comparison library with anti-aliasing tolerance and ignore-region support.
- **[Odiff](https://github.com/dmtrKovalenko/odiff)** — High-performance pixel diffing engine with layout detection and anti-aliasing handling.
- **[Loki](https://github.com/oblador/loki)** — Storybook visual regression testing with Docker-based environment consistency.
- **[Vitest Visual Testing (Built-in)](https://vitest.dev/)** — Native `toMatchScreenshot` API in Vitest Browser Mode for local visual assertions, with Playwright provider support and screenshot masking options [citation:7].
- **[BackstopJS](https://github.com/garris/BackstopJS)** — Node.js visual regression tool with Playwright/Puppeteer engines, CSS selector targeting, and HTML reporting.
- **[Wraith](https://github.com/BBC-News/wraith)** — BBC's Ruby-based screenshot comparison tool using headless browsers and ImageMagick.

**Frameworks for building custom systems**: Combine **Visual Regression Tracker** for self-hosted result management, **Playwright** or **Vitest Browser Mode** for screenshot capture, **Pixelmatch** or **Odiff** for diffing, and **GitHub Actions** with **Allure** for CI-native visual quality pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Visual testing tools must be configured with appropriate thresholds and ignore regions to avoid false positives from dynamic content, animations, and rendering differences across environments.
- Self-hosted open-source solutions require proper baseline storage, access control, and CI integration to maintain a reliable visual quality gate.

---

**Made for frontend engineers, design system maintainers, QA teams, and platform teams.**  
Let's make visual regression testing more open, automated, and reliable.
