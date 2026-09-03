KS-Semilla Ecosystem Versions

Public version metadata for the KS-Semilla PHP System Builder ecosystem.

This repository provides the official version index used by KS-Semilla development tools to identify and compare the current stable and prerelease versions of KS-Semilla components and Nutrients.

The public SSOT is:

ecosystem_versions.json

KS-Semilla tools use this metadata to determine whether a local installation is up to date, ahead of the official release, missing version metadata, or running an older published component version.

KS-Semilla

KS-Semilla is a PHP System Builder designed to provide a transparent, maintainable and reusable foundation for building custom PHP systems and applications.

Official website:

https://ks-semilla.com

Repository Scope

This repository contains version metadata only.

It does not contain:

KS-Semilla source code

Nutrient source code

private development tools

deployment credentials

automatic update mechanisms

The repository exists only as the public version SSOT for the KS-Semilla ecosystem.

Ecosystem Metadata

The file ecosystem_versions.json may contain official version information for:

KS-Semilla

KS-Semilla Nutrients

other versioned components that belong to the KS-Semilla ecosystem

Example:

{
    "components": {
        "ks-semilla": {
            "stable": {
                "version": "1.1.0"
            }
        },
        "nt-example": {
            "stable": {
                "version": "1.0.0"
            }
        }
    }
}

Maintained by KhamaleonLab

KS-Semilla is created and maintained by KhamaleonLab, a software development studio focused on custom systems, automation, digital infrastructure and maintainable web solutions.

https://khamaleonlab.com

KS-Semilla Ecosystem Versions
Official public version metadata for the KS-Semilla ecosystem.
