# Contributing

This archive is intended to be historically useful. Contributions should therefore prioritise provenance, exactness, and careful classification.

## Good contributions

Good contributions include:

- verified licence texts from primary sources
- metadata records for licences that cannot yet be redistributed
- pointers to original vendor, university, project, or archived release material
- historical notes explaining why a licence mattered
- comparisons between related licence variants
- corrections to provenance, dates, or classification

## Minimum standard for new entries

Every new entry should include at least:

```yaml
id:
title:
short_name:
family:
era:
organisation:
source_url:
source_type:
redistribution_status:
text_status:
verification:
historical_notes:
verification_notes:
```

## Provenance rules

- Prefer primary sources.
- Use archived URLs where available.
- Record the release, tarball, repository, manual, or page where the text was found.
- Note whether the text is canonical, a source-header notice, a README condition, an agreement, a FAQ, or commentary.
- Do not silently modernise old spelling, punctuation, or section numbering.
- Do not replace a historical variant with a modern SPDX text unless the entry is explicitly for the modern SPDX text.

## Redistribution caution

Some historically significant licensing documents may not be safe or appropriate to reproduce in full. In those cases, add a metadata-only entry with source pointers and notes rather than copying the text.

Use these values:

- `full-text-ok` where the archive can include the text
- `metadata-only` where the archive should only describe and point to the document
- `unknown` where review is required
- `do-not-redistribute` where the archive should not include the document text

## Suggested entry layout

```text
families/<family>/<entry-id>/
  metadata.yml
  LICENSE.txt        # only where redistribution is OK
  notes.md
```

For broad family notes, use:

```text
families/<family>/README.md
```

## Tone

The project can be enthusiastic about old Unix, workstation companies, free software, and licensing weirdness, but entries should stay precise. Do not turn metadata notes into advocacy unless the advocacy itself is part of the historical record.
