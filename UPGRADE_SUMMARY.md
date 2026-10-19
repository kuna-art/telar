---
layout: default
title: Upgrade Summary
---

## Upgrade Summary
- **From:** 1.7.0
- **To:** 1.8.2
- **Date:** 2026-10-19
- **Automated changes:** 181
- **Manual steps:** 7

## Automated Changes Applied

### Configuration (11 files)

- [x] Updated requirements.txt
- [x] Updated package.json
- [x] Updated package-lock.json
- [x] Updated _data/glossary_kinds.yml
- [x] Updated _data/languages/en.yml
- [x] Updated _data/languages/es.yml
- [x] Added tests/, pytest.ini, vitest.config.js, telar-content/texts/ to `exclude:` in _config.yml, so Jekyll does not publish them as pages of your site
- [x] Updated package.json
- [x] Updated package-lock.json
- [x] Updated package.json
- [x] Updated package-lock.json

### Layouts (10 files)

- [x] Updated _layouts/default.html
- [x] Updated _layouts/glossary-index.html
- [x] Updated _layouts/glossary.html
- [x] Updated _layouts/object.html
- [x] Updated _layouts/objects-index.html
- [x] Updated _layouts/story.html
- [x] Updated _layouts/index.html
- [x] Updated _layouts/object.html
- [x] Updated _layouts/objects-index.html
- [x] Updated _layouts/story.html

### Includes (21 files)

- [x] Updated _includes/footer.html
- [x] Updated _includes/katex.html
- [x] Updated _includes/katex-loader.html
- [x] Updated _includes/panels.html
- [x] Updated _includes/share-panel.html
- [x] Updated _includes/story-step.html
- [x] Updated _includes/story-steps.html
- [x] Updated _includes/glossary-intro.html
- [x] Updated _includes/glossary-kind-entries.html
- [x] Updated _includes/glossary-kind-text.html
- [x] Updated _includes/glossary-kinds-used.html
- [x] Updated _includes/glossary-kinds.html
- [x] Updated _includes/widgets/glossary.html
- [x] Updated _includes/objects/metadata/audio.html
- [x] Updated _includes/objects/metadata/image.html
- [x] Updated _includes/objects/metadata/video.html
- [x] Updated _includes/objects/tools/audio.html
- [x] Updated _includes/objects/tools/image.html
- [x] Updated _includes/objects/tools/video.html
- [x] Updated _includes/story-step.html
- [x] Updated _includes/iiif-url-warning.html

### Styles (13 files)

- [x] Updated _sass/_coordinate-panel.scss
- [x] Updated _sass/_embed.scss
- [x] Updated _sass/_latex.scss
- [x] Updated _sass/_layout.scss
- [x] Updated _sass/_mixins.scss
- [x] Updated _sass/_panels.scss
- [x] Updated _sass/_responsive.scss
- [x] Updated _sass/_share.scss
- [x] Updated _sass/_story.scss
- [x] Updated _sass/_typography.scss
- [x] Updated _sass/_viewer.scss
- [x] Updated _sass/_widgets.scss
- [x] Updated assets/css/telar.scss

### Scripts (111 files)

