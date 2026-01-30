![Version](https://img.shields.io/endpoint?url=https://shield.abappm.com/github/abapPM/ABAP-Mimetypes/src/%2523apmg%2523cl_mimetypes.clas.abap/c_version&label=Version&color=blue)

[![License](https://img.shields.io/github/license/abapPM/ABAP-Mimetypes?label=License&color=success)](https://github.com/abapPM/ABAP-Mimetypes/blob/main/LICENSE)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg?color=success)](https://github.com/abapPM/.github/blob/main/CODE_OF_CONDUCT.md)
[![REUSE Status](https://api.reuse.software/badge/github.com/abapPM/ABAP-Mimetypes)](https://api.reuse.software/info/github.com/abapPM/ABAP-Mimetypes)

# Mimetypes

Class to initialize the table MIMETYPES, which is used by the SAP Web Repository (transaction SMW0).

NO WARRANTIES, [MIT License](https://github.com/abapPM/ABAP-Mimetypes/blob/main/LICENSE)

## Usage

| Method        | Description                        |
|---------------|------------------------------------|
| get_all       | List of mimetypes with extensions  |
| get_extension | Comma-separated list of extensions |
| init          | Update `mimetypes` database table with missing extensions |

## Prerequisites

SAP Basis 7.50 or higher

## Installation

Install `mimetypes` as a global module in your system using [apm](https://abappm.com).

or

Specify the `mimetypes` module as a dependency in your project and import it to your namespace using [apm](https://abappm.com).

## Contributions

All contributions are welcome! Read our [Contribution Guidelines](https://github.com/abapPM/ABAP-Mimetypes/blob/main/CONTRIBUTING.md), fork this repo, and create a pull request.

You can install the developer version of ABAP Mimetypes using [abapGit](https://github.com/abapGit/abapGit) by creating a new online repository for `https://github.com/abapPM/ABAP-Mimetypes`.

Recommended SAP package: `/APMG/MIMETYPES`

## About

Made with ❤ in Canada

Copyright 2026 apm.to Inc. <https://apm.to>

Follow [@marcf.be](https://bsky.app/profile/marcf.be) on Bluesky and [@marcfbe](https://linkedin.com/in/marcfbe) or LinkedIn
