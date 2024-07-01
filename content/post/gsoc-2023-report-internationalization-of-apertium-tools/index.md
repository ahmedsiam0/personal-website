---
title: 'GSoC 2023 Report: Internationalization of Apertium Tools'
description: Report that describes what I have done during Google Summer of Code 2023 at Apertium
slug: gsoc-2023-report-internationalization-of-apertium-tools
date: 2022-08-27 23:08:14+0000
image: cover.png
tags:
    - gsoc
    - i18n
    - apertium
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

This project aims to [internationalize](https://en.wikipedia.org/wiki/Internationalization_and_localization) Apertium tools so that they can be [localized](https://en.wikipedia.org/wiki/Internationalization_and_localization) easily to other languages, which makes usage of Apertium tools easier for non-English users. I have done this by building and using a [library](https://github.com/apertium/icuformat) that wraps [ICU4C](https://icu.unicode.org/#h.i33fakvpjb7o), which supports Unicode and internationalization.

## Background

- Apertium is a rule-based machine translation toolchain and ecosystem.

- Apertium tools were hard-coded as English only.

## Achieved Goals

- Internationalized Apertium tools.

- Assigned codes to error/warning messages for easy search online.

- Created a wiki page for each warning/error in the [Apertium wiki](https://wiki.apertium.org/wiki/Category:Error_Codes) (except for apertium-recursive and lexd repos).

## Future Goals

- Make wiki pages for apertium-recursive and lexd errors/warnings

- More testing.

- Simplify code and rephrase messages to be more useful.

- Help in adding languages other than English ([Localization](https://en.wikipedia.org/wiki/Internationalization_and_localization)).

## Source Code

- [https://apertium.projectjj.com/gsoc2023/ahmedsiam0.html](https://apertium.projectjj.com/gsoc2023/ahmedsiam0.html)
