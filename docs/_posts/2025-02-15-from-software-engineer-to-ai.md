---
layout: post
title: "From Software Engineer to AI Engineer"
date: "2025-02-15 01:24:00 -0000"
author: jQN
category: ai software engineering
tags: ai software engineerirng
excerpt_separator: <!--more-->
---

Create and deploy AI-powered applications from scratch.

<!--more-->

## Setting Up Your Coding Environment

## Prerequisite tools

We need to have Bun, and UV, the python package manager, installed.

### UV Installation

Run this command:

```
curl -LsSf https://astral.sh/uv/install.sh | sh

# Output should look like this if you're on mac
# downloading uv 0.5.18 aarch64-apple-darwin
# no checksums to verify
# installing to /Users/youusername/.local/bin
# uv
# uvx
# everything's installed!
```

Test that it worked by running uv --version. It should output the following:

uv 0.5.18 (27d1bad55 2025-01-11)

That's all we need to do with UV for now.

Bun Installation

Run this command to install bun:

```
curl -fsSL https://bun.sh/install | bash

# This command should output:
# ######################################################################## 100.0%
# bun was installed successfully to ~/.bun/bin/bun
# Run 'bun --help' to get started
```

You can run bun --help to verify that it installed correctly.

This is all you should need to get started with the course, so let's get to scaffolding everything!

## Scaffolding the Project
