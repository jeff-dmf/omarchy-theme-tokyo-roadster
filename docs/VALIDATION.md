# Validation

Target: Omarchy Quattro 51bfd1dbaa1b5f790e19623faf2745945d40c796.

PASS: real upstream headless theme generator; local and Git-installed staging; generated TOML/JSON parsing; resolved templates; default wallpaper; repeated application; switching away and back; refusal to overwrite an existing theme. The initial wall-ride was fully decoded at 8192 × 5461, sRGB PNG.

Contrast: text/background 8.10:1; text/selection 6.36:1; blue accent/background 6.79:1. The canonical Tokyo Night muted colour has 1.91:1 contrast and is intended for subdued/decorative states, not ordinary body text.

NOT RUN: live XPS display, mixed scale, all shell orientations, keyboard/mouse interaction, lock screen, notification, GTK/terminal/editor reloads, shell restart/login, registry validator. Rust scaffold helper unavailable because cargo is not installed. No live preview or stable-release claim.

Wallpaper dimensions are export enlargements of generated artwork; no extra contextual enhancement passes are claimed.

Full-set update: PASS — all eight PNG exports fully decoded; SHA256SUMS passed for every wallpaper; default wall-ride bytes unchanged from the previous commit. Real upstream Git-installed headless staging verified all eight wallpapers in order, wraparound to the default, and retention of the selected wallpaper after switching away and back. Portable repository checks and five Node tests passed. Live desktop checks remain NOT RUN.

Poster addition: ninth wallpaper, lossless sRGB PNG at 8192 × 4608. Fully decoded and visually reviewed at full-frame and 100% detail. Existing eight wallpaper bytes and default selection preserved.
PASS for the ninth-image update: portable repository checks and five Node tests; all nine image checksums; real upstream headless Git-installed staging, nine-image cycle, default, wraparound and remembered selection. Live desktop interaction is not implied by this check.

Starlight addition: tenth wallpaper, lossless RGB8 sRGB PNG at 8192 × 8192, copied byte-for-byte from the reviewed and fully decoded export. Original received two contextual passes; Tokyo Night is a separate 1254 × 1254 colour edit enlarged to 8K. Existing nine wallpapers and wall-ride default are unchanged. No new live desktop acceptance is claimed.
