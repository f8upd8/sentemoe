---
title: "Solo or Multiple Character Detection (Baseline Version)"
date: 2023-07-08T20:18:57+07:00
draft: false
---

## Project Goal

The goal was to make something very simple, yet at least a little bit interesting as a part of me going through Fast.AI course.
This is supposed to be a trivial (at least for 2023) application that is able to visually discern if there is one or multiple characters on an anime picture.
This is a baseline model, it means that I used the simplest solution I had in hand that I can further improve.

## Data

For Data, I simply used Grabber to download ~2000 pictures for each category. I included tags "2girls", "3girls", "group" when downloading pictures of anime waifus in groups, and tag "solo" is self-explanatory too.

## Results & Thouhts

The best I could achieve is 10% error on the validation set, which is pretty satisfying for a baseline.
Result might be improved using CLIP, OpenPose or even Segment Anything as well as other, more modern than ResNet16 models for CV. I'll sure

## Demo

{{% solo_or_not_hf %}}

