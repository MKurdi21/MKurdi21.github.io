---
title: "Security Analysis of Web AI Agents"
excerpt: "Research on security risks in browser-based and tool-using AI agents."
collection: portfolio
permalink: /portfolio/agentic-ai-web-agent-security/
order: 1
---

This project reflects Mohammed Alkurdi's current Ph.D. research direction under Professor Junjie Zhang. It focuses on web and browser-based AI agents that interact with pages, tools, files, code, credentials, and external services.

## Problem

Web and browser-based AI agents introduce security risks that differ from standalone language-model use. They can read untrusted webpages, follow instructions embedded in external content, operate tools, handle credentials, and perform multi-step workflows where a single unsafe action can have downstream consequences.

This research studies prompt injection, external-content manipulation, unsafe tool use, credential exposure, weak separation between web content and privileged tools, and security evaluation for long-horizon agent workflows.

## My Role

Mohammed Alkurdi is developing this as an ongoing Ph.D. research direction. His role includes literature review, problem framing, mapping web-agent risks to evaluation scenarios, and preparing controlled security analyses for browser-based and tool-using agents.

## Approach

The work begins from a structured review of web-agent, browser automation, website traversal, benchmark, and web-agent safety/security literature. It uses that review to identify security-relevant workflows, threat surfaces, evaluation gaps, and safe ways to study agent behavior around untrusted web content and privileged actions.

The current public research-mapping work organizes papers and systems by benchmark families, browser-control interfaces, website traversal tasks, scraper-generation settings, safety/security testbeds, and prompt-injection or malicious-webpage threat models. It also tracks gaps around live-web evaluation, privacy leakage during browsing, containment/sandboxing, and the boundary between agent planning and tool execution.

## Outputs and Evidence

- Current Ph.D. research notes and evaluation planning are in preparation.

## Related Public Artifacts

- [Agentic-Web-Crawlers](https://github.com/MKurdi21/Agentic-Web-Crawlers) — Mohammed's authored literature-synthesis and research-mapping resource on web agents, browser automation, website traversal, web-agent benchmarks, and web-agent safety/security.
- [Agentic-AI-Security-Papers](https://github.com/MKurdi21/Agentic-AI-Security-Papers) — Mohammed's authored curated literature resource focused on security and privacy challenges in agentic AI systems.

The public repositories include paper inventories, problem/approach matrices, gap-analysis notes, reading-order/citation-cluster notes, and metadata-verification records. They support literature review and problem framing rather than representing a finalized experimental system.

## Current Status

Ongoing Ph.D. research.

## Security and Ethics

The public description intentionally omits operational attack steps, credential-handling details, and instructions that would enable unsafe use of web agents. Public artifacts focus on literature synthesis, risk mapping, and defensive evaluation framing.
