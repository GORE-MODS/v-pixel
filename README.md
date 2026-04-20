# v-pixel
A lightweight, high-performance CSS injection for Vencord and BetterDiscord that transforms your client into a retro-future CRT terminal.

## OVERVIEW
v-pixel is designed for developers and users who want a clean, pixelated aesthetic without the bloat of traditional themes. It prioritizes UI stability while delivering an authentic retro experience.

## CORE_FEATURES
[STABILIZED_TYPOGRAPHY]: Uses a refined Press Start 2P configuration.

Correction Logic: Custom line-height and letter-spacing to prevent UI stretching and container overflow.

[CRT_ENGINE]: A zero-latency CSS overlay providing:

Horizontal scanlines.

Subtle RGB phosphor mask.

Vignette depth for "curved screen" immersion.

[ZERO_FOOTPRINT]: Does not modify Discord's core layout classes. This ensures the theme remains functional even after major Discord updates.

[PERFORMANCE_FIRST]: Minimalistic code footprint with no external assets besides the Google Font import.

## INSTALLATION
Open your Vencord Settings.

Navigate to Themes > Upload Theme

Paste the v-pixel.theme.css code.

Enable and enjoy the phosphor glow.

## CONFIGURATION
You can easily adjust the intensity of the scanlines by modifying the opacity or background-size variables within the :root or body::after selector.

## LICENSE
This project is licensed under the MIT License. You are free to use, copy, modify, merge, publish, and distribute this software as you see fit.

Note: Best experienced on dark mode.
