---
layout: post
title: artillery.io
date: 2022-09-30 22:30:00 +0200
description: Website or API load testing with Artillery.io
img: loadtesting.jpg
tags: [testing]
author: wim
---

# Artillery.io

Artillery is an open-source performance & reliability testing suite for
developers & SREs

- Emulate user behavior with scenarios - with multiple steps, transactions,
  request chaining, and more
- Run scenarios as load tests or end-to-end synthetic tests
- Full-stack attack - test at the protocol level (HTTP, WebSocket,
  Socket.io, and more) or with real headless browsers
- And lots more: detailed performance metrics, monitoring/o11y integrations,
  extension APIs for custom scripting in JavaScript, and plugins

[Why artillery](https://www.artillery.io/docs/guides/overview/why-artillery)

"Launching 10,000 browsers for fun and profit"

![Demo GIF]({{site.baseurl}}/assets/img/2022-09-30-artillery-playwright-load-testing-browsers.gif)

## Access tokens

- [How to automate the OAuth 2.0 token generation using Artillery?](https://stackoverflow.com/questions/58712212/how-to-automate-the-oauth-2-0-token-generation-using-artillery)
- [Using a 'before' hook to get the access token gives an error](https://github.com/artilleryio/artillery/issues/959)
