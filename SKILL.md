---
name: youtube-title-thumbnail-workflow
description: Use when packaging China immersive YouTube videos from user-provided video files, location details, local features, and numeric highlights into high-CTR English titles, thumbnail images, descriptions, and tags. Trigger for requests to create YouTube titles, thumbnails, cover images, descriptions, SEO copy, or complete packaging workflows for China walking, village, ancient town, rainy, misty, rural, or scenic videos.
---

# YouTube Title Thumbnail Workflow

## Overview

Use this skill to package China immersive video content for English-language YouTube audiences. The goal is not neutral location labeling; the goal is a title + thumbnail system with enough curiosity, SEO value, and visual promise to target a 10% YouTube open rate while staying anchored to the video's real content.

When doing detailed title/thumbnail judgment, read `references/standard.md`.

## Inputs

Expect the user to provide some or all of:

- A video file.
- Local information: place, region, geography, history, culture, or route.
- Local features: ancient town, village, valley, mist, rain, river, road, architecture, street life, market, bridge, mountain, or people.
- Numeric highlights: duration, number of locations, route count, scenic points, distance, age, altitude, steps, bridges, villages, or other credible numbers.
- Any facts that must not be exaggerated or written as certain.

If the user gives a video file, inspect it and find usable screenshots/keyframes before deciding thumbnail directions. If the user provides limited metadata, infer from the video and avoid inventing core facts.

## Two-Step Workflow

### Step 1 - Exploration Pack

Deliver:

- 10 English titles.
- 6 thumbnail image previews.

Each title must:

- Include `China`.
- Include at least one credible number.
- Combine high-click curiosity with SEO value.
- Pair with the thumbnail concept instead of acting as standalone copy.

Each thumbnail preview must:

- Be an image, not only a written prompt.
- Use a 16:9 YouTube thumbnail composition.
- Include core elements visible in the video or strongly supported by the video.
- Use 3-5 English words only when text adds mystery or a strong finishing touch.
- Prioritize visual clarity at mobile size.

### Step 2 - Final Pack

After the user selects a title/thumbnail direction, deliver:

- Final 1280 x 720 YouTube thumbnail.
- Final title.
- YouTube description.
- Tags.

Save outputs under the active project unless the user specifies otherwise:

- Preview thumbnails: `output/youtube-packaging/thumbnails/`
- Final thumbnails: `output/youtube-packaging/final/`
- Copy: `output/youtube-packaging/copy/`

## Thumbnail Rules

The thumbnail does not have to be a raw screenshot, but it must contain the video's real core elements. It may use a stronger composition or better source image if the visual promise is still supported by the video.

Allowed enhancements:

- Add or strengthen people, if they fit the scene naturally.
- Add mist, rain, wet ground, light, reflections, atmosphere, and cinematic color.
- Recompose the scene for stronger foreground, midground, and background.
- Make rainy scenes more immersive through low-saturation cool tones, local warm light, haze layers, and wet surfaces.

Do not:

- Add core elements that do not exist or are not supported by the video.
- Invent giant palaces, fake ethnic costumes, nonexistent rivers, boats, bridges, or buildings.
- Create fantasy, wuxia, game, or overdone red-lantern imagery unless the video genuinely supports it.
- Make a thumbnail that viewers will experience as a bait-and-switch.

## Title Rules

Use title patterns that sell the experience before the administrative place name. Specific place names can go in the title when useful, but unfamiliar names should often move to the description.

Strong title language is allowed when supported by footage:

- Hidden
- Lost World
- Most Beautiful
- Secret
- Unreal
- Paradise
- Ancient
- Forgotten
- Misty
- Remote
- Untouched
- Breathtaking

Avoid flat titles such as `Walking in Guangxi 4K`, `China Village Tour`, or `Ancient Town Walking Video`.

## Completion Criteria

Before finishing, check:

- The final title contains `China` and a credible number.
- The thumbnail and title support the same click promise.
- The thumbnail is readable as a small YouTube image.
- The thumbnail has a clear subject and curiosity.
- The thumbnail uses real or video-supported core elements.
- Description and tags reinforce the same topic and SEO direction.
- The overall package is deliberately optimized toward a 10% open-rate target.
