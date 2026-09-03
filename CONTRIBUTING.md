# Contributing to Omarchy Silicon

Thank you for helping develop Omarchy on Apple Silicon. The target is all present and future Apple M-series chips and every materially distinct board or hardware profile. The project is in active development: current code is foundation and in-progress work, and no board is currently supported or qualified.

## Before opening work

There is no supported Omarchy Silicon installer or release yet. Do not install or distribute an artifact as an Omarchy Silicon release based on a branch, a successful build, a green CI result, or a desktop boot. M1 and M2 are first staging targets only; they are not a support guarantee.

For cross-repository contracts, read the central platform repository and its current issue tracker: https://github.com/omarchy-silicon/omarchy-apple-platform

## Evidence standard

Every hardware or compatibility claim must identify the exact Apple chip variant, machine and board/profile, firmware and boot artifacts, kernel and device-tree revisions, userspace or image revision, test date, and result. A chip-family token, architecture report, repository state, or source-code match is not qualification evidence.

Keep design, implementation, CI, delivery, and physical qualification claims separate. If a required artifact or test is unavailable, say so explicitly instead of inferring support.

## Pull requests

Use one focused change per pull request. Explain the contract being changed, the repositories and files affected, migration or rollback implications, and the exact checks run. Include negative or fail-closed cases for changes that gate installation, boot, updates, credentials, release, or support claims.

Do not include secrets, private vulnerability details, personal data, or unredacted machine logs. Report security issues using SECURITY.md.

## Upstream work

Some repositories are downstreams of upstream Linux, Asahi, U-Boot, Mesa, and related projects. Preserve upstream attribution and applicable license notices. Follow the contribution channel documented by the specific repository; this organization policy does not replace upstream submission rules.
