# APC40 Bridge program updates

Public program-only release channel. No GitHub account or token is needed by the installed updater.

At startup, a newer published release requires Update or Exit. The old dashboard is not opened when the update is declined or fails. If the update server is unreachable, the installed version remains usable offline. A running show is not terminated; close Arena before installing an update.

Updates validate the release digest and file allowlist, back up replaced program files and roll back on copy failure. Composition, MIDI/output presets, config/state, profiles, room models, physical layouts, workspaces and private scene-calibrated preview.html are excluded.

Use the full offline kit for the first installation. Release tags use bridge-YYYY.M.D.N and the bridge-update.zip asset. Publishing a new complete release makes it required at the next successful startup check. Local administrators and offline use are not tamper-proof restrictions.
