---
layout: page
title: Developer information
permalink: /developer
nav_order: 80
has_children: true
---

Developer Information
=====================

The pages here are intended for developers who [are making][guidelines] or maintaining a package,
especially one that is part of Scikit-HEP or being proposed to become part.

New developers are encouraged to read the following pages.
Veteran developers should still check out [introduction][intro], as it has a guide on recommendations for your `CONTRIBUTING.md`.

Following that, there are recommendations for [style][], intended to promote
good practices and to ensure continuity across the packages.  There is then a
guide on [packaging][], which should help in ensuring a consistent developer
and user experience when working with distribution.

A section on CI follows, with a [general setup guide][gha_basic], and then two choices for using CI to distribute
your package, on for [pure Python][gha_pure], and one for [compiled extensions][gha_wheels].

Finally, there are [badge recommendations][badges] for your readme, including the Scikit-HEP badge!

[guidelines]: {{ site.baseurl }}{% link pages/developers/guidelines.md %}
[intro]: {{ site.baseurl }}{% link pages/developers/intro.md %}
[style]: {{ site.baseurl }}{% link pages/developers/style.md %}
[packaging]: {{ site.baseurl }}{% link pages/developers/packaging.md %}
[gha_basic]: {{ site.baseurl }}{% link pages/developers/gha_basic.md %}
[gha_pure]: {{ site.baseurl }}{% link pages/developers/gha_pure.md %}
[gha_wheels]: {{ site.baseurl }}{% link pages/developers/gha_wheels.md %}
[badges]: {{ site.baseurl }}{% link pages/developers/badges.md %}
