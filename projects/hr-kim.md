# HR-KIM

> Independent HR, contracts, attendance, and payroll platform

[← Back to profile](../README.md) · [View screenshots and workflows](https://phamthanhvu-portfolio.vercel.app/projects/kim-hr)

## Overview

A dedicated HR application separated from the project-management product so payroll policies, contracts, and sensitive HR permissions can evolve independently.

## Product scope

- Read-only HR feed integration with Kimcom PM
- SSO-style credential verification without storing PM App passwords or tokens
- Four permission levels: HR admin, HR staff, accountant, and viewer
- Employee profiles, positions, allowances, contracts, and Excel imports
- Attendance conversion, payroll grids, payroll-period closing, and immutable snapshots
- Contract and acceptance-document generation in DOCX format
- Warnings when issued documents become inconsistent with updated payroll data
- Explicit failure handling when the upstream PM App is unavailable

## Architecture and stack

- **Frontend:** React, Vite
- **Backend:** Laravel 11 with an independent database and protected HR feed
- **Quality:** 95 tests — 77 backend and 18 frontend

## Role

**Full-Stack Developer** — building the application boundary, authentication and authorization, HR workflows, payroll integrity rules, document generation, and automated tests.

> This case study excludes employee records, salary data, credentials, and private source code.
