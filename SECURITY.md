# Security Policy

This collection is a community project in the [chocolatey-community](https://github.com/chocolatey-community) organization. It is not a Chocolatey Software product and is maintained by the community on a best-effort basis.

## Supported Versions

Only the latest released version of the `chocolatey.chocolatey` collection receives security fixes.

## Where to Report

Please do not report security issues in public GitHub issues, discussions or pull requests.

### Vulnerabilities in This Collection

Examples:

- Credentials, API keys or source passwords exposed in task output, logs or module return values
- Unsafe handling of module parameters, such as command injection
- Insecure defaults set by the collection's modules

Report these privately using [Report a vulnerability](https://github.com/chocolatey-community/chocolatey-ansible/security/advisories/new) on this repository's **Security** tab. The collection's maintainers will review the report on a best-effort basis. There is no guaranteed response time and no bug bounty.

### Vulnerabilities in Chocolatey Products

If the issue is in a Chocolatey Software product, and this collection only exposes it, follow the [Chocolatey security disclosure process](https://docs.chocolatey.org/en-us/information/security).

### Not Sure Which?

Report it here using **Report a vulnerability**. If the maintainers find the cause is in a Chocolatey product, they will pass it on through the Chocolatey disclosure process.

## What to Include

- The collection version, plus the Ansible and Chocolatey product versions.
- The module and parameters involved.
- Steps to reproduce, or a minimal playbook.
- The impact you expect an attacker could achieve.
