---
title: Alice Novel, v0.9.3 release schedule
description: Next release schedule
slug: 20241004-alicenovel-next
date: 2024-10-04 21:20:00+0900
categories:
    - Project
    - Alice Novel
    - "Progress: Plan"
tags:
    - Release schedule
---

I am planning to release next version, v0.9.3 of Alice Novel. That's include some ci/cd fixes, changing directory structured and updated packages.

### Currently

Currently, I decided to include some PRs, it shows below.

- docs (license): change the license ([#72](https://github.com/AliceNovel/AliceNovel/pull/72))
- chore (dependencies): bump dependencies ([#73](https://github.com/AliceNovel/AliceNovel/pull/73))
- chore (dependencies): bump maui version ([#74](https://github.com/AliceNovel/AliceNovel/pull/74))
- chore (ci/cd): recreate the android ci/cd on azure devops ([#77](https://github.com/AliceNovel/AliceNovel/pull/77))
- build (deps): bump packages ([#78](https://github.com/AliceNovel/AliceNovel/pull/78))
- chore (ci/cd): bump actions/upload-artifact from v3 to v4 ([#46](https://github.com/AliceNovel/AliceNovel/pull/46))

### Schedule

I want to add some PRs by next release.

- chore (scripts): move scripts files and update documentations ([#76](https://github.com/AliceNovel/AliceNovel/pull/76))

And, this application has issue about its save system. So the system has bugs and it need to replace into new system. (Related: [#67](https://github.com/AliceNovel/AliceNovel/issues/67))

In addition, I think that [#69](https://github.com/AliceNovel/AliceNovel/issues/69) (disable the save button until read `.anproj` file) and [#10](https://github.com/AliceNovel/AliceNovel/issues/10) (i18n English) is easy to close issue.

In short, I have a view to fix [#76](https://github.com/AliceNovel/AliceNovel/pull/76), [#67](https://github.com/AliceNovel/AliceNovel/pull/67) (include [#61](https://github.com/AliceNovel/AliceNovel/issues/61) for Android and [#47](https://github.com/AliceNovel/AliceNovel/issues/47) for Windows) , [#69](https://github.com/AliceNovel/AliceNovel/pull/69), [#10](https://github.com/AliceNovel/AliceNovel/pull/10) and some refactoring by the release of v0.9.3.

## Distribute
- [Lemon73 Blog (here)](./) (October 04, 2024)
