# SMART local-data browser test

Open https://wy901015.github.io/smart/

This is a frontend-only test build. It contains no trial data or trial-derived snapshots. Select your own exp_data.zip using the local file control; the file is parsed and processed entirely in your browser and is not uploaded by this page. Reloading clears local file data and settings.

After local loading, select Exp1/Exp2/Exp3, select legs A-D, zoom actual strain and auxiliary curves, inspect reversal markers and adjust threshold, baseline, deadband and gap handling. Per-leg health is reversal count / reference count; overall is the strict mean of four legs.

The provisional source timezone is Asia/Hong_Kong; original CSV files do not specify a timezone. Angle units remain unconfirmed. There is no backend or live logger connected in this test. The raw ZIP remains in the private source repository, never this public build.
