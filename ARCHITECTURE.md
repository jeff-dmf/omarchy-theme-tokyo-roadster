# Architecture

colors.toml uses Omarchy’s Tokyo Night semantic palette. Four complete shell overrides style bar, controls, menu and launcher with blue accents; other shell and application configurations are generated upstream. Section defaults target Quattro 51bfd1dbaa1b5f790e19623faf2745945d40c796 and must be compared when upgrading. No full shell.toml override, install hook or Lua payload is supplied.

The sole wallpaper is backgrounds/01-tokyo-wall-ride-8k.png. It is a proportional 8192 × 5461 export of the approved generated preview, without a further contextual enhancement pass. SHA256SUMS verifies its bytes.

Offline validation and live-testing limits are recorded in docs/VALIDATION.md.
