# Biodiversitix Reference Database

Public distribution endpoint for the global reference database used by Biodiversitix.

The Biodiversitix application source code and database-build pipeline are maintained separately and are not published in this repository.

## Distribution model

The small `database_manifest.json` file identifies the current supported reference-database release.

Database archives are distributed exclusively as GitHub Release assets and are not committed to this Git repository.

Current database release:

- Database version: `2026.08.2`
- Schema version: `2`
- Release tag: `reference-db-2026.08.2`
- Archive: `biodiversitix_reference_2026.08.2.zip`

## Integrity

Biodiversitix verifies downloaded releases using SHA-256 before installation and validates the SQLite database before activating it.

Database releases are versioned immutably. A modified database must receive a new database version and a new release tag.

## Data provenance

The Biodiversitix reference database is derived from global biodiversity and taxonomy reference sources including Catalogue of Life and NCBI Taxonomy.

Release-specific source versions and provenance should be retained with each database build.

This repository contains distribution metadata only; upstream datasets remain subject to their respective attribution, licensing, and usage terms.
