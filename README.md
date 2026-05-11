# What is this?

[![Release](https://github.com/amentumcms/Collector-Redhat-Hardened/actions/workflows/collect.yml/badge.svg?branch=main)](https://github.com/amentumcms/Collector-Redhat-Hardened/actions/workflows/collect.yml)

This is a project that automatically collects artifacts to ease in air-gapped transfer from the internet.

It runs actions on Push or on the first of the month and creates a release.

In this case, it collects the source code repositories and the associated container images via skopeo for:

- Redhat Secure Registry Helm Charts
- Redhat Secure Registry Hardened container image
