---
layout: default
title: Other
permalink: /other
---

# Other

[`Home`](/index) | [`Publications`](/publication) | [`Other`](/other)

## Activities
### Running
* Cooper River Bridge Run, Apr 2, 2022. [TIME 54:25](https://results2.xacte.com/#/e/2429/searchable/11454).
* Atlanta Journal-Constitution Peachtree Road Race 10K, July 4, 2022. [TIME 54:44](https://www.athlinks.com/event/115192/results/Event/1016777/Course/2241401/Bib/9687).
* The Mega Cupcake Marathon @ Hawthorne HM, November 24, 2024. [TIME 2:05:09](https://runsignup.com/Race/Results/82263/IndividualResult/HPSd?resultSetId=512775#U91579045).
* Tom Walker Half Marathon, November 9, 2025. [TIME 2:01:13](https://runsignup.com/Race/Results/115494/IndividualResult/TMCq?resultSetId=605096#U91579045).
* FTC Archer Braid Trail 10K, Mar 28, 2026. [TIME 55:59](https://runsignup.com/Race/FL/Archer/ArcherBraidTrail5k10k).

## Curiosities
* A minigame to test your marketing intuition. [Click here.](https://dayuan-wang.github.io/Market-maker-game/)

## Writing
I share short research notes, technical posts, and project updates here:
[Browse all articles (tree view)](/articles/)

### Latest posts
{% if site.posts.size > 0 %}
{% for post in site.posts limit:3 %}
* **{{ post.date | date: "%b %d, %Y" }}** - [{{ post.title }}]({{ post.url }})
{% endfor %}
{% else %}
* No articles yet. First post coming soon.
{% endif %}