- [x] Updated assets/js/README.md
- [x] Updated assets/js/home-page.js
- [x] Updated assets/js/iiif-url-warning.js
- [x] Updated assets/js/katex-loader.js
- [x] Updated assets/js/object-theme.js
- [x] Updated assets/js/story-unlock.js
- [x] Updated assets/js/telar.js
- [x] Updated assets/js/object-audio.js
- [x] Updated assets/js/object-audio.js.map
- [x] Updated assets/js/object-image.js
- [x] Updated assets/js/object-image.js.map
- [x] Updated assets/js/object-video.js
- [x] Updated assets/js/object-video.js.map
- [x] Updated assets/js/object-page/audio-entry.js
- [x] Updated assets/js/object-page/audio-object.js
- [x] Updated assets/js/object-page/boot.js
- [x] Updated assets/js/object-page/clip-panel.js
- [x] Updated assets/js/object-page/image-entry.js
- [x] Updated assets/js/object-page/image-object.js
- [x] Updated assets/js/object-page/video-entry.js
- [x] Updated assets/js/objects-filter.js
- [x] Updated assets/js/objects-filter.js.map
- [x] Updated assets/js/objects-filter/escape.js
- [x] Updated assets/js/objects-filter/main.js
- [x] Updated assets/js/objects-index-page.js
- [x] Updated assets/js/share-panel.js
- [x] Updated assets/js/share-panel.js.map
- [x] Updated assets/js/share-panel/main.js
- [x] Updated assets/js/embed.js
- [x] Updated assets/js/telar-story.js
- [x] Updated assets/js/telar-story.js.map
- [x] Updated assets/js/telar-story/audio-card.js
- [x] Updated assets/js/telar-story/audio-layout.js
- [x] Updated assets/js/telar-story/authoring-frame.js
- [x] Updated assets/js/telar-story/camera-move.js
- [x] Updated assets/js/telar-story/camera-travel.js
- [x] Updated assets/js/telar-story/card-fit.js
- [x] Updated assets/js/telar-story/card-height.js
- [x] Updated assets/js/telar-story/card-pool.js
- [x] Updated assets/js/telar-story/deep-link.js
- [x] Updated assets/js/telar-story/iiif-card.js
- [x] Updated assets/js/telar-story/ios-device.js
- [x] Updated assets/js/telar-story/iiif-manifest.js
- [x] Updated assets/js/telar-story/iiif-viewer.js
- [x] Updated assets/js/telar-story/layout-mode.js
- [x] Updated assets/js/telar-story/main.js
- [x] Updated assets/js/telar-story/media-arrangement.js
- [x] Updated assets/js/telar-story/move-plan.js
- [x] Updated assets/js/telar-story/navigation.js
- [x] Updated assets/js/telar-story/panels.js
- [x] Updated assets/js/telar-story/scroll-engine.js
- [x] Updated assets/js/telar-story/state.js
- [x] Updated assets/js/telar-story/story-input.js
- [x] Updated assets/js/telar-story/utils.js
- [x] Updated assets/js/telar-story/video-card.js
- [x] Updated assets/js/telar-story/video-layout.js
- [x] Updated assets/js/telar-story/viewer.js
- [x] Updated assets/js/telar-story/plates/audio-plate.js
- [x] Updated assets/js/telar-story/plates/base-plate.js
- [x] Updated assets/js/telar-story/plates/framing.js
- [x] Updated assets/js/telar-story/plates/iiif-plate.js
- [x] Updated assets/js/telar-story/plates/media-plate.js
- [x] Updated assets/js/telar-story/plates/video-plate.js
- [x] Updated scripts/dev-only-files.txt
- [x] Updated scripts/encrypt_protected_stories.py
- [x] Updated scripts/fetch_demo_content.py
- [x] Updated scripts/generate_collections.py
- [x] Updated scripts/generate_iiif.py
- [x] Updated scripts/iiif_utils.py
- [x] Updated scripts/process_pdf.py
- [x] Updated scripts/telar/__init__.py
- [x] Updated scripts/telar/answer_budget.py
- [x] Updated scripts/telar/config.py
- [x] Updated scripts/telar/core.py
- [x] Updated scripts/telar/csv_utils.py
- [x] Updated scripts/telar/demo.py
- [x] Updated scripts/telar/dev_only_files.py
- [x] Updated scripts/telar/encryption.py
- [x] Updated scripts/telar/frontmatter.py
- [x] Updated scripts/telar/glossary.py
- [x] Updated scripts/telar/glossary_kinds.py
- [x] Updated scripts/telar/glossary_pages.py
- [x] Updated scripts/telar/images.py
- [x] Updated scripts/telar/latex.py
- [x] Updated scripts/telar/markdown.py
- [x] Updated scripts/telar/pages.py
- [x] Updated scripts/telar/story_pages.py
- [x] Updated scripts/telar/theme_colours.py
- [x] Updated scripts/telar/widgets.py
- [x] Updated scripts/telar/processors/project.py
- [x] Updated scripts/telar/processors/stories.py
- [x] Updated scripts/telar/processors/objects/featured.py
- [x] Updated scripts/telar/processors/objects/frame.py
- [x] Updated scripts/telar/processors/objects/local.py
- [x] Removed assets/js/object-page.js — superseded by the files installed with this upgrade
- [x] Removed assets/js/object-page.js.map — superseded by the files installed with this upgrade
- [x] Removed assets/js/object-page/main.js — superseded by the files installed with this upgrade
- [x] Updated assets/js/telar-story.js
- [x] Updated assets/js/telar-story.js.map
- [x] Updated assets/js/telar-story/deep-link.js
- [x] Updated assets/js/telar-story/iiif-card.js
- [x] Updated assets/js/telar-story/scroll-engine.js
- [x] Updated scripts/telar/config.py
- [x] Updated scripts/telar/glossary.py
- [x] Updated scripts/telar/core.py
- [x] Updated scripts/telar/demo.py
- [x] Updated scripts/telar/processors/objects/remote.py
- [x] Updated scripts/dev-only-files.txt
- [x] Updated scripts/telar/dev_only_files.py
- [x] Removed scripts/migrations/ — this site runs the upgrade launcher, which downloads a verified copy of the migrations each time it runs.
- [x] Removed scripts/telar_upgrade.py: the upgrade runs from the verified tooling `scripts/upgrade.py` downloads

