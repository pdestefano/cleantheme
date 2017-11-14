---
layout: guidelines
title: Testing
heading: Testing
permalink: /guidelines/testing/
---

We aim to write a lot of tests -- each module should have at least some kind of
test associated with it. These can be traditional unit tests, black-box tests
that talk through the WS API, and/or proper integration tests.

When hunting down problems, it is considered good form to write a test that
demonstrates the problem first, then a fix that makes the test pass.

