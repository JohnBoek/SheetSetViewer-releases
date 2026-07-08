# Changelog

## v1.0.3 (2026-07-08)

- Fixed: opening a file from a second window (e.g. double-clicking a .dst while the Viewer was
  already open) could hang the second launch if there was a problem opening it, instead of showing
  an error and closing normally.
- Fixed: a license check that failed unexpectedly at startup could permanently block opening files
  until the app was restarted, instead of retrying next time.
- Improved: the sheet properties panel now loads and scrolls smoothly even for sheet sets with
  hundreds of custom property values.
- Fixed (rare): launching the app with an empty file argument could leave a hidden background
  process running.
- Fixed: opening a file via a relative path could, in a rare case, cause "Reload" to look in the
  wrong location later if the app's working directory had changed since.

## v1.0.2 (2026-07-07)

- Fixed: closing the update dialog without clicking a button (the X button, Alt+F4, Escape) no
  longer silently postpones the update prompt for two days — you'll be asked again next launch.
- Security: license keys are now unique per Boek Solutions product, even on the same computer.
  If you have an existing license and it's no longer recognized after updating, this is expected —
  email info@boeksolutions.nl with your Machine ID for a replacement key, a one-time step.

## v1.0.1 (2026-07-07)

- Security: strengthened how license keys are generated and validated. If you have an existing
  license and it's no longer recognized after updating, this is expected — email
  info@boeksolutions.nl with your Machine ID for a replacement key, a one-time step.

## v1.0.0 (2026-07-07)

- First release: WPF port with Light/Dark/Book themes, offline licensing (14-day trial), auto-update.
