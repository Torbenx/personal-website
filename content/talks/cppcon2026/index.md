---
title: "Writing High Performance Parsers Using State Machines"
date: 17 Sep 2026
description: ""
repository: "https://github.com/Torbenx/highperformanceparsers-cppcon2026"
slides: "https://cppcon2026.trivial.ly"
slidesPdf: "https://cppcon2026.trivial.ly/slides.pdf"
schedule: "https://cppcon2026.sched.com/event/2RT6F/writing-high-performance-parsers-using-state-machines"
where: "CppCon 2026"
---

## Abstract

Starting from the simple objective of writing an optimized lexer we will grapple with their fundamental performance factor: branch prediction. We will investigate how lookup tables can improve (or hurt) the CPUs prediction capabilities with some unexpected results. Over time our design evolves by combining parsing and lexing into a single step in a way that is as fast as just a standalone lexer. A central aspect of the design will be a primitive parsing state machine from which the parser source code is generated.

After the talk attendees will have a better understanding of some advanced branch prediction techniques and should have some new ideas for their present or future parsing endeavors.
