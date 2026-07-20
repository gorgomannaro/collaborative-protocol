<p align="center">
  <img src="cover.png" alt="Collaborative Protocol" width="900">
</p>

# Collaborative Protocol

A lightweight protocol for more rigorous, context-aware human–AI collaboration.

## Overview

The Collaborative Protocol is a behavioral framework designed to improve technical collaboration between humans and Large Language Models.

Rather than prescribing rigid workflows, it introduces a small set of operational heuristics—called **Rumble Strips**—that help detect common reasoning failures before they become costly mistakes.

The protocol focuses on improving collaboration by encouraging participants to:

- verify context before reasoning;
- distinguish evidence from inference;
- make assumptions explicit;
- keep attention on the real problem instead of its proxies;
- apply rigor proportionally to risk;
- periodically audit the collaboration process itself.

## Why

Many failures in AI-assisted engineering are not caused by a lack of intelligence, but by predictable collaboration failures.

The Collaborative Protocol aims to reduce those failures while remaining lightweight enough to be used during everyday technical work.

## Repository

This repository contains the current specification of the Collaborative Protocol.

## License

MIT License.

## How GPT-5.6 and Codex Were Used

The initial version of the Collaborative Protocol was developed using GPT-5.5, before GPT-5.6 became available.

After the release of GPT-5.6, the protocol was subjected to an adversarial review. GPT-5.6 was used as an independent technical reviewer to challenge the protocol's assumptions, identify inconsistencies, search for regressions, and stress-test its internal logic. The protocol was subsequently refined based on this review process.

Codex was used to evaluate the protocol during implementation work on independent software projects. These practical sessions were used to assess whether the protocol improved context preservation, decision quality, and technical collaboration during real development tasks. Feedback from these evaluations informed refinements to the published specification.
