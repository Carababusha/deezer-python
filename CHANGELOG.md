# Changelog

<!--next-version-placeholder-->

## v3.1.0 (2021-10-09)
### Feature
* Ability to manage tracks from the user's library ([`59b0f57`](https://github.com/browniebroke/deezer-python/commit/59b0f578127a99622632f51359ba88cc23dcaa1b))
* Ability to manage artists from the user's library ([`10f2967`](https://github.com/browniebroke/deezer-python/commit/10f29678c262be6349703ed093f0dbb96eea256a))
* Ability to manage albums from the user's library ([`45f9bba`](https://github.com/browniebroke/deezer-python/commit/45f9bbac416a359a06cc7c2b270161dff8119a8d))
* Add support to rate an album ([`c8dc771`](https://github.com/browniebroke/deezer-python/commit/c8dc771b6c11c927cd599dc88563b9ec6db2f994))
* Add support to rate an album ([`1c72557`](https://github.com/browniebroke/deezer-python/commit/1c725572fa66839ddc1f7ed3b1f7a529a8d0572d))
* Basic structure to support POST method ([`9da4e81`](https://github.com/browniebroke/deezer-python/commit/9da4e81ed80c516d806502eed4b1671eb944b75c))

## v3.0.0 (2021-10-09)
### Breaking
* remove deprecated `asdict` method on `Resource` class  ([`daeee61`](https://github.com/browniebroke/deezer-python/commit/daeee6131d249106a2233e432a179aba40cdbbc8))
* remove deprecated `host` and `use_ssl` arguments for `Client`  ([`2bd2c39`](https://github.com/browniebroke/deezer-python/commit/2bd2c39988066999d3ae34995e1e98c31d6c5a17))

### Documentation
* Use https in link ([`f7eb114`](https://github.com/browniebroke/deezer-python/commit/f7eb114e4d1d0dba9e8a65f25cb2ce842270036e))

## v2.4.0 (2021-10-07)
### Feature
* Add official python 3.10 support ([`b29b0cb`](https://github.com/browniebroke/deezer-python/commit/b29b0cb87e025bc52663c8d81d0f1dd94277badc))

## v2.3.1 (2021-09-13)
### Fix
* **deps:** Update dependency sphinx-rtd-theme to v1 ([`af43757`](https://github.com/browniebroke/deezer-python/commit/af43757238760ca8fa23ff67cafa11cd8dd74eea))

### Documentation
* Fix docstrings ([`0e87749`](https://github.com/browniebroke/deezer-python/commit/0e87749c182f59b40341f85b61dbb73578ed6567))

## v2.3.0 (2021-06-27)
### Feature
* Deprecate the `asdict` method from the `Resource` class ([`412b954`](https://github.com/browniebroke/deezer-python/commit/412b954791f9759028ad8320528f56347cc89d1b))

## v2.2.4 (2021-06-13)
### Fix
* **deps:** Update dependency myst-parser to ^0.15 ([`81ed3d8`](https://github.com/browniebroke/deezer-python/commit/81ed3d88389a321d4fb2d980d1154a055060e8c8))

## v2.2.3 (2021-05-04)
### Fix
* **deps:** Update dependency myst-parser to ^0.14 ([`9fbc55a`](https://github.com/browniebroke/deezer-python/commit/9fbc55a7371dd6c2bba1d9dd2d9b9f6650c37df2))

## v2.2.2 (2021-04-06)
### Fix
* Release in a separate environment ([`4d987d0`](https://github.com/browniebroke/deezer-python/commit/4d987d0076c2e763424eeadd9c6cbbbf71706498))
* **deps:** Update dependency sphinx-autobuild to v2021 ([`f70a1bd`](https://github.com/browniebroke/deezer-python/commit/f70a1bda9c28e1cf2d1d1140a0fbf482ae0bc6cb))
* **deps:** Update dependency myst-parser to ^0.13 ([`73255fb`](https://github.com/browniebroke/deezer-python/commit/73255fb3c79f28155744ff7ff37511761e17abd6))

## v2.2.1 (2020-10-23)
### Fix
* Set minimum python version to 3.6 ([`4ff223d`](https://github.com/browniebroke/deezer-python/commit/4ff223df0e144ecddcd0eb2918b2ed161776490a))
* Poetry extras ([`cc36e0f`](https://github.com/browniebroke/deezer-python/commit/cc36e0ffa70267efee6aeeff169d7dd186a73ea6))

## v2.2.0 (2020-10-13)
### Feature
* Switch to Poetry (#196) ([`92030dd`](https://github.com/browniebroke/deezer-python/commit/92030dd9409ba906716cea3f7f49e30a9a5a8cf7))

### Fix
* Build command for PSR ([`c76b8ea`](https://github.com/browniebroke/deezer-python/commit/c76b8ea5f396586ab9eddf4bdd265438d0410351))

## v2.1.0 (2020-10-10)
### Feature
* Add support for python 3.9 ([`b4669ee`](https://github.com/browniebroke/deezer-python/commit/b4669ee0e1f698529b78a37c64d6daf210d8970a))

### Documentation
* Add naveen521kk as a contributor (#171) ([`0df16d3`](https://github.com/browniebroke/deezer-python/commit/0df16d34c1005ade3751f6f762e06387440894a8))

## v2.0.0 (2020-10-01)
### Feature
* Drop support for Python 3.5 ([`20d999b`](https://github.com/browniebroke/deezer-python/commit/20d999ba370cf0bc643434d8257cfd9821ef26de))

### Fix
* Include docs/*.md files in package ([`5fcc38d`](https://github.com/browniebroke/deezer-python/commit/5fcc38df6e9137fd9d4d362141e428727a632565))

### Breaking
* dropping EOL Python version ([`20d999b`](https://github.com/browniebroke/deezer-python/commit/20d999ba370cf0bc643434d8257cfd9821ef26de))

## v1.6.2 (2020-09-21)
### Fix
* Remove universal wheel option ([`5f31f14`](https://github.com/browniebroke/deezer-python/commit/5f31f14ce77f9363b33ba42130ad190cbd4fe4ce))
* Fix missing requirements when running tests ([`cb7d421`](https://github.com/browniebroke/deezer-python/commit/cb7d421ddaa166f168dcaff42c2944fd3334437a))
* Fix configuration for python-semantic-release ([`dd446d2`](https://github.com/browniebroke/deezer-python/commit/dd446d2d438c6045ea2640776f80d7ee7ce29e66))

## [v1.6.1](https://github.com/browniebroke/deezer-python/tree/1.6.1) (2020-08-27)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/1.6.0...1.6.1)

### 🐛 Bug Fixes:

- Fix Playlist.iter\_fans, improve tests to catch similar errors [\#139](https://github.com/browniebroke/deezer-python/pull/139) ([hithomasmorelli](https://github.com/hithomasmorelli))

## [v1.6.0](https://github.com/browniebroke/deezer-python/tree/1.6.0) (2020-08-20)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/1.5.0...1.6.0)

### 🚀 Enhancements:

- Fix crash for unknown resource, add Podcast & Episode resources [\#134](https://github.com/browniebroke/deezer-python/pull/134) ([hithomasmorelli](https://github.com/hithomasmorelli))
- 📦 Move package metadata to setup.cfg [\#91](https://github.com/browniebroke/deezer-python/pull/91) ([browniebroke](https://github.com/browniebroke))

### 📖 Documentation updates:

- Add hithomasmorelli as a contributor [\#138](https://github.com/browniebroke/deezer-python/pull/138) ([allcontributors[bot]](https://github.com/apps/allcontributors))

### ✅ Testing:

- Use codecov-action to upload coverage report [\#97](https://github.com/browniebroke/deezer-python/pull/97) ([browniebroke](https://github.com/browniebroke))
- Pin dependencies in requirements files [\#94](https://github.com/browniebroke/deezer-python/pull/94) ([browniebroke](https://github.com/browniebroke))
- ☂️ Increase test coverage to 100% [\#92](https://github.com/browniebroke/deezer-python/pull/92) ([browniebroke](https://github.com/browniebroke))

## [v1.5.0](https://github.com/browniebroke/deezer-python/tree/1.5.0) (2020-07-01)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/1.4.0...1.5.0)

### 🚀 Enhancements:

- Add `get\_tracks` and `get\_fans` methods to `Playlist` resources [\#90](https://github.com/browniebroke/deezer-python/pull/90) ([browniebroke](https://github.com/browniebroke))

### 📖 Documentation updates:

- Migrate most of the docs to Markdown with MyST [\#85](https://github.com/browniebroke/deezer-python/pull/85) ([browniebroke](https://github.com/browniebroke))
- Improve documentation for resources [\#84](https://github.com/browniebroke/deezer-python/pull/84) ([browniebroke](https://github.com/browniebroke))

### ✅ Testing:

- Refactor tests to use the pytest style [\#89](https://github.com/browniebroke/deezer-python/pull/89) ([browniebroke](https://github.com/browniebroke))
- Split resources tests into multiple classes [\#88](https://github.com/browniebroke/deezer-python/pull/88) ([browniebroke](https://github.com/browniebroke))
- 🛠 Move CI to Github actions [\#86](https://github.com/browniebroke/deezer-python/pull/86) ([browniebroke](https://github.com/browniebroke))

## [v1.4.0](https://github.com/browniebroke/deezer-python/tree/1.4.0) (2020-05-02)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/1.3.0...1.4.0)

### 🚀 Enhancements:

- Use explicit kwargs for the Client class [\#79](https://github.com/browniebroke/deezer-python/pull/79) ([browniebroke](https://github.com/browniebroke))

### 📖 Documentation updates:

- Documentation reworking and explain usage [\#78](https://github.com/browniebroke/deezer-python/pull/78) ([browniebroke](https://github.com/browniebroke))
- Auto generate changelog [\#75](https://github.com/browniebroke/deezer-python/pull/75) ([browniebroke](https://github.com/browniebroke))

### ✅ Testing:

- Clean-up config for coverage [\#80](https://github.com/browniebroke/deezer-python/pull/80) ([browniebroke](https://github.com/browniebroke))
- Use Python 3.8 on Travis \(drop the -dev\) [\#77](https://github.com/browniebroke/deezer-python/pull/77) ([browniebroke](https://github.com/browniebroke))
- Update names in Github action & run on Python 3.8 [\#76](https://github.com/browniebroke/deezer-python/pull/76) ([browniebroke](https://github.com/browniebroke))

## [v1.3.0](https://github.com/browniebroke/deezer-python/tree/1.3.0) (2019-11-09)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/1.2.0...1.3.0)

### 🚀 Enhancements:

- Add Python 3.8 support [\#71](https://github.com/browniebroke/deezer-python/pull/71) ([jnth](https://github.com/jnth))

### 🐛 Bug Fixes:

- Get method error handling [\#64](https://github.com/browniebroke/deezer-python/pull/64) ([nrebena](https://github.com/nrebena))

### ✅ Testing:

- Add isort [\#72](https://github.com/browniebroke/deezer-python/pull/72) ([browniebroke](https://github.com/browniebroke))
- Remove appveyor.yml [\#70](https://github.com/browniebroke/deezer-python/pull/70) ([browniebroke](https://github.com/browniebroke))
- Move deploy step to a separate stage on Travis [\#61](https://github.com/browniebroke/deezer-python/pull/61) ([browniebroke](https://github.com/browniebroke))

## [v1.2.0](https://github.com/browniebroke/deezer-python/tree/1.2.0) (2019-09-25)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/1.1.2...1.2.0)

### 🚀 Enhancements:

- Add a header kwarg in Client to force session headers [\#60](https://github.com/browniebroke/deezer-python/pull/60) ([jnth](https://github.com/jnth))
- Add user's favorite albums, artists, tracks and playlists in user resource. [\#53](https://github.com/browniebroke/deezer-python/pull/53) ([jnth](https://github.com/jnth))

### 📖 Documentation updates:

- Update Travis CI badge: travis.org -\> travis.com [\#57](https://github.com/browniebroke/deezer-python/pull/57) ([browniebroke](https://github.com/browniebroke))
- Create .config for all-contributors bot [\#51](https://github.com/browniebroke/deezer-python/pull/51) ([browniebroke](https://github.com/browniebroke))

### ✅ Testing:

- Create pythonpackage.yml to enable GitHub actions [\#58](https://github.com/browniebroke/deezer-python/pull/58) ([browniebroke](https://github.com/browniebroke))

## [v1.1.0](https://github.com/browniebroke/deezer-python/tree/1.1.0) (2019-05-25)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/1.0.0...1.1.0)

### 💥 Breaking Changes:

- Drop support for EOL Python 3.4 [\#47](https://github.com/browniebroke/deezer-python/pull/47) ([hugovk](https://github.com/hugovk))

### 📖 Documentation updates:

- Update template to match filename [\#48](https://github.com/browniebroke/deezer-python/pull/48) ([hugovk](https://github.com/hugovk))

### ✅ Testing:

- Python 3.7+ support [\#44](https://github.com/browniebroke/deezer-python/pull/44) ([browniebroke](https://github.com/browniebroke))
- Test with `vcrpy` [\#43](https://github.com/browniebroke/deezer-python/pull/43) ([jnth](https://github.com/jnth))

## [v1.0.0](https://github.com/browniebroke/deezer-python/tree/1.0.0) (2019-02-11)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/0.9.0...1.0.0)

### 💥 Breaking Changes:

- Drop Python 2 support [\#41](https://github.com/browniebroke/deezer-python/pull/41) ([hugovk](https://github.com/hugovk))

## [v0.9.0](https://github.com/browniebroke/deezer-python/tree/0.9.0) (2019-02-10)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/0.8.0...0.9.0)

### 🚀 Enhancements:

- Add advanced search method [\#37](https://github.com/browniebroke/deezer-python/pull/37) ([jnth](https://github.com/jnth))

## [v0.8.0](https://github.com/browniebroke/deezer-python/tree/0.8.0) (2018-10-30)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/0.7.0...0.8.0)

### 🚀 Enhancements:

- Auto-format code using black [\#35](https://github.com/browniebroke/deezer-python/pull/35) ([browniebroke](https://github.com/browniebroke))
- Make tornado an optional requirements [\#34](https://github.com/browniebroke/deezer-python/pull/34) ([browniebroke](https://github.com/browniebroke))
- Pagination feature [\#32](https://github.com/browniebroke/deezer-python/pull/32) ([MDCEY](https://github.com/MDCEY))

## [v0.7.0](https://github.com/browniebroke/deezer-python/tree/0.7.0) (2018-10-03)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/0.6.1...0.7.0)

### 💥 Breaking Changes:

- Change name files names and docs from async [\#28](https://github.com/browniebroke/deezer-python/pull/28) ([horstmannmat](https://github.com/horstmannmat))

### 🚀 Enhancements:

- Store the session in the client [\#24](https://github.com/browniebroke/deezer-python/pull/24) ([sheregeda](https://github.com/sheregeda))

### ✅ Testing:

- Add a CI step for check-manifest [\#30](https://github.com/browniebroke/deezer-python/pull/30) ([browniebroke](https://github.com/browniebroke))
- Update build matrices [\#29](https://github.com/browniebroke/deezer-python/pull/29) ([browniebroke](https://github.com/browniebroke))
- Appveyor tests [\#25](https://github.com/browniebroke/deezer-python/pull/25) ([browniebroke](https://github.com/browniebroke))

## [v0.6.1](https://github.com/browniebroke/deezer-python/tree/0.6.1) (2017-06-19)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/0.6.0...0.6.1)

### 🚀 Enhancements:

- Add access token to request kwargs [\#20](https://github.com/browniebroke/deezer-python/pull/20) ([sheregeda](https://github.com/sheregeda))

### 📖 Documentation updates:

- Update README.rst [\#18](https://github.com/browniebroke/deezer-python/pull/18) ([khamaileon](https://github.com/khamaileon))

## [v0.6.0](https://github.com/browniebroke/deezer-python/tree/0.6.0) (2016-12-27)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/0.5.0...0.6.0)

### 🚀 Enhancements:

- Refactoring: replace urlopen by requests [\#16](https://github.com/browniebroke/deezer-python/pull/16) ([browniebroke](https://github.com/browniebroke))

## [v0.5.0](https://github.com/browniebroke/deezer-python/tree/0.5.0) (2016-12-26)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/0.4.0...0.5.0)

### 📖 Documentation updates:

- Docs enhancements [\#13](https://github.com/browniebroke/deezer-python/pull/13) ([browniebroke](https://github.com/browniebroke))

### ✅ Testing:

- Run Flake8 on Travis [\#14](https://github.com/browniebroke/deezer-python/pull/14) ([browniebroke](https://github.com/browniebroke))
- Use tox-travis to integrate environments better [\#12](https://github.com/browniebroke/deezer-python/pull/12) ([browniebroke](https://github.com/browniebroke))

## [v0.4.0](https://github.com/browniebroke/deezer-python/tree/0.4.0) (2016-12-08)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/0.3.0...0.4.0)

### 🚀 Enhancements:

- Improve chart integration [\#11](https://github.com/browniebroke/deezer-python/pull/11) ([pfouque](https://github.com/pfouque))
- Add pypy to the build matrix [\#10](https://github.com/browniebroke/deezer-python/pull/10) ([browniebroke](https://github.com/browniebroke))
- Implement chart methods [\#8](https://github.com/browniebroke/deezer-python/pull/8) ([pfouque](https://github.com/pfouque))

### ✅ Testing:

- Switch from coveralls to codecov [\#9](https://github.com/browniebroke/deezer-python/pull/9) ([browniebroke](https://github.com/browniebroke))
- Correct a couple of flake8 warning [\#7](https://github.com/browniebroke/deezer-python/pull/7) ([browniebroke](https://github.com/browniebroke))
- Add basic flake8 config to setup.cfg [\#6](https://github.com/browniebroke/deezer-python/pull/6) ([browniebroke](https://github.com/browniebroke))

## [v0.3.0](https://github.com/browniebroke/deezer-python/tree/0.3.0) (2016-11-09)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/0.2.3...0.3.0)

### 🚀 Enhancements:

- add resource parameters and iterators [\#5](https://github.com/browniebroke/deezer-python/pull/5) ([pfouque](https://github.com/pfouque))
- Async client for Tornado, search [\#1](https://github.com/browniebroke/deezer-python/pull/1) ([misuzu](https://github.com/misuzu))

## [v0.2.1](https://github.com/browniebroke/deezer-python/tree/0.2.1) (2015-09-14)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/0.2...0.2.1)

### 🚀 Enhancements:

- Run tests against Python 3.5 [\#3](https://github.com/browniebroke/deezer-python/pull/3) ([browniebroke](https://github.com/browniebroke))

## [v0.2](https://github.com/browniebroke/deezer-python/tree/0.2) (2015-01-31)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/0.1...0.2)

### 🚀 Enhancements:

- Methods for resources [\#2](https://github.com/browniebroke/deezer-python/pull/2) ([misuzu](https://github.com/misuzu))

## [v0.1](https://github.com/browniebroke/deezer-python/tree/0.1) (2014-11-23)

[Full Changelog](https://github.com/browniebroke/deezer-python/compare/e87692f7aeb80bc0ed858ccdf6165f0ac8f9c2ec...0.1)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
