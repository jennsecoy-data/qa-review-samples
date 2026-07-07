# Content Quality Issue Tracker

This sample tracker is used to document content, formatting, accuracy, consistency, and completeness issues found during QA review.

## Purpose

A content quality issue tracker helps organize findings so issues can be corrected, reviewed, and monitored for repeated patterns.

This type of tracker is useful for:

- Documenting QA findings
- Tracking content review issues
- Recording correction status
- Identifying repeated errors
- Communicating clearly with a program lead, reviewer, or production team
- Supporting process improvement

## Issue Tracker Table

| Issue ID | Content Area | Issue Description | Requirement or Source Conflict | Severity | Recommended Action | Status |
|---|---|---|---|---|---|---|
| QA-001 | Final Form Text | Instruction wording does not match approved source | Approved source uses different wording | Medium | Update final text to match source | Needs Correction |
| QA-002 | Image Caption | Caption punctuation differs across forms | Captions should be consistent across versions | Low | Standardize punctuation | Needs Review |
| QA-003 | Online Version | Required accessibility note is missing | Online version should match required accommodation notes | High | Add missing note and recheck | Needs Correction |
| QA-004 | Record Entry | Date does not match source record | Final record conflicts with approved source | Medium | Correct date and verify related fields | Needs Correction |
| QA-005 | Formatting | Heading spacing is inconsistent | Formatting should match document style | Low | Adjust spacing for consistency | Needs Review |
| QA-006 | Ancillary Material | Supporting material uses outdated wording | Main document uses updated wording | Medium | Update ancillary material to match | Needs Correction |
| QA-007 | Text-to-Speech | One sentence is missing from spoken version | TTS should match final item text | High | Add missing sentence and complete second review | Needs Correction |

## Issue Categories

| Category | Description |
|---|---|
| Accuracy | Incorrect names, dates, numbers, labels, item references, or instructions |
| Completeness | Missing sections, fields, notes, captions, images, or required edits |
| Consistency | Wording, formatting, punctuation, or structure differs across versions |
| Formatting | Spacing, headings, tables, lists, or visual layout do not match the required format |
| Accessibility | Alternate-format, accommodation, text-to-speech, or readability requirements are missing or inconsistent |
| Documentation | Issue notes are unclear, incomplete, or missing needed detail |
| Process | Repeated issue suggests a workflow or communication improvement opportunity |

## Severity Levels

| Severity | Description |
|---|---|
| Low | Minor formatting, style, or punctuation issue that does not change meaning |
| Medium | Accuracy, completeness, or consistency issue that should be corrected before approval |
| High | Missing, incorrect, or conflicting information that may affect usability, quality, compliance, or final approval |

## Example Issue Notes

### QA-001: Final Form Text

The final instruction text does not match the approved source wording. The meaning is similar, but the approved wording should be used exactly for consistency across forms.

**Recommended action:** Update the final version to match the approved source and complete a second verification pass.

### QA-003: Online Version

The required accessibility note is missing from the online version. The paper version includes the note, so the online version does not currently align.

**Recommended action:** Add the missing note to the online version and confirm that all related versions match.

### QA-007: Text-to-Speech

The text-to-speech version is missing one sentence from the final item text. This creates an incomplete alternate-format version.

**Recommended action:** Add the missing sentence, then compare the full text-to-speech version against the approved final content.

## Repeated Issue Tracking

Repeated issues should be documented so they can be reviewed for process improvement.

| Pattern Found | Example | Possible Process Improvement |
|---|---|---|
| Missing accessibility notes | Notes missing from multiple online items | Add an accessibility-note checkpoint before final review |
| Caption inconsistency | Captions differ across forms | Use a shared caption source or checklist |
| Outdated wording | Ancillary materials not updated | Confirm all related materials are included in edit requests |
| Formatting drift | Headings and spacing differ by section | Add formatting review to final QA pass |

## Final Status Options

| Status | Meaning |
|---|---|
| Open | Issue has been documented but not yet reviewed |
| Needs Review | Issue needs confirmation or lead review |
| Needs Correction | Issue should be corrected before approval |
| Corrected | Update was made but needs verification |
| Verified | Correction was reviewed and confirmed |
| Closed | Issue is fully resolved |

## Summary

This sample demonstrates how a QA reviewer can document content quality issues clearly, track correction status, and identify repeated patterns that may improve future workflows.