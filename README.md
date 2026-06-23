# destiny-engine — BaZi Four Pillars + Western Astrology dual-core

> Precise BaZi birth chart analysis combined with Western astrology interpretation. Eliminates LLM calendar hallucinations by running dedicated calculation scripts for both systems.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
destiny-engine provides traditional Chinese BaZi (四柱八字) analysis enhanced with an optional Western astrology layer. Instead of letting the LLM estimate calendar conversions (a known error source), it always executes a Python script for BaZi calculation and an astrology library for the Western chart. Four analysis modes let users focus on Eastern, Western, dual-core, or relationship-specific readings. The skill references nine classical texts for BaZi interpretation and standard Ptolemaic rules for the Western layer.

## Features
- **Four modes** — pure BaZi, pure Western chart, dual-core (default), relationship special
- **Script-enforced accuracy** — never self-calculates; always execs Python for BaZi
- **References** — wuxing-tables.md, shichen-table.md, dayun-rules.md, classical-texts.md (9 classics), western-texts.md
- **Interactive** — collects name, gender, birth date (solar/lunar), time (optional), location

## Usage / Quick Start
Provide: name, gender, birth date (specify solar or lunar), birth time (optional), birth location.

## Trigger Keywords (OpenClaw)
算八字, 看八字, 四柱, 命盘, bazi, birth chart analysis, fortune telling, 算命

## Related Skills
- [bazi-master](https://github.com/NachaFromMars/bazi-master) — full-stack BaZi + Tarot + Zi Wei web app
- [ziwei](https://github.com/NachaFromMars/ziwei) — Zi Wei Dou Shu dedicated app

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
