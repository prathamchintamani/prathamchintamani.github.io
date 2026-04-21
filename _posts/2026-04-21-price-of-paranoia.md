---
title: Why AI Cooperation Fails (And How We Fixed It)
date: 2026-04-21 18:00:00 +0530
categories: [Research, RL]
tags: [MARL, Risk-Sensitive RL]
---


In our latest paper, **"The Price of Paranoia,"** (accepted to AAMAS 2026) we found that AI agents often stop working together because they are *too* cautious. 

When one agent explores, the other sees it as betrayal. This triggers a "paranoia" cycle where everyone starts defecting towards a suboptimal nash equilibrium.

We fixed this with **RATTL**, a lightweight trust mechanism that helps agents distinguish between "partner noise" and "actual betrayal."

Check out the full paper here: https://arxiv.org/abs/2604.15695v1
