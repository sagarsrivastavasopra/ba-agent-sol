# BA Requirement — REQ-001

**Title:** Add "Preferred Contact Method" field to Contact record

**Requested by:** Jane BA
**Priority:** Medium

## Description
The sales team needs a way to record how a contact prefers to be reached
(Email, Phone, SMS). This should appear on the Contact main form, be
visible on the Contact list view, and be optional (not required).

## Scope
- New choice field on the Contact entity: "Preferred Contact Method"
  - Options: Email, Phone, SMS
  - Default: Email
- Add field to the main Contact form, General tab
- Add field as a column on the default Active Contacts view
- No changes to any existing automation, flows, or plugins

## Acceptance Criteria
- Field exists on Contact entity with correct options
- Field visible and editable on main form
- Field visible as a column on Active Contacts view
- No impact to existing contact creation flow
