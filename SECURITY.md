# Security policy

Omarchy Silicon is in active development. Current repositories contain foundation and in-progress work; no board is currently supported or qualified, and there is no supported installer or release. Do not test an unreviewed artifact on hardware or include secrets in a report.

## Private reporting

Use the central platform repository's private vulnerability advisory interface: https://github.com/omarchy-silicon/omarchy-apple-platform/security/advisories/new

Maintainers must verify that private vulnerability reporting is enabled for that repository before treating the workflow as active. Until it is verified, still use the exact private advisory interface above and do not publish vulnerability details in an issue, discussion, pull request, or public log. If the interface is unavailable, stop and request maintainer assistance through the GitHub repository without disclosing the vulnerability publicly.

Please include the affected repository and revision, a concise impact statement, reproduction steps that do not destroy data, and any proposed mitigation. Redact credentials, personal data, device identifiers, and private URLs.

## Scope

Security reports may include the installer, boot and update paths, release artifacts, package or firmware provenance, CI workflows, credential handling, and support tooling. A normal reproducible bug belongs in the applicable repository's issue workflow after removing sensitive information.

## Disclosure

Please do not disclose a vulnerability publicly until maintainers have acknowledged it and agreed on a disclosure plan. The project cannot promise a response time or a release timeline while the program remains in foundation and qualification work.
