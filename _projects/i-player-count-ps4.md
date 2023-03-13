---
layout: project
title: Player count of PS games 
---

Find a player count of PS4 games on a leaked dataset.

Application performs an OCR on the [leakead images containing PS4 player counts](https://arstechnica.com/gaming/2018/12/sony-inadvertently-leaks-player-counts-for-ps4-titles/), 
then does a fuzzy search to check if image contains a game title you are looking for.

**Tech stack:**
- *python*
- *OpenCV*
- *pytorch*

[Source code](https://gitlab.com/spestushko/player_count_ps4)

![_config.yml]({{ site.baseurl }}/images/ps4_players.png)