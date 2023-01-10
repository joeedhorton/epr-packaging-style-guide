<!-- ---
override:tags: []
layout: post
title: Check if EPR for packaging affects your organisation
description: A small service to help organisations understand if they are effected by the epr for packaging regulations and what they'll need to do if they are.
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
--- -->