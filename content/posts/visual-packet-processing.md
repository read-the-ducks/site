---
date: '2024-11-16T23:39:11+01:00'
title: 'Visual Packet Processing'
subtitle: ""
toc: true
bold: true
math: true
draft: true
---


Update 14/12: Live display of packet information would require collecting per-buffer VPP information, which is quite expensive.. Start with displaying trace buffer information with dedicated commands ? e.g. show trace paths..

Could be used to display packet paths available in the trace..
Could be used to generate .dot file to represent the different paths in the trace..

- VPP graph visualization Utility
Real-time.. Companion tool.. Analysis..
- Existing tools
CLI commands.. graphviz.. vpptop..
- Challenge #1 - Collecting real-time data
vlib_buffer trajectory.. VPP callbacks..
- Challenge #2 - Publishing
Plugin.. enable.. disable..
Architecture..
Utilising Graphviz