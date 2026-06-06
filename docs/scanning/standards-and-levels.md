# Standards and levels

A11yScanFix lets you choose which rule sets the scanner enforces, so results
match the standard you are held to.

## WCAG level

Pick the conformance level to test against (A / AA / AAA). AA is the common
legal target.

## Standard toggles

Turn rule sets on or off:

- **WCAG 2.0 / 2.1 / 2.2**
- **Section 508** (US federal)
- **EN 301 549** (EU)
- **Best practice** (axe-core recommendations beyond the formal standards)

These map to the tags axe-core attaches to each rule, so toggling a standard
shows or hides the matching issues.

!!! warning "✏️ FILL IN: exact toggle labels + defaults"
    Confirm the exact wording of each toggle and which are on by default in the
    current release.
    <!--FILLIN-->

## What A11yScanFix does not claim

Automated checks catch a large share of issues but not all of them. Some WCAG
criteria need human judgement. The dashboard reports what was tested; it does
not certify legal compliance.
