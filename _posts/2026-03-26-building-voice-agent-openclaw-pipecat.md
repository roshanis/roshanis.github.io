---
title: "Building Voice Agent with OpenClaw and Pipecat"
date: 2026-03-26
categories: [ai, agents, voice]
tags: [openclaw, pipecat, codex, claude, realtime]
linkedin_activity_id: "7434047788751077376"
linkedin_url: "https://www.linkedin.com/posts/roshanvenugopal_this-weekend-was-fun-i-had-the-opportunity-activity-7434047788751077376-_8YV"
---

I joined the OpenClaw hackathon and built a voice-agent workflow around a real personal frustration: long hold times while calling my dentist.

I tested multiple approaches. OpenAI Realtime API worked, but quality was not good enough for my target experience. Vapi was strong for standalone voice agents, but it did not fit because my agent identity and orchestration already live inside OpenClaw.

I moved to Pipecat for deeper control. It was harder, but it aligned with production architecture requirements.

A practical workflow emerged:
- Codex for implementation and iteration
- Claude for review, challenge, and architecture critique
- Repeat until behavior and reliability improved

One key lesson: token limits can be useful guardrails when building with AI tools for long stretches.

I plan to open source the adapter-level work so teams can deploy voice agents directly in Telegram-based setups.

Source: [LinkedIn post](https://www.linkedin.com/posts/roshanvenugopal_this-weekend-was-fun-i-had-the-opportunity-activity-7434047788751077376-_8YV)
