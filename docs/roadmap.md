# Roadmap

## Stage 1: archive foundations

Status: in progress.

Objectives:

- Establish taxonomy and metadata fields.
- Define provenance and redistribution rules.
- Create family folders for the major Unix, free software, open source, and source-available licensing lineages.
- Seed the archive with high-value metadata entries before adding large volumes of text.

Deliverables:

- `README.md`
- `CONTRIBUTING.md`
- `docs/taxonomy.md`
- `docs/provenance.md`
- `docs/collection-strategy.md`
- `data/schema.yml`
- `data/collection-priorities.yml`
- `data/sources.yml`
- family `README.md` files
- first metadata-only entries

## Stage 2: Unix licensing spine

Build a verified set of entries covering the historical transition from source-access licensing to modern open source.

Priority families:

1. AT&T / Bell Labs / Western Electric / USL / Novell
2. BSD / University of California
3. GNU / FSF
4. MIT / X11 / Athena
5. CMU / Mach / University of Utah / Flux / OSKit
6. Sun / Solaris / OpenSolaris / Java
7. SCO / Caldera / UnixWare / OpenServer
8. SGI / IRIX / XFS / Open Inventor
9. NeXT / Apple / Darwin / APSL
10. IBM / AIX / CPL / EPL

## Stage 3: 1990s and 2000s infrastructure licences

Add entries for licences that defined open infrastructure and language ecosystems.

Priority families:

- Apache / NCSA
- Mozilla / Netscape
- Perl / Artistic
- Python
- Tcl/Tk
- PostgreSQL
- Sendmail
- OpenSSL / SSLeay

## Stage 4: modern comparison material

Add modern licensing forms that illuminate the historical shift from open source to source-available and open-core licensing.

Priority families:

- Business Source License
- Server Side Public License
- Elastic License
- Commons Clause
- PolyForm
- Functional Source License
- Creative Commons
- CDLA and data licences
- CERN Open Hardware Licence
- AI/model licences

## Stage 5: validation and tooling

Possible later work:

- schema validation script;
- generated index pages;
- SPDX cross-reference checker;
- OSI/FSF status checker;
- duplicate text detector;
- source URL availability checker;
- static site output;
- comparison tables by era, family, and licence style.

## Quality bar

A useful entry is not just a licence text. It should say what the document is, where it came from, whether it is canonical, whether it can be redistributed, and why it matters historically.
