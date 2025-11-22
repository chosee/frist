# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Swiss legal deadline calculator based on the Swiss Civil Procedure Code (ZPO) Articles 142-145.

**Live Site**: https://frist.ch

## Deployment

Hosted via **Cloudflare Pages** with automatic deployment on push to main branch.

**Build configuration:**
- Build command: (none)
- Build output: (none)
- Root directory: `/`
- Build system version: v3

## Tech Stack

- **Frontend**: Vanilla HTML5/CSS3/JavaScript (no build step, single-page app)
- **Styling**: CSS Variables, Font Awesome icons
- **No backend** - all calculation logic runs client-side

## Features

- Calculate legal deadlines per Swiss ZPO
- Considers weekends and Swiss public holidays
- Handles court recess periods (Gerichtsferien)
- Multi-language support

## Legal Basis

The calculator implements deadline rules from:
- Art. 142 ZPO - General deadline rules
- Art. 143 ZPO - Compliance with deadlines
- Art. 144 ZPO - Extension of deadlines
- Art. 145 ZPO - Court recess periods

## Project Documentation

The `/memory-bank/` directory contains structured context documentation:
- `projectbrief.md` - Legal requirements and Swiss ZPO rules
- `techContext.md` - Technical stack details
- `systemPatterns.md` - Architecture patterns
- `activeContext.md` - Current development state
- `progress.md` - Development milestones
