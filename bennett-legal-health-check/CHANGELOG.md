# Changelog — bennett-legal-health-check

## v2.0.0 — 2026-04-29

Initial release. Department-aware health check for all Bennett Legal Cowork users.

### Tests
- T-01 MattersDB Read
- T-02 MattersDB Write
- T-03 EspoCRM
- T-04 Moxo
- T-05 M365 Calendar
- T-06 Memory Health
- T-07 Linear Write → posts pass/fail to OBE-1212

### Department coverage
- owner (Charles, Simon): all tests
- litigation (AJ): T-01 through T-07
- solar (Ana): T-01 through T-07
- admin (Katonya): T-04 through T-07
- marketing (Amy): T-05 through T-07

### Known issues at release
- T-01 spec typo: "Teles" should be "Tellez" — tracked OBE-1213
- T-06 CLAUDE.md 10.9KB (over 8KB target)
