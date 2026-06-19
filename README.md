# Fantasia

**Local-first AI operations desktop for safe creative automation.**

Fantasia is a desktop control room for builders who want AI tools to operate with receipts, rollback, and clear authority boundaries. It coordinates local services, operator queues, Codex/OpenClaw handoffs, FVE visual-engine workflows, and COAI / WordPress publish-readiness checks without turning every action into an unsafe live write.

## What It Does

- Starts scoped local work sessions.
- Shows local service and queue state.
- Routes handoffs between Faith, Codex, OpenClaw, and local operator lanes.
- Provides an FVE Workbench for image-review and website-change prep.
- Checks COAI / WordPress readiness while redacting credentials.
- Records checkpoints, task packets, verification runs, patch receipts, and rollback paths.

## Why It Exists

AI work is becoming too important to live only in chat windows. Builders need a place where AI can help operate real workflows while preserving privacy, authorship, and production safety.

Fantasia is built around a simple rule:

> AI can move faster when the system has memory, receipts, and brakes.

## First Use Case: FVE Website Visual Operations

Fantasia's first focused workflow is helping operate the FAŸTH Visual Engine:

- review live website images
- keep passing images in place
- find weak, repeated, broken, generic, or line-drawn assets
- prepare replacements
- map candidates to target slots
- check COAI / WordPress publish readiness
- keep production publish guarded until rollback, target slots, typed slug, and production status are clean

Fantasia does not bypass FVE. FVE remains the source of truth for visual decisions and guarded publishing.

## Safety Model

Fantasia is local-first by default:

- no direct WordPress publish from Fantasia
- no credential values in UI logs
- no DNS/auth/plugin changes by default
- no social posting without approval
- no public dashboard exposure by default
- no hidden cloud telemetry
- no production writes without a specific guarded adapter

## Current Status

Fantasia is in local preview. The current docs and deck describe the working product direction and investor story. Public launch should happen private-first after a final secret scan, private-path scan, and release review.

## License and Commercial Use

Fantasia core is proprietary commercial software owned/licensed through XXYYZZ Society LLC. The public repository is a docs-first product surface for review, investor diligence, and evaluation; it is not an open-source release of the desktop app, FVE adapters, COAI publishing workflow, or private automation system.

Commercial use requires written permission or a signed license from XXYYZZ Society LLC.

Creator/founder: Faith Cheltenham.

No public license is granted. No training use, redistribution, commercial reuse, hosting, sublicensing, reverse engineering, or implied permission is granted.

## Start Here

- [Launch README](README_LAUNCH.md)
- [Project Brief](docs/PROJECT_BRIEF.md)
- [Product Screenshots](docs/PRODUCT_SCREENSHOTS.md)
- [Workflow Maps](docs/WORKFLOW_MAPS.md)
- [Commercial Use Policy](docs/COMMERCIAL_USE_POLICY.md)
- [Public / Private Boundary](docs/PUBLIC_PRIVATE_BOUNDARY.md)
- [GitHub Links](docs/GITHUB_LINKS.md)

## Investor Share Pack

- [Fantasia Investor Pack Folder](https://drive.google.com/drive/folders/1U1Y4DqxW28w3nV1hJwACnqExh8ALKL_Z)
- [Updated Investor Pack Zip](https://drive.google.com/file/d/1-JutItFU37CcTG6TlfekBij_3zjaD20y/view?usp=drivesdk)
- [Pitch Deck HTML Preview](https://drive.google.com/file/d/1Dd4AbA1hH9l0gUlP8pts_0umWx3JdZi3/view?usp=drivesdk)
- [Brand Board HTML Preview](https://drive.google.com/file/d/1FTcDc_bMEkuA8MdaF9lBWZRDoejlo4MB/view?usp=drivesdk)
- [FaithCheltenham WordPress Demo HTML Preview](https://drive.google.com/file/d/1HuvAF0A0bjvXE4_B8hIciLwopLoe7x1j/view?usp=drivesdk)

Drive upload succeeded. General sharing may still need to be turned on in Google Drive UI if investors are outside the account's permitted domain.

## Keep Private

- Fantasia core source
- FVE production adapters
- COAI credentials or WordPress credentials
- code-signing materials
- private receipts, queue state, rollback snapshots, and customer/project data

## Investor Story

Fantasia is not another AI chat app. It is an operations layer for owner-controlled AI work: a desktop cockpit that helps practical automation become inspectable, reversible, and commercially usable.
