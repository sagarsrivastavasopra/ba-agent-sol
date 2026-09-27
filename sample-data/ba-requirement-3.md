# BA Requirement — REQ-003

**Title:** Auto-close stale leads and archive old records

**Requested by:** Priya BA
**Priority:** Medium

## Description
Leads that haven't been touched in 90 days should be automatically closed
to keep the pipeline clean. Also, we want to permanently delete old lead
records older than 1 year to save storage.

## Scope
- Cloud flow to auto-close leads inactive for 90 days
- Separate process to delete lead records older than 1 year
- Should run on a schedule, no manual trigger needed

## Acceptance Criteria
- Stale leads (90+ days inactive) are closed automatically
- Lead records older than 1 year are removed from the system
- Runs automatically on a schedule