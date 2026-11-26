# Changelog

## 1.0.0 (2026-11-26)


### Features

* adapt contacto mode by contact type (recruiter/HM/peer/interviewer) ([40cc702](https://github.com/BaoTNguyen/career-ops/commit/40cc702dd6a087814c48af2da7117054bc9a743a))
* add --min-score flag to batch runner ([#249](https://github.com/BaoTNguyen/career-ops/issues/249)) ([06405bf](https://github.com/BaoTNguyen/career-ops/commit/06405bfe9a914aaab9c429f852e1b130700a9482))
* add {{PHONE}} placeholder to CV template ([#287](https://github.com/BaoTNguyen/career-ops/issues/287)) ([19b4148](https://github.com/BaoTNguyen/career-ops/commit/19b4148c1d8c4a7f8264b75ecfd07616388980b1))
* add Block G — posting legitimacy assessment ([fa8b84e](https://github.com/BaoTNguyen/career-ops/commit/fa8b84e0d58ed8683f2e84a2eabc93becf7dcbf7))
* add follow-up cadence tracker mode ([3217e77](https://github.com/BaoTNguyen/career-ops/commit/3217e77ef83e0aaec50f507d4337c92012c35139))
* add GitHub Actions CI + auto-labeler + welcome bot + /run skill ([d8eda9b](https://github.com/BaoTNguyen/career-ops/commit/d8eda9b90fbdb77bc4f770667ad57fa2e3a0ee39))
* add Nix flake devshell with Playwright support ([a364046](https://github.com/BaoTNguyen/career-ops/commit/a364046f37337477c4e59bf3cede2407f176c16f))
* add OpenCode slash commands for career-ops ([#67](https://github.com/BaoTNguyen/career-ops/issues/67)) ([92137d4](https://github.com/BaoTNguyen/career-ops/commit/92137d4e1fd878d6ed7f53f115aa13ecae254e08))
* add scan.mjs — zero-token portal scanner ([a7cd72c](https://github.com/BaoTNguyen/career-ops/commit/a7cd72c905b8814a4fc6b8d7d2c54e7d14c272a4))
* **dashboard:** add Catppuccin Latte light theme with auto-detection ([67b695b](https://github.com/BaoTNguyen/career-ops/commit/67b695b15ac6ac5eb2230b308f3b92ddc3966f3e))
* **dashboard:** add manual refresh shortcut ([#246](https://github.com/BaoTNguyen/career-ops/issues/246)) ([b448784](https://github.com/BaoTNguyen/career-ops/commit/b4487840d88b9fefe606fe42c7bf843ecb8d7f62))
* **dashboard:** add progress analytics screen ([78997fa](https://github.com/BaoTNguyen/career-ops/commit/78997fad9f31d3962a901dffb7ee2b8ffa4c9218))
* **dashboard:** add vim motions to pipeline screen ([#262](https://github.com/BaoTNguyen/career-ops/issues/262)) ([1e6b1c8](https://github.com/BaoTNguyen/career-ops/commit/1e6b1c8e52689de9ef1f5a794db8df6542537e0a))
* **dashboard:** aligned tables and markdown syntax rendering in viewer ([ff821c3](https://github.com/BaoTNguyen/career-ops/commit/ff821c3424a008b9e17a4cbc6a59e2c233ad5f47))
* expand portals.example.yml with 8 dev-tools companies + 23 search queries ([#140](https://github.com/BaoTNguyen/career-ops/issues/140)) ([ccc4b7f](https://github.com/BaoTNguyen/career-ops/commit/ccc4b7f4c238b80f875796cadced3f02dc8cac9c))
* **i18n:** add Japanese README + language modes for Japan market ([8496c2d](https://github.com/BaoTNguyen/career-ops/commit/8496c2d22871ec596d879256751eb25411229197))


### Bug Fixes

* 10 bug fixes — resource leaks, command injection, Unicode, navigation ([43cdb93](https://github.com/BaoTNguyen/career-ops/commit/43cdb93f0dc24fe034bf5e8f0e79b297769d3790))
* add data/ fallback to UpdateApplicationStatus ([#55](https://github.com/BaoTNguyen/career-ops/issues/55)) ([fcf051e](https://github.com/BaoTNguyen/career-ops/commit/fcf051e3bf4d4b1da924518ded31c7e139be5174))
* add stopword filtering and overlap ratio to roleMatch ([#248](https://github.com/BaoTNguyen/career-ops/issues/248)) ([41233db](https://github.com/BaoTNguyen/career-ops/commit/41233db55ba5e9e8fbc5f9b4c29ae3ebf73a63b7))
* align portals.example.yml indentation for new companies ([f5be20a](https://github.com/BaoTNguyen/career-ops/commit/f5be20a9519bf0f9c4b9cde5419e90e7fadab3fd))
* **ci:** use pull_request_target for labeler on fork PRs ([#260](https://github.com/BaoTNguyen/career-ops/issues/260)) ([1f1bb2a](https://github.com/BaoTNguyen/career-ops/commit/1f1bb2abb3fde2ce8c86e773e987fce44b30ee37))
* correct _shared.md → _profile.md reference in CUSTOMIZATION.md (closes [#137](https://github.com/BaoTNguyen/career-ops/issues/137)) ([2dc5aa7](https://github.com/BaoTNguyen/career-ops/commit/2dc5aa76ffee780435caa1019aa75cf94ecb196f))
* correct dashboard launch path in docs ([#80](https://github.com/BaoTNguyen/career-ops/issues/80)) ([62996d8](https://github.com/BaoTNguyen/career-ops/commit/62996d8cb785072b12d7ac47070f57ae61590609))
* **dashboard:** show dates in pipeline list ([#298](https://github.com/BaoTNguyen/career-ops/issues/298)) ([e291cd0](https://github.com/BaoTNguyen/career-ops/commit/e291cd0933c013168359a01b39b5fd04947b9b52))
* ensure data/ and output/ dirs exist before writing in scripts ([#261](https://github.com/BaoTNguyen/career-ops/issues/261)) ([8768d0b](https://github.com/BaoTNguyen/career-ops/commit/8768d0b6ef651f6ec2cb8e5010bd47bce80ff1ea))
* filter expired WebSearch links before they reach the pipeline ([#57](https://github.com/BaoTNguyen/career-ops/issues/57)) ([83f5072](https://github.com/BaoTNguyen/career-ops/commit/83f5072227a6d3d34053395f84a336b5232ef835))
* improve default PDF readability ([#85](https://github.com/BaoTNguyen/career-ops/issues/85)) ([2c2cdcb](https://github.com/BaoTNguyen/career-ops/commit/2c2cdcbc732269f9b4231cb77cc8d5387a908efb))
* liveness checks ignore nav/footer Apply text, expired signals win ([9bf01e2](https://github.com/BaoTNguyen/career-ops/commit/9bf01e20d44361742b82b76ea3ce4225911b97f6))
* remove wellfound, lever and remotefront from portals.example.yml ([#286](https://github.com/BaoTNguyen/career-ops/issues/286)) ([a100887](https://github.com/BaoTNguyen/career-ops/commit/a1008875ab10b510af23b81211c87c267b1a62e6))
* replace grep -P with POSIX-compatible grep in batch-runner.sh ([e309567](https://github.com/BaoTNguyen/career-ops/commit/e3095678fd0d0f22ac529cf4e5c496e9cd38fd5c))
* test-all.mjs scans only git-tracked files, avoids false positives ([9fc3ba2](https://github.com/BaoTNguyen/career-ops/commit/9fc3ba23e8fcd663f83b0bac62417401c4da7bda))
* use candidate name from profile.yml in PDF filename ([e2754b3](https://github.com/BaoTNguyen/career-ops/commit/e2754b3edc096a57cb3a9ebc8efda87751dbec27))
* use execFileSync to prevent shell injection in test-all.mjs ([354d85f](https://github.com/BaoTNguyen/career-ops/commit/354d85fdbfe522ef329da259ebb3f724030f2c21))
* use fileURLToPath for cross platform compatible paths in tracker scripts ([#32](https://github.com/BaoTNguyen/career-ops/issues/32)) ([#58](https://github.com/BaoTNguyen/career-ops/issues/58)) ([6748504](https://github.com/BaoTNguyen/career-ops/commit/6748504af3a198246012d43e701cbe4fa01493d7))
* use hi@santifer.io in English README ([7ca2004](https://github.com/BaoTNguyen/career-ops/commit/7ca2004c7c3260fb7aeec72a1ff136e884516979))


### Performance Improvements

* compress hero banner from 5.7MB to 671KB ([28de18f](https://github.com/BaoTNguyen/career-ops/commit/28de18f7d96113fa045762ee8273ae8cca76a856))

## [1.5.0](https://github.com/santifer/career-ops/compare/v1.4.0...v1.5.0) (2026-04-14)


### Features

* add --min-score flag to batch runner ([#249](https://github.com/santifer/career-ops/issues/249)) ([cb0c7f7](https://github.com/santifer/career-ops/commit/cb0c7f7d7d3b9f3f1c3dc75ccac0a08d2737c01e))
* add {{PHONE}} placeholder to CV template ([#287](https://github.com/santifer/career-ops/issues/287)) ([e71595f](https://github.com/santifer/career-ops/commit/e71595f8ba134971ecf1cc3c3420d9caf21eed43))
* **dashboard:** add manual refresh shortcut ([#246](https://github.com/santifer/career-ops/issues/246)) ([4b5093a](https://github.com/santifer/career-ops/commit/4b5093a8ef1733c449ec0821f722f996625fcb84))


### Bug Fixes

* add stopword filtering and overlap ratio to roleMatch ([#248](https://github.com/santifer/career-ops/issues/248)) ([4da772d](https://github.com/santifer/career-ops/commit/4da772d3a4996bc9ecbe2d384d1e9d2ed75b9819))
* **dashboard:** show dates in pipeline list ([#298](https://github.com/santifer/career-ops/issues/298)) ([e5e2a6c](https://github.com/santifer/career-ops/commit/e5e2a6cffe9a5b9f3cec862df25410d02ecc9aa4))
* ensure data/ and output/ dirs exist before writing in scripts ([#261](https://github.com/santifer/career-ops/issues/261)) ([4b834f6](https://github.com/santifer/career-ops/commit/4b834f6f7f8f1b647a6bf76e43b017dcbe9cd52f))
* remove wellfound, lever and remotefront from portals.example.yml ([#286](https://github.com/santifer/career-ops/issues/286)) ([ecd013c](https://github.com/santifer/career-ops/commit/ecd013cc6f59e3a1a8ef77d34e7abc15e8075ed3))

## [1.4.0](https://github.com/santifer/career-ops/compare/v1.3.0...v1.4.0) (2026-04-13)


### Features

* add GitHub Actions CI + auto-labeler + welcome bot + /run skill ([2ddf22a](https://github.com/santifer/career-ops/commit/2ddf22a6a2731b38bcaed5786c4855c4ab9fe722))
* **dashboard:** add Catppuccin Latte light theme with auto-detection ([ff686c8](https://github.com/santifer/career-ops/commit/ff686c8af97a7bf93565fe8eeac677f998cc9ece))
* **dashboard:** add progress analytics screen ([623c837](https://github.com/santifer/career-ops/commit/623c837bf3155fd5b7413554240071d40585dd7e))
* **dashboard:** add vim motions to pipeline screen ([#262](https://github.com/santifer/career-ops/issues/262)) ([d149e54](https://github.com/santifer/career-ops/commit/d149e541402db0c88161a71c73899cd1836a1b2d))
* **dashboard:** aligned tables and markdown syntax rendering in viewer ([dbd1d3f](https://github.com/santifer/career-ops/commit/dbd1d3f7177358d0384d6e661d1b0dfc1f60bd4e))


### Bug Fixes

* **ci:** use pull_request_target for labeler on fork PRs ([#260](https://github.com/santifer/career-ops/issues/260)) ([2ecf572](https://github.com/santifer/career-ops/commit/2ecf57206c2eb6e35e2a843d6b8365f7a04c53d6))
* correct _shared.md → _profile.md reference in CUSTOMIZATION.md (closes [#137](https://github.com/santifer/career-ops/issues/137)) ([a91e264](https://github.com/santifer/career-ops/commit/a91e264b6ea047a76d8c033aa564fe01b8f9c1d9))
* replace grep -P with POSIX-compatible grep in batch-runner.sh ([637b39e](https://github.com/santifer/career-ops/commit/637b39e383d1174c8287f42e9534e9e3cdfabb19))
* test-all.mjs scans only git-tracked files, avoids false positives ([47c9f98](https://github.com/santifer/career-ops/commit/47c9f984d8ddc70974f15c99b081667b73f1bb9a))
* use execFileSync to prevent shell injection in test-all.mjs ([c99d5a6](https://github.com/santifer/career-ops/commit/c99d5a6526f923b56c3790b79b0349f402fa00e2))
