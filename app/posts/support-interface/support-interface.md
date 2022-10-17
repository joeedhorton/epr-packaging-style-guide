---
override:tags: []
layout: collection
title: Service support interface
description: A tool for support agents to manage the service
pagination:
  data: collections.support-interface
  reverse: true
  size: 50
permalink: "support-interface/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: Home
---