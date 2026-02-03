# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a **GitHub profile README repository** for Andrés Santana (ruloCode). It displays a personalized README on the GitHub profile page. There is no application code, build system, or runtime.

## Repository Structure

- `README.md` — Profile content displayed on GitHub (markdown with badge images from shields.io and github-readme-stats)
- `.github/workflows/wakatime-coding-stats.yml` — GitHub Action that updates README daily at midnight UTC with WakaTime coding statistics (requires `WAKATIME_API_KEY` secret)
- `LICENSE` — MIT License

## Key Details

- The WakaTime workflow uses `athul/waka-readme@master` and custom block characters (`⣀⣄⣤⣦⣶⣷⣿`)
- README badges link to social profiles: Instagram, LinkedIn, Twitch, Twitter, YouTube (all under "rulocode" handle)
- Tech stack highlighted: React, Next.js, TypeScript, GraphQL, Apollo, Vercel
