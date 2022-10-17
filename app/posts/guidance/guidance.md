---
override:tags: []
layout: collection
title: Guidance
description: A tool for support agents to manage the service
pagination:
  data: collections.guidance
  reverse: true
  size: 50
permalink: "guidance/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: Home
---