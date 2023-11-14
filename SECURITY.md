# Security Policy

## Supported Versions

As outlined by our [Repository requirements](https://github.com/security-as-code/.github/blob/main/CONTRIBUTING.md#repository-requirements), security-as-code artifacts adhere to semantic versioning and include meaningful change logs. The security-as-code repo includes [Document status](link) definitions, which are used to indicate the stability level of each specification section.

## Reporting a Vulnerability

If you find something suspicious and want to report it, we'd really appreciate it!

### Ways to report

- Many repositories provide a way to report vulnerabilities privately to maintainers through a GitHub issue. This can be done by selecting the `Report a vulnerability` template when creating a new issue. Only report vulnerabilities using this template, so the issue can be addressed before public disclosure.
- Send a message to [MAILINGLIST](link). This option should only be used if the vulnerability template is unavailable.

## Vulnerability Policies

Securiy-as-code uses ?? and ?? vulnerability scans to make sure we minimize vulnerabilities in our dependencies and get notified of new vulnerabilities.

There are many situations where a vulnerability does not affect a particular dependency because of how the vulnerable package is used. In that situation, the package authors may choose to stay at the current version rather than bumping the dependency, leading to a warning in the vulnerability scans but no actual vulnerability.
