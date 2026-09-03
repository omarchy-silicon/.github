# Omarchy Silicon

Omarchy Silicon is the engineering program for bringing Omarchy to Apple Silicon across all present and future M-series chips and every materially distinct board or hardware profile.

## Current status

This program is in active development. The current repositories contain foundation and in-progress work only. No Apple Silicon board is currently supported or qualified by Omarchy Silicon. M1 and M2 are the first staging targets, not a support guarantee, and newer M-series work must not be inferred from chip-name recognition or source-code presence.

There is currently no supported Omarchy Silicon installer, release image, or recovery release. Do not treat a successful build, a green CI check, a boot into a desktop, or a design document as support or qualification evidence.

## What support requires

Support is board-specific. A board can be called supported only after the relevant kernel, device tree, firmware, boot chain, graphics, installer, rollback, and release artifacts have passed the project gates and physical qualification for that exact board and profile. Reports must identify the exact machine, chip variant, board/profile, firmware, and tested artifact.

The central platform repository records the contracts and evidence for this work: https://github.com/omarchy-silicon/omarchy-apple-platform

## Contributing

Read the contribution and support policies in this repository before opening work. Engineering reports belong in the central platform repository once its issue workflow is enabled; use the templates there and include reproducible evidence.

## Attribution

This program builds on the work of the Linux, Asahi, U-Boot, Mesa, and other upstream communities. Each downstream repository retains its applicable upstream copyright and license notices.
