# Open Licensing Archive

A source-first archive of software licensing history, with an initial focus on Unix, Unix-like systems, workstation vendors, university releases, early open source, free software, and later commercial open source licensing models.

The project is not intended to be a legal advice site or a substitute for SPDX, OSI, FSF, ScanCode, or Software Heritage. Its purpose is historical: to collect, classify, compare, and explain the licensing documents that shaped how source code moved from laboratories, universities, hardware vendors, workstation companies, startups, and free software projects into the modern open source ecosystem.

## Initial focus

The first major collection phase focuses on 1970s, 1980s, 1990s, and 2000s Unix-type licensing.

Core targets include:

- AT&T Bell Labs / Western Electric / USL / Novell Unix licensing
- University of California Berkeley BSD releases and Regents of UC license variants
- University of Utah / Flux / Mach / BSD-derived research operating-system work
- Sun Microsystems, Solaris, OpenSolaris, Java-related and workstation-era licenses
- SCO, Santa Cruz Operation, Caldera, UnixWare, OpenServer, and related Unix licensing material
- SGI, IRIX, XFS, OpenGL, Open Inventor, and workstation-source releases
- NeXT, NEXTSTEP, OpenStep, Darwin lineage, and Apple Public Source License material
- IBM AIX, Jikes, Eclipse/CPL/EPL lineage, and corporate open source releases
- GNU, GPL, LGPL, AGPL, GFDL, Autoconf exception, Classpath exception, and FSF licensing material
- MIT, X11, Athena, Kerberos, CMU, Mach, and other university/network computing licenses
- Apache, Mozilla, Netscape, Perl/Artistic, Python, PostgreSQL, Tcl/Tk, Sendmail, OpenSSL/SSLeay, and other 1990s/2000s infrastructure licenses

The archive should preserve both canonical license texts and the surrounding historical context: release notes, source headers, notices, READMEs, distribution terms, patent clauses, advertising clauses, contributor agreements, source availability terms, and vendor explanations.

## Modern comparison scope

The archive should also include modern licensing forms where they help explain the historical development of open licensing:

- Apache-2.0, MPL-2.0, EPL-2.0, CDDL, Unicode, ISC, 0BSD, Blue Oak, PostgreSQL, BSL/Business Source License, SSPL, Elastic License, PolyForm, Commons Clause, Server Side Public License, source-available terms, open core licensing, and cloud-era anti-competition clauses.
- Data, documentation, hardware, model, and AI licensing where the comparison is useful, including Creative Commons, CDLA, OpenRAIL-style model licenses, and dataset licensing.

Modern entries should be treated as comparison material unless they have a direct historical link to Unix, workstation computing, free software, open source, or source-available business models.

## Repository structure

Suggested layout:

```text
archive/
  1970s/
  1980s/
  1990s/
  2000s/
  modern/

families/
  att-unix/
  bsd/
  gnu/
  sun/
  sco-caldera/
  sgi/
  next-apple/
  ibm-eclipse/
  mit-x11-athena/
  mozilla-netscape/
  apache/
  perl-python-tcl/
  postgres/
  source-available/

data/
  collection-priorities.yml
  schema.yml
  sources.yml

docs/
  collection-strategy.md
  provenance.md
  taxonomy.md
  research-notes.md
```

## Entry model

Each archived license or licensing document should eventually have a metadata record. A good entry should include:

- `title`
- `short_name`
- `spdx_id`, where one exists
- `family`
- `organisation`
- `jurisdiction`
- `first_known_date`
- `era`
- `source_url`
- `archive_url`
- `source_type`
- `text_status`
- `redistribution_status`
- `osi_approved`
- `fsf_free`
- `gpl_compatible`
- `license_style`
- `key_terms`
- `historical_notes`
- `related_licenses`
- `verification_notes`

## Collection rules

1. Prefer primary sources over summaries.
2. Keep exact provenance for every text.
3. Preserve original spelling, punctuation, section numbering, and warranty disclaimers.
4. Record whether a file is a canonical license, source-tree notice, README condition, manual restriction, press release, FAQ, or later commentary.
5. Do not silently normalise historic documents into modern SPDX form.
6. Where the archive cannot safely redistribute full text, keep metadata and source pointers instead.
7. Distinguish open source, free software, source-available, shared-source, research-only, educational, evaluation, binary-only, and proprietary-but-source-disclosed terms.

## Useful external baselines

This archive should interoperate with, but not merely duplicate:

- SPDX License List
- Open Source Initiative license list
- Free Software Foundation license commentary
- ScanCode LicenseDB
- Software Heritage
- Debian license and DFSG discussions
- historical vendor source releases and archived documentation

## Status

Early-stage archive. The immediate objective is to build the taxonomy, seed the priority list, and create repeatable metadata conventions before bulk-adding texts.
