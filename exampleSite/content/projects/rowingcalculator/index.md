---
title: "Rowing Calculator"
date: 2023-12-01
lastMod: 2026-02-19
draft: false
project_tags: ["technology", "rowing"]
status: "composting"
summary: "多功能赛艇计算器应用程序"
weight: 3
---

## 死亡说明

快两年过去了，我对写代码认识更多了。显然当时的想法很幼稚，技术的选择当时我为它找到了使用的理由，但是真正的理由是没有能力使用更合适的技术。（这个现象值得写一篇文章来讨论）我有想重启、重构项目的想法，或许使用Flutter。2025年末我入手了Mac电脑，可以更方便地在各平台测试。——2026年2月

## 简介

这是一个集合了多个赛艇相关的计算器的应用程序。

制作它的原因是这些计算器都在互联网的不同网站上，如[体重调整计算器](https://www.concept2.com/indoor-rowers/training/calculators/weight-adjustment-calculator)在Concept2的网站上，计算不同距离下的配速公式[Paul's Law](https://www.machars.net/)在一个另一位用户做的网站上。我希望把这几个计算器集中在一起，并能方便地在多平台使用。

目前这个软件包括了以下计算器：

- 配速-总时间-距离转换
- 配速-功率转换
- 500m配速-时速转换
- 体重调整
- 保罗定律
- 自定义版保罗定律
- 心率百分比区间
- 配速百分比转换

## 技术

这是我第一次尝试写应用程序。

我希望它能全平台使用，所以我曾在[Flutter](https://flutter.dev/)和[React Native](https://reactnative.dev/)之间选择，谷歌Flutter使用Dart语言，而Meta的React Native使用JavaScript，所以我选择了自己更为熟悉的JavaScript也就是React Native。

我发现了一个神奇的平台[Expo Snack](https://snack.expo.dev/)，它允许我在线编辑React Native app的代码，并不用在任何操作系统中配置环境，而直接通过其app在各操作系统运行代码。

我希望应用的UI可以更加原生，这样UI更漂亮，同时我作为新手编写起来也更轻松。因此我了解到了谷歌的[Material Design 3](https://m3.material.io/)（也就是Material You），最终我使用了[React Native Paper](https://reactnativepaper.com/)作为我主要的UI组件。

## 更新日记

2024年6月13日 抽空又进行了一些编写。增加了很多易用性，UI也几乎全部替换为React Native Paper。
