# Settings and security

## Where settings live

A11yScanFix settings are grouped under the **A11yScanFix** admin menu: Scanner,
Fixers, AI Alt Text, Statement, and (in Pro) Roles & Rules and Reports.

## How your data is handled

- **Scanning runs in your browser** (axe-core). Page content is not sent to
  A11yScanFix or any third party.
- **Results stay in your database** (post meta, options, transients). No custom
  database tables are created.
- **AI API keys are stored encrypted** in the options table and are sent only
  to the AI provider you chose, only when generating alt text.

## Permissions

Actions that change data require the right WordPress capability, and every form
and request is protected against cross-site request forgery. Pro adds
role-based permissions to control who can scan, fix, or change settings.

!!! warning "✏️ FILL IN: exact capability + roles details"
    Confirm which capabilities gate which actions, and document the Pro
    role-based permissions options.
    <!--FILLIN-->
