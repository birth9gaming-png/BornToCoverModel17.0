# Prototype 17

This complete build integrates the expanded CFB totals layer, revised NFL spread/total models, guarded seasonal context learning, accurate matchup overlap handling and top-two ≥60% weekly shortlists with additional leans. Saved-data and missing-value serialization protections are preserved.

Extract football_dashboard_prototype17.zip and replace every file inside football_dashboard/ in your app repository, including requirements and all preloaded assets. Retain your existing Streamlit Secrets, private storage configuration and saved workspace; rebuild dependencies and reboot. Confirm Prototype 17 in the sidebar. No historical-season download, model reset, R2 deletion or key change is needed. The active main recipe is version 17.

Allow the normal background refresh to load current inputs and actual prices. The bundled saved preview is not live advice. Research decisions, year-split performance, coverage and early-2026 failures are documented in research_notes_v17.md and Method & Validation. Development CFB/NFL high-estimate results exceed 60%, but do not establish a guaranteed future or live win rate. No confidence is inflated to fill weekly slots.

See audit_report_v17.md for current verification: 330 backend tests, 12 interface/startup/save tests and final tab checks passed. Historical/live CFB rules agree on 5,878 rows. Software tests validate behavior, not betting accuracy; native-browser visual sign-off is not claimed. Prototype 16.1 remains the separate previous-build rollback.
