---
title: "Amber: Distributed Web Caching Service (Sorta)"
date: 2017-02-16 13:57:00 -0800
draft: false
categories:
    - Internet
---

[Amber][1] is an attempt from [Harvard's Berkman Klein Center for Internet & Society][2] to get content creators and publishing platforms to help distribute (or populate centralized) cached copies of linked content. By default it keeps locally (on your infrastructure) cached copies of content you link to so that if that content disappears you can still serve up a reference to that content. It will also allow you to use a centralized copy such as the [Internet Archive][3] for this same purpose. As of this posting they are providing plugins for Drupal and Wordpress as well modules for the Apache and Nginx HTTP web servers. 

Given the potential copyright issues (they do allow for content publishers to opt-out of the Amber content fetcher) I would prefer a centrally shared repository such as the Internet Archive to be the default storage mechanism but I do appreciate the single-point-of-failure flaw in that thinking. The pros & cons for local for central seemingly changed based on the type of content your are refer to but my instincts say the "install and forget" crowd would best serve the Internet by populating the Internet Archives' "Wayback Machine".

[1]: http://amberlink.org
[2]: http://cyber.law.harvard.edu/
[3]: https://archive.org
