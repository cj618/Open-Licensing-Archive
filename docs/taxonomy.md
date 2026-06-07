# Licensing taxonomy

This project should classify documents by historical function, not just by whether they are open source in the modern sense.

## Top-level categories

### Proprietary source access

Licenses or agreements that permitted access to source code but did not permit general redistribution or community development.

Examples to investigate:

- AT&T / Western Electric Unix source licenses
- UNIX System Laboratories licensing material
- early commercial Unix vendor agreements
- university research access terms tied to AT&T code
- evaluation and educational Unix licenses

### Academic permissive

University-origin licenses that allowed broad reuse, often with warranty disclaimers and attribution terms.

Examples:

- BSD 4-clause, 3-clause, 2-clause, and related UC Regents notices
- MIT / X11
- CMU/Mach notices
- University of Utah Flux/OSKit-style licensing
- ISC
- PostgreSQL

### Free software copyleft

Licenses designed to protect software freedom through reciprocal licensing requirements.

Examples:

- GNU GPL family
- GNU LGPL family
- GNU AGPL family
- GFDL
- special exceptions including Autoconf and Classpath

### Weak copyleft / file-level copyleft

Licenses with reciprocal obligations that are narrower than GPL-style whole-work copyleft.

Examples:

- MPL
- CDDL
- EPL
- CPL
- LGPL, where treated functionally as weak copyleft

### Corporate open source

Licenses published by companies to manage commercial open source, standards participation, platform adoption, patent risk, or ecosystem control.

Examples:

- Sun Public License
- CDDL
- Apple Public Source License
- IBM Public License
- Common Public License
- Eclipse Public License
- Mozilla Public License
- Apache License

### Source-available / shared source

Terms that provide source visibility but do not meet standard open source or free software criteria.

Examples:

- Microsoft Shared Source-style licences
- Business Source License
- Server Side Public License
- Elastic License
- Commons Clause add-ons
- PolyForm licences
- vendor anti-cloud-service clauses

### Public domain / no-permission / ultra-permissive

Documents that disclaim copyright, dedicate works to the public domain, or provide near-zero restriction.

Examples:

- 0BSD
- Unlicense
- CC0
- historical public domain notices in university software

### Documentation, standards, data, hardware, and model licensing

Related licences outside the core software-license tradition.

Examples:

- Creative Commons
- GNU FDL
- Open Publication License
- Open Hardware Licence
- CDLA
- OpenRAIL-style model licences
- dataset usage terms

## Eras

### 1970s

Source licensing is dominated by research access, university relationships, hardware bundling, Bell Labs / Western Electric practices, and the pre-mass-market software industry.

### 1980s

Commercial Unix expands. BSD licensing becomes historically important. GNU and the Free Software Foundation emerge. Workstation vendors and network computing projects proliferate.

### 1990s

The modern open source settlement begins to form. Linux, BSD variants, Apache, Netscape/Mozilla, Perl, Python, Tcl/Tk, PostgreSQL, Sendmail, OpenSSL, and commercial Unix disputes become central.

### 2000s

Corporate open source matures. Apache-2.0, GPLv3, CDDL, EPL, MPL revisions, OpenSolaris, Java, Darwin, and cloud-era business pressures reshape licensing.

### Modern

Cloud services, open core, AI, data licensing, source-available terms, contributor agreements, patent retaliation, and anti-competitive use restrictions become key comparison points.

## Per-entry classification fields

Use the following fields consistently:

- `era`: one of `1970s`, `1980s`, `1990s`, `2000s`, `modern`
- `family`: primary lineage or vendor family
- `style`: `proprietary-source-access`, `permissive`, `strong-copyleft`, `weak-copyleft`, `corporate-open-source`, `source-available`, `public-domain`, `documentation`, `data`, `hardware`, `model`
- `status`: `canonical`, `variant`, `source-header`, `notice`, `agreement`, `faq`, `commentary`, `unknown`
- `redistribution`: `full-text-ok`, `metadata-only`, `unknown`, `do-not-redistribute`
- `verification`: `primary-source`, `reputable-secondary`, `unverified`, `needs-review`

## Families to prioritise

1. AT&T / Bell Labs / Western Electric / USL / Novell Unix
2. BSD / University of California / Berkeley CSRG
3. GNU / FSF
4. Sun / Solaris / OpenSolaris / Java
5. SCO / Santa Cruz Operation / Caldera / UnixWare / OpenServer
6. SGI / IRIX / XFS / OpenGL / Open Inventor
7. NeXT / Apple / Darwin / APSL
8. IBM / AIX / Jikes / CPL / EPL
9. MIT / X11 / Athena / Kerberos
10. CMU / Mach / Utah / Flux / OSKit
11. Mozilla / Netscape
12. Apache / NCSA / HTTP server lineage
13. Perl / Artistic / Python / Tcl/Tk / Ruby
14. PostgreSQL / Ingres / database systems
15. OpenSSL / SSLeay / cryptography licensing
16. Modern source-available and cloud-era licences
