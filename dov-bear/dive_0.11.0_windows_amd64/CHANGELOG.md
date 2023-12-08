# Changelog

## [v0.11.0](https://github.com/wagoodman/dive/tree/v0.11.0) (2023-07-07)

[Full Changelog](https://github.com/wagoodman/dive/compare/v0.10.0...v0.11.0)

### Added Features

- Allow for autodetecting both `.yaml` and `.yml` config files [[PR #401](https://github.com/wagoodman/dive/pull/401)] [[dosisod](https://github.com/dosisod)]
- Allow for vertical and horizontal scrolling on all views [[Issue #181](https://github.com/wagoodman/dive/issues/181)] [[PR #399](https://github.com/wagoodman/dive/pull/399)] [[mark2185](https://github.com/mark2185)]
- Support Ctrl-Z for job control. [[Issue #297](https://github.com/wagoodman/dive/issues/297)] [[PR #447](https://github.com/wagoodman/dive/pull/447)] [[yurenchen000](https://github.com/yurenchen000)]
- Quit on `q` [[Issue #352](https://github.com/wagoodman/dive/issues/352)] [[PR #354](https://github.com/wagoodman/dive/pull/354)] [[abitrolly](https://github.com/abitrolly)]
- dive with podman on MacOS [[Issue #368](https://github.com/wagoodman/dive/issues/368)] [[PR #390](https://github.com/wagoodman/dive/pull/390)] [[michaelherold](https://github.com/michaelherold)]
- Add more details to "Image Details" section [[Issue #369](https://github.com/wagoodman/dive/issues/369)] [[PR #399](https://github.com/wagoodman/dive/pull/399)] [[mark2185](https://github.com/mark2185)]
- Viewing command Details [[Issue #381](https://github.com/wagoodman/dive/issues/381)] [[PR #399](https://github.com/wagoodman/dive/pull/399)] [[mark2185](https://github.com/mark2185)]

### Bug Fixes

- Fix stream podman command hanging [[PR #349](https://github.com/wagoodman/dive/pull/349)] [[hedrox](https://github.com/hedrox)]
- Fix rendering for multi-line commands [[PR #443](https://github.com/wagoodman/dive/pull/443)] [[lutzky](https://github.com/lutzky)]
- Layers selection area pushes other UI elements offscreen [[Issue #285](https://github.com/wagoodman/dive/issues/285)] [[PR #399](https://github.com/wagoodman/dive/pull/399)] [[mark2185](https://github.com/mark2185)]
- How to see all layers? [[Issue #328](https://github.com/wagoodman/dive/issues/328)] [[PR #399](https://github.com/wagoodman/dive/pull/399)] [[mark2185](https://github.com/mark2185)]
- UI - 'Command' details are truncated! [[Issue #376](https://github.com/wagoodman/dive/issues/376)] [[PR #399](https://github.com/wagoodman/dive/pull/399)] [[mark2185](https://github.com/mark2185)]
- Dive is crashing when browsing layers of paketobuildpacks/run:base-cnb image [[Issue #396](https://github.com/wagoodman/dive/issues/396)] [[PR #395](https://github.com/wagoodman/dive/pull/395)] [[lightsnowball](https://github.com/lightsnowball)]

### Additional Changes

- improve README with new docker run command [[PR #344](https://github.com/wagoodman/dive/pull/344)] [[ozbillwang](https://github.com/ozbillwang)]
- Add Nix/NixOS package installation instructions [[PR #348](https://github.com/wagoodman/dive/pull/348)] [[alexandregv](https://github.com/alexandregv)]
- Correct installation instruction for Ubuntu/Debian [[PR #400](https://github.com/wagoodman/dive/pull/400)] [[iwataka](https://github.com/iwataka)]
- ubuntu install latest version script [[PR #403](https://github.com/wagoodman/dive/pull/403)] [[orihomie](https://github.com/orihomie)]
- feat: add support for alternative ordering strategies [[PR #424](https://github.com/wagoodman/dive/pull/424)] [[iiian](https://github.com/iiian)]
- Update README.md about installation on Arch Linux [[PR #428](https://github.com/wagoodman/dive/pull/428)] [[orhun](https://github.com/orhun)]
- Updated the deprecated ioutil dependency [[PR #429](https://github.com/wagoodman/dive/pull/429)] [[zachary-walters](https://github.com/zachary-walters)]
- Bump module versions to resolve vulnerabilities [[PR #455](https://github.com/wagoodman/dive/pull/455)] [[luhring](https://github.com/luhring)]
- Fix CI [[PR #457](https://github.com/wagoodman/dive/pull/457)] [[abitrolly](https://github.com/abitrolly)]
- Update the link for the Arch Linux package [[PR #459](https://github.com/wagoodman/dive/pull/459)] [[orhun](https://github.com/orhun)]


