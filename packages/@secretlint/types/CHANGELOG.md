# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [5.3.0](https://github.com/secretlint/secretlint/compare/v5.2.4...v5.3.0) (2022-10-30)

**Note:** Version bump only for package @secretlint/types

## [5.2.4](https://github.com/secretlint/secretlint/compare/v5.2.3...v5.2.4) (2022-08-24)

**Note:** Version bump only for package @secretlint/types

## [5.2.1](https://github.com/secretlint/secretlint/compare/v5.2.0...v5.2.1) (2022-06-26)

### Bug Fixes

* **config-loader:** use native import() ([#275](https://github.com/secretlint/secretlint/issues/275)) ([7699777](https://github.com/secretlint/secretlint/commit/769977776eaa5bd8b663106195f88d7e3070d1d6))
* **deps:** update minor updates ([0913164](https://github.com/secretlint/secretlint/commit/0913164dbc3178dc7ec8230a2bcae6f2434eacfc))

# [5.2.0](https://github.com/secretlint/secretlint/compare/v5.1.3...v5.2.0) (2022-04-11)

**Note:** Version bump only for package @secretlint/types

## [5.1.3](https://github.com/secretlint/secretlint/compare/v5.1.1...v5.1.3) (2022-04-04)

**Note:** Version bump only for package @secretlint/types

## [5.1.2](https://github.com/secretlint/secretlint/compare/v5.1.1...v5.1.2) (2022-04-04)

**Note:** Version bump only for package @secretlint/types

## [5.1.1](https://github.com/secretlint/secretlint/compare/v5.1.0...v5.1.1) (2022-03-24)

**Note:** Version bump only for package @secretlint/types

# [5.1.0](https://github.com/secretlint/secretlint/compare/v5.0.1...v5.1.0) (2022-03-08)

**Note:** Version bump only for package @secretlint/types

## [5.0.1](https://github.com/secretlint/secretlint/compare/v5.0.0...v5.0.1) (2022-03-05)

**Note:** Version bump only for package @secretlint/types

# [5.0.0](https://github.com/secretlint/secretlint/compare/v4.2.1...v5.0.0) (2022-03-05)

### Bug Fixes

* **deps:** update dependencies ([7c665d5](https://github.com/secretlint/secretlint/commit/7c665d59e9e6ac6646f69800c609b1b07be693e4))

### chore

* Drop Node.js 12 support ([#226](https://github.com/secretlint/secretlint/issues/226)) ([d05fbe6](https://github.com/secretlint/secretlint/commit/d05fbe672bc0554a4fac98dd886b080fa6ea4e6d))

### Features

* **config-loader:** improve validation to config ([#224](https://github.com/secretlint/secretlint/issues/224)) ([222555f](https://github.com/secretlint/secretlint/commit/222555f46f230c451917bf87442b9473a67855bb))

### BREAKING CHANGES

* Drop Node.js 12 support
* **config-loader:** this change will throw error some config that is already wrong.

* fix: remove unused type

* chore: update test

* docs: fix

* test: add assertion for rule/preset impl

* test: add assertion for rule/preset impl

* test: fix test snapshot

* fix

* chore:  fix

# [4.2.0](https://github.com/secretlint/secretlint/compare/v4.1.4...v4.2.0) (2022-03-02)

### Features

* **sarif:** add @secretlint/secretlint-formatter-sarif ([#217](https://github.com/secretlint/secretlint/issues/217)) ([6cdf303](https://github.com/secretlint/secretlint/commit/6cdf303073d0686a1d5ac0004e1365b1b8a70205))

### Performance Improvements

* introduce turborepo ([#215](https://github.com/secretlint/secretlint/issues/215)) ([7080b05](https://github.com/secretlint/secretlint/commit/7080b052f1e02feb9146bfb054aa17b7e0ed27a1))

## [4.1.3](https://github.com/secretlint/secretlint/compare/v4.1.1...v4.1.3) (2021-10-13)

**Note:** Version bump only for package @secretlint/types

# [4.0.0](https://github.com/secretlint/secretlint/compare/v3.3.0...v4.0.0) (2021-09-15)

**Note:** Version bump only for package @secretlint/types

# [3.3.0](https://github.com/secretlint/secretlint/compare/v3.2.0...v3.3.0) (2021-07-05)

### Features

* **core:** add `maskSecrets` option ([#177](https://github.com/secretlint/secretlint/issues/177)) ([658db4b](https://github.com/secretlint/secretlint/commit/658db4b1f0526006bec0448f9cba9a02bc8edd4a))

# [3.1.0](https://github.com/secretlint/secretlint/compare/v3.0.0...v3.1.0) (2021-06-24)

**Note:** Version bump only for package @secretlint/types

# [3.0.0](https://github.com/secretlint/secretlint/compare/v2.2.0...v3.0.0) (2021-05-29)

**Note:** Version bump only for package @secretlint/types

# [2.2.0](https://github.com/secretlint/secretlint/compare/v2.1.1...v2.2.0) (2021-05-27)

**Note:** Version bump only for package @secretlint/types

## [2.1.1](https://github.com/secretlint/secretlint/compare/v2.1.0...v2.1.1) (2020-11-04)

**Note:** Version bump only for package @secretlint/types

# [2.1.0](https://github.com/secretlint/secretlint/compare/v2.0.0...v2.1.0) (2020-06-16)

**Note:** Version bump only for package @secretlint/types

# [2.0.0](https://github.com/secretlint/secretlint/compare/v1.1.0...v2.0.0) (2020-04-27)

### Bug Fixes

* **core:** change SecretLintRuleMessageTranslate to check statically ([03ccff1](https://github.com/secretlint/secretlint/commit/03ccff116390374193ca5975405b0cafeaf63932))

### BREAKING CHANGES

* **core:** It changes SecretLintRuleMessageTranslate interface

Rule need to change `messages` object format.

# [1.1.0](https://github.com/secretlint/secretlint/compare/v1.0.5...v1.1.0) (2020-04-04)

**Note:** Version bump only for package @secretlint/types

## [1.0.5](https://github.com/secretlint/secretlint/compare/v1.0.4...v1.0.5) (2020-04-03)

**Note:** Version bump only for package @secretlint/types

## [1.0.4](https://github.com/secretlint/secretlint/compare/v1.0.3...v1.0.4) (2020-03-31)

**Note:** Version bump only for package @secretlint/types

## [1.0.3](https://github.com/secretlint/secretlint/compare/v1.0.2...v1.0.3) (2020-03-30)

**Note:** Version bump only for package @secretlint/types

## [1.0.1](https://github.com/secretlint/secretlint/compare/v1.0.0...v1.0.1) (2020-03-29)

**Note:** Version bump only for package @secretlint/types

# [1.0.0](https://github.com/secretlint/secretlint/compare/v0.10.1...v1.0.0) (2020-03-18)

**Note:** Version bump only for package @secretlint/types

## [0.10.1](https://github.com/secretlint/secretlint/compare/v0.10.0...v0.10.1) (2020-03-18)

**Note:** Version bump only for package @secretlint/types

# [0.10.0](https://github.com/secretlint/secretlint/compare/v0.9.2...v0.10.0) (2020-03-18)

### Features

* **core:** support locale options ([256a58c](https://github.com/secretlint/secretlint/commit/256a58c6cd03f585f15dd09972212ca6dfb70ac4))

## [0.9.2](https://github.com/secretlint/secretlint/compare/v0.9.1...v0.9.2) (2020-03-16)

**Note:** Version bump only for package @secretlint/types

## [0.9.1](https://github.com/secretlint/secretlint/compare/v0.9.0...v0.9.1) (2020-03-16)

**Note:** Version bump only for package @secretlint/types

# [0.9.0](https://github.com/secretlint/secretlint/compare/v0.7.3...v0.9.0) (2020-03-16)

**Note:** Version bump only for package @secretlint/types

# [0.7.0](https://github.com/secretlint/secretlint/compare/v0.6.0...v0.7.0) (2020-03-01)

**Note:** Version bump only for package @secretlint/types

# [0.6.0](https://github.com/secretlint/secretlint/compare/v0.5.0...v0.6.0) (2020-02-29)

### Features

-   support terminalLink ([#65](https://github.com/secretlint/secretlint/issues/65)) ([a28ef9e](https://github.com/secretlint/secretlint/commit/a28ef9eb9b3803984ec37bbbd9cdf35e7d4b67a6))

# [0.5.0](https://github.com/secretlint/secretlint/compare/v0.4.2...v0.5.0) (2020-02-28)

**Note:** Version bump only for package @secretlint/types

## [0.4.1](https://github.com/secretlint/secretlint/compare/v0.4.0...v0.4.1) (2020-02-28)

**Note:** Version bump only for package @secretlint/types

# [0.4.0](https://github.com/secretlint/secretlint/compare/v0.3.0...v0.4.0) (2020-02-28)

### Features

-   **core:** support "disabled" options ([17c1391](https://github.com/secretlint/secretlint/commit/17c1391cbd19edfe72f894fcf2e3a9d50fc4a7d2))
-   **core:** support "disabledMessages" options ([17de33e](https://github.com/secretlint/secretlint/commit/17de33eaef2408c63cbaeecb4038c8878a292ca0))
-   **core:** support Context#ignore method ([7ca0445](https://github.com/secretlint/secretlint/commit/7ca0445e9a5c494ea52ab0b9efa302ef5c902e2f))
-   **types:** rule require `messages` ([412803e](https://github.com/secretlint/secretlint/commit/412803eeebe7f14ce67f1c33c2ba16eac2acf9a5))

# [0.3.0](https://github.com/secretlint/secretlint/compare/v0.2.0...v0.3.0) (2020-02-27)

**Note:** Version bump only for package @secretlint/types

# [0.2.0](https://github.com/secretlint/secretlint/compare/v0.1.2...v0.2.0) (2020-02-23)

### Features

-   **rule:** add `supportedContentTypes` to rule `meta` ([#39](https://github.com/secretlint/secretlint/issues/39)) ([3883c75](https://github.com/secretlint/secretlint/commit/3883c7578de38854aba2d1d20b8f167c8275f1c9))

# 0.1.0 (2020-02-16)

### Bug Fixes

-   **cli:** fix exit status ([04d9b41](https://github.com/secretlint/secretlint/commit/04d9b412fe60eb638d0cb131d95ed4dcfcc4c11a))
-   **core:** separate options to rules in preset ([1b16638](https://github.com/secretlint/secretlint/commit/1b166380b8174b1e474aab05a9c1e4b4f6bb0d1a))
-   **types:** fix type ([08b113c](https://github.com/secretlint/secretlint/commit/08b113cba971f37a1cfb3b0f10bc96f0614c6bcf))
-   fix type name ([08d39e8](https://github.com/secretlint/secretlint/commit/08d39e8fb8ce8c4eb7a8ac8087e7da969e3afa8b))
-   optional docs ([3d27587](https://github.com/secretlint/secretlint/commit/3d2758776f1bf638086a9bdfc1103c21fcc309a0))

### Features

-   **config-loader:** add config-loader ([c56e8a3](https://github.com/secretlint/secretlint/commit/c56e8a3b8f2b1dc5fc6b3306dbd3ef496b31feb5))
-   **config-loader:** add validation on loading ([686b879](https://github.com/secretlint/secretlint/commit/686b879928e60e3f886f0af50f3d51d495c364b0))
-   **core:** add basic core ([248e312](https://github.com/secretlint/secretlint/commit/248e3128d09fc73a3d0b247f56ee0c71ee01dae2))
-   **core:** support `ruleId` implicitly ([1aa6d5c](https://github.com/secretlint/secretlint/commit/1aa6d5c90c9b62714e45e0b997be6a20c56a208b))
-   **core:** support Localization ([845f24a](https://github.com/secretlint/secretlint/commit/845f24a2a5ba1af39a3da8c2b5d487f3f4e6c313))
-   **core:** support severity options ([876e936](https://github.com/secretlint/secretlint/commit/876e9360c324232aeade50fd7767fe8bd08907a5))
-   **formatter:** add @secretlint/formatter ([2b2d9ab](https://github.com/secretlint/secretlint/commit/2b2d9abe693848c3271abbdb9845feefed582a1e))
-   **secretlint-rule-preset-recommend:** implement secretlint-rule-preset-recommend ([2728140](https://github.com/secretlint/secretlint/commit/27281404717565a6bcea4749bb047cf0d6b777ed))
-   **tester:** support .secretlintrc options via file ([c137c00](https://github.com/secretlint/secretlint/commit/c137c00829d6ee903d0e81894e0d343fff94f089))
-   preset ([868ac0f](https://github.com/secretlint/secretlint/commit/868ac0f2526217e04a774a48c26d90a89937cee2))
