# uden - Unsloppified Den.

A fork of [den](https://github.com/denful/den) you can actually use.

## Overview

The upstream has seen a change in direction towards word salad features of marginal utility,
AI-generated patches which introduce breaking changes in minor revisions, and significant
performance drops simply from having to fetch all of the "gen" infrastructure. It additionally
suffers from documentation that focuses on the technical details far more than actual practical
usage of the framework, forcing users to reverse-engineer the expectation of the framework for
anything more complicated than an Alice and Bob example. This fork aims to fix those issues:

- The upstream is monitored for features introduced in commits.
  - If the feature is useful and handmade, the implementing commit is cherry-picked.
  - If the feature is useful but uses LLM-generated code, an issue is made to reimplement
    it by hand.
- The documentation will be revised to give more complete examples and guidance on using the tech.
  The features den offers are genuinely great for multi-host and / or multi-user configurations,
  though that may be difficult to pick up from the upstream docs.
