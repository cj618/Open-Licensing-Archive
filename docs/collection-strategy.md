# Collection strategy

The archive should begin with a curated historical spine rather than indiscriminately collecting every license text available online.

## Phase 1: build the historical Unix spine

Focus on the licensing history that explains how Unix source moved between Bell Labs, universities, workstation vendors, commercial Unix companies, free software, and open source projects.

### 1970s

Priority questions:

- How was Unix source originally distributed to universities and research institutions?
- What role did Western Electric and AT&T licensing terms play?
- What restrictions existed on redistribution, publication, and derivative works?
- How did source availability differ from modern open source?

Targets:

- Research Unix source distribution terms
- Bell Labs / Western Electric notices
- early university Unix materials
- commentary from primary historical sources where original licences cannot be redistributed

### 1980s

Priority questions:

- How did BSD licensing diverge from AT&T-controlled Unix?
- How did workstation vendors handle source availability?
- How did the FSF and GNU licensing philosophy respond to proprietary Unix?

Targets:

- BSD 4.1/4.2/4.3-era notices
- UC Regents license variants
- MIT/X11 license material
- CMU Mach notices
- GNU Manifesto, GPLv1, LGPL predecessors, Emacs/GCC notices
- SunOS/SunView/Sun RPC licensing material where available
- early SCO/Xenix/Open Desktop material where available

### 1990s

Priority questions:

- How did the open source settlement form around BSD, GPL, Apache, Mozilla, Perl, Python, and Linux?
- What did commercial Unix vendors do as Linux and BSD grew?
- How did corporate source releases differ from community free software?

Targets:

- GPLv2 and LGPLv2.x
- Linux COPYING and early source-tree notices
- BSD Net/2, 386BSD, FreeBSD, NetBSD, OpenBSD license materials
- Apache 1.0/1.1
- Mozilla/Netscape Public License
- Perl Artistic/GPL dual licensing
- Python license history
- Tcl/Tk notices
- PostgreSQL license
- Sendmail license variants
- OpenSSL/SSLeay license
- SGI Free Software License, XFS, Open Inventor materials
- SCO / Caldera / UnixWare / OpenServer public source releases and license notices
- NeXT/OpenStep material and Apple transition materials

### 2000s

Priority questions:

- How did corporate open source become normalised?
- How did patents, contributor agreements, file-level copyleft, and open-core concerns enter mainstream licensing?
- How did Unix-derived systems such as OpenSolaris and Darwin handle source releases?

Targets:

- Apache-2.0
- GPLv3 and LGPLv3
- MPL 1.1 and 2.0
- CDDL
- EPL / CPL
- APSL 1.x and 2.0
- OpenSolaris licensing material
- Darwin and Apple open source licensing material
- IBM Public License / CPL / EPL transition material
- Sun Public License
- Java-related source licensing where historically relevant

## Phase 2: modern comparison set

Add modern documents that explain the later shift from open source to source-available, open core, cloud restriction, data, hardware, and AI licensing.

Targets:

- Business Source License
- Server Side Public License
- Elastic License
- Commons Clause
- PolyForm licences
- Blue Oak Model License
- Unicode License
- Functional Source License
- modern CLA and DCO materials
- Creative Commons family
- CDLA data licences
- CERN Open Hardware Licence
- OpenRAIL-style model licences

## Phase 3: metadata and verification

For every document, create a metadata record before or alongside the text.

Minimum viable metadata:

```yaml
id:
title:
short_name:
family:
era:
first_known_date:
organisation:
source_url:
archive_url:
source_type:
redistribution_status:
text_status:
spdx_id:
osi_approved:
fsf_free:
gpl_compatible:
license_style:
key_terms: []
related_licenses: []
verification_notes:
historical_notes:
```

## Source hierarchy

Use this order of preference:

1. Original source distribution, release tarball, source repository, manual, or vendor page.
2. Archived original source from Internet Archive, Software Heritage, vendor archive, university archive, or historical mirror.
3. Official SPDX, OSI, FSF, Apache, GNU, Eclipse, Mozilla, Apple, Sun/Oracle, IBM, Berkeley, or project pages.
4. Reputable secondary historical accounts.
5. Unsourced online copies only as leads, not as authoritative texts.

## What not to do

- Do not bulk-copy licence texts without provenance.
- Do not assume an SPDX text is historically identical to a particular old source-tree notice.
- Do not merge vendor-specific variants into generic families without recording the exact variant.
- Do not label something open source merely because the source was visible.
- Do not redistribute documents where the legal status is unclear; create metadata-only entries instead.

## First 50 target entries

A strong first milestone would include metadata entries for:

1. AT&T Unix research source licence material
2. Western Electric Unix notice material
3. 32V / Research Unix source-distribution terms
4. 4BSD UC Regents notice
5. 4.2BSD UC Regents notice
6. 4.3BSD UC Regents notice
7. Net/2 BSD notice
8. 4-clause BSD
9. 3-clause BSD
10. 2-clause BSD
11. MIT/X11
12. MIT Athena
13. CMU Mach notice
14. University of Utah Flux/OSKit notice
15. GPLv1
16. GPLv2
17. LGPLv2
18. GPLv3
19. LGPLv3
20. AGPLv3
21. GNU FDL
22. Autoconf exception
23. Classpath exception
24. Apache License 1.0
25. Apache License 1.1
26. Apache License 2.0
27. NCSA License
28. Mozilla Public License 1.0
29. Netscape Public License
30. Mozilla Public License 1.1
31. Mozilla Public License 2.0
32. Common Public License
33. Eclipse Public License 1.0
34. Eclipse Public License 2.0
35. Sun Public License
36. CDDL 1.0
37. Apple Public Source License 1.x
38. Apple Public Source License 2.0
39. Python License variants
40. Artistic License 1.0
41. Artistic License 2.0
42. Perl dual-license notice
43. Tcl/Tk license
44. PostgreSQL License
45. Sendmail License
46. OpenSSL License
47. SSLeay License
48. SGI Free Software License variants
49. Open Inventor licence material
50. SCO / Caldera open-source or source-release notices
