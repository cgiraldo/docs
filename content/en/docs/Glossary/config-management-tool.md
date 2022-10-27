---
title: Configuration management tool
id: config-management-tool
full_link: /docs/concepts/score/
short_description: >
    Score isn't a configuration management tool.
tags:
- fundamental
- testing
---

Score doesn't specify any `dns` or `route` attribute values in the specification file.

<!-- more -->

Those values may change based on the target environment, like `testing`, `integration`, or `production`

For example, route table management is a configuration management task and Score isn't a configuration management tool.
