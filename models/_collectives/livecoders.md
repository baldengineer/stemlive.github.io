---
title: Live Coders
tag: livecoders
description: >-
  Which Twitch streamers belong to the Live Coders collective?
images:
  thumbnail:
    filename: "livecoders.jpg"
links:
  website: https://livecoders.dev/
  facebook: https://www.facebook.com/thelivecoders/
  github: https://github.com/livecoders/
  twitch: https://www.twitch.tv/team/livecoders
  twitter: https://twitter.com/thelivecoders
  youtube: https://www.youtube.com/thelivecoders
layout: collective
---
{%- assign collective_streamers = site.educators | where: 'collectives', 'livecoders' | where: 'display_on_site', true -%}
# About {{ page.title }}

Comprised of a number of programmers, some of whom work for big name brands and companies, the **{{ page.title }}** community aims to broadcast high-quality programming content to its viewership.

At present, this collective has a total of <span class="counter">{{ collective_streamers.size }}</span> streamers registered on {{ site.title }}.
