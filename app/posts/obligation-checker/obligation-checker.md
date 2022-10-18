---
override:tags: []
layout: collection
title: Obligation checker tool
description: Help organisations understand if they are effected by the epr for packaging regulations
pagination:
  data: collections.obligation-checker
  reverse: true
  size: 50
permalink: "obligation-checker/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: Home
---