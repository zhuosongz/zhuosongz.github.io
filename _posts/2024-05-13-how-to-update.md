---
layout: post
title: How to update this webpage
date: 2024-05-13 00:32:13
description:
tags: formatting code
categories: update
tabs: true
---

- [Deploy on my local machine](#deploy-on-my-local-machine)
- [Publish on the website](#publish-on-the-website)

## Deploy on my local machine

Run the following codes:

```{shell}
bundle exec jekyll serve
```

## Publish on the website

Run the following codes:

```{shell}
yarn run prettier --write .
git add .
git commit -m "messages"
git push
```

Wait for 5 minites and the website will be updated.

$$ \alpha + \beta = 1 $$. You can never know it.