### Documentation (8 files)

- [x] Updated README.md
- [x] Updated CHANGELOG.md
- [x] Updated index.md: its default content now comes from `{{ lang.index_page.welcome | default: site.data.languages.en.index_page.welcome | markdownify }}`
- [x] Updated pages/glossary.md: its default content now comes from `{% include glossary-intro.html lang=lang %}`
- [x] Updated README.md
- [x] Updated CHANGELOG.md
- [x] Updated README.md
- [x] Updated CHANGELOG.md

### Other (7 files)

- [x] Removed migration.json, the manifest of the 1.5.4 upgrade, which Jekyll published as a page of your site
- [x] No spreadsheet has two columns that mean the same thing
- [x] No page source sets a layout or address of its own
- [x] No glossary entry needed its `related_terms` rewritten
- [x] No story answer is cut or loses content in the build
- [x] telar-content/spreadsheets/glossary.csv: the Telar entry now has only your site's language
- [x] telar-content/spreadsheets/glossary.csv: the instruction rows now name telar-content/texts/glossary/

## Manual Steps Required

Please complete these steps:

1. **Update `.github/workflows/build.yml` by hand (recommended).** GitHub does not let an automated upgrade change workflow files, so you need to do this yourself. Open the current `build.yml` in the Telar repository on GitHub, choose "Copy raw contents", paste it over your copy, and commit. The new workflow checks that the saved copy of your object images still exists before it decides not to rebuild them. GitHub deletes that copy after seven days without use, so until now a site that went quiet for a week could publish a text edit with every image missing, on a run that reported success. It also builds with Node 22, and installs only the tools a build needs. ([guide](https://telar.org/docs/setup/upgrading/))
2. **Update `.github/workflows/upgrade.yml` (optional).** Your current copy keeps working. The new one reads your site's version the same way the upgrade does, so the upgrade issue and the summary always name the same starting version. ([guide](https://telar.org/docs/setup/upgrading/))
3. **`.github/workflows/telar-tests.yml` runs Telar's own tests, not your site's (optional).** You can copy the current version from the Telar repository, or delete it together with `tests/`, `pytest.ini` and `vitest.config.js`: nothing your site builds or publishes uses them. ([guide](https://telar.org/docs/setup/upgrading/))
4. **If you keep your stories in a spreadsheet, check the column that marks a story private.** Telar accepted `privada` and `protegida` but not `privado` or `protegido`, and a story marked with one of the two it did not accept was published unencrypted, with no warning, because the build never recognized it as protected. All four spellings work from this release on. If your sheet used either masculine form, treat those stories as having been public until now and decide what to do about it: the next build will encrypt them, but it cannot undo what was already published. ([guide](https://telar.org/docs/site-features/private-stories/))
5. **What changed for your content.** Each step's answer now has to fit its text card: up to 18 lines and five paragraphs, roughly 150 words in a single paragraph. The build cuts a longer answer, and removes widgets, images, tables, code and footnotes from answers; the upgrade summary lists the answers it will shorten, so you can move that text into a layer panel. A `zoom` below 1 now zooms out, so a step that uses one shows more of the object than before. Spreadsheet cells are read as you typed them: `NA`, `N/A`, `null` and `None` are text, and `007` and `7` are different object IDs. Glossary entries can now take a kind in an optional `kind` column, and the `:::glossary` widget places an entry beside the text as a callout. SVG, HEIC, GIF and BMP images can be objects. ([guide](https://telar.org/docs))
6. **No action needed.** v1.8.1 fixes story navigation and two details of the demo content, and no longer reports some valid IIIF manifests as invalid. The upgrade installs the Telar files that changed; your site's content and settings are left as they are. ([guide](https://telar.org/docs/setup/upgrading/))
7. **Delete `.github/workflows/telar-tests.yml` (optional).** It runs Telar's own tests, and only in Telar's repositories, so on your site it reports a skipped check and nothing else. GitHub does not let an automated upgrade change workflow files, so this one is yours to delete. The test files themselves can stay: nothing your site builds or publishes uses them. ([guide](https://telar.org/docs/setup/upgrading/))

## Resources

- [Full Documentation](https://telar.org/docs)
- [CHANGELOG](https://github.com/UCSB-AMPLab/telar/blob/main/CHANGELOG.md)
- [Report Issues](https://github.com/UCSB-AMPLab/telar/issues)
