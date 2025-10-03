# Awesome Sage 50 Canada [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated list of libraries, tools, guides, and datasets for working with **Sage 50 (Canadian Edition)**.

[![awesome-lint](https://github.com/bookkeepingfromgravelhill/awesome-sage50-canada/actions/workflows/awesome-lint.yml/badge.svg)](https://github.com/bookkeepingfromgravelhill/awesome-sage50-canada/actions/workflows/awesome-lint.yml)
[![markdownlint](https://github.com/bookkeepingfromgravelhill/awesome-sage50-canada/actions/workflows/markdownlint.yml/badge.svg)](https://github.com/bookkeepingfromgravelhill/awesome-sage50-canada/actions/workflows/markdownlint.yml)
[![link-check](https://github.com/bookkeepingfromgravelhill/awesome-sage50-canada/actions/workflows/link-check.yml/badge.svg)](https://github.com/bookkeepingfromgravelhill/awesome-sage50-canada/actions/workflows/link-check.yml)
[![CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](LICENSE)

Pull requests welcome! Read **CONTRIBUTING.md**.

## Contents

- [Libraries & ODBC](#libraries--odbc)

- [Bank File Converters](#bank-file-converters)

- [Datasets & APIs](#datasets--apis)

- [Guides & Notes](#guides--notes)

- [Community](#community)

- [Notes](#notes)

## Libraries & ODBC

- **smart-io/php-sage50** — PHP lib for *Sage50 Canadian Edition*. https://github.com/smart-io/php-sage50

- **Boran/sage** — PHP/ODBC read-only explorer & dumps (pattern works with Sage 50 CA). https://github.com/Boran/sage

- **Official help: Connect via ODBC** — https://help-sage50.na.sage.com/en-us/2024/Content/Getting_Started/COMPANY/Connecting_to_your_data_using_ODBC.htm

- *(Note)* Write access typically needs Sage 50 SDK/Partner program; ODBC is generally read-only. Community context: https://communityhub.sage.com/us/sage50_us/f/software-development-kit-sdk/121889/i-need-write-access-to-the-sage-50-database-to-integrate-a-3rd-party-app

## Bank File Converters

- **ofxtools** (Python OFX parse/generate). https://github.com/csingley/ofxtools • Docs: https://ofxtools.readthedocs.io/en/latest/installation.html

- **ofxstatement** (CLI, plugins, CSV→OFX). https://github.com/kedder/ofxstatement

- **ofxparse** (Python). https://github.com/jseutter/ofxparse

- **asgrim/ofxparser** (PHP). https://github.com/asgrim/ofxparser

- **csv2qif-py** (Python CSV→QIF). https://github.com/fabrizionastri/csv2qif-py

- **csv2qif-ts** (TypeScript CSV→QIF). https://github.com/fabrizionastri/csv2qif-ts

## Datasets & APIs

- **Canadian Sales Tax (JSON)** — https://github.com/wiredmax/canadian-sales-tax

- **Canada Sales Tax API** — https://github.com/jpmurray/canada-sale-tax-api • https://salestaxapi.ca/

- **Bank of Canada Valet API** — https://www.bankofcanada.ca/valet/ • Python: https://github.com/tylercroberts/pyvalet • R: https://cran.r-project.org/web/packages/valet/index.html

- **Government-wide Chart of Accounts (GoC)** — Overview: https://www.tpsgc-pwgsc.gc.ca/recgen/pceaf-gwcoa/index-eng.html

## Guides & Notes

- **CRA – RC4022 (GST/HST registrants)** — https://www.canada.ca/en/revenue-agency/services/forms-publications/publications/rc4022.html

- **CRA – RC4058 (Quick Method)** — https://www.canada.ca/en/revenue-agency/services/forms-publications/publications/rc4058.html

- **CRA – T4002 (Self-employed income)** — https://www.canada.ca/en/revenue-agency/services/forms-publications/publications/t4002.html

- **CRA – T4127 (Payroll formulas)** — https://www.canada.ca/en/revenue-agency/services/forms-publications/payroll/t4127-payroll-deductions-formulas/t4127-jan.html

- **CRA – T4032 (Payroll tables)** — https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/payroll/t4032-payroll-deductions-tables.html

- **ODBC version gotchas** — 32/64-bit mismatch and versioning threads (example): https://communityhub.sage.com/ca/sage_50/f/general-discussion/155896/sage-50-odbc-connection

- **GoC – Government‑wide Chart of Accounts** — https://www.tpsgc-pwgsc.gc.ca/recgen/pceaf-gwcoa/index-eng.html

## Community

- **Sage City (Canada)** — https://communityhub.sage.com/ca/sage_50/

- **YouTube: Sage 50 Canada ODBC DSN setup** — https://www.youtube.com/watch?v=JjD8KBS7zmE

### Notes

- ODBC version mismatches: https://www.reddit.com/r/Sage/comments/1iubfli/sage50_2025_obdc_connector/

- Canadian compounding sanity‑check: GnuCash News highlights semi‑annual compounding for Canadian loans. https://www.gnucash.org/news.phtml

