This fork is just for my own personal use with my own modifications. All credit for original work goes to misutesu-desu, and my additions may or may not work.

**15/03/2026:**
- Add customisable dk threshold (dk_activation_percent in preset) - falls back to 15
- Add sphere perk emoji threshold support: e.g.:
            "chaos_kakeraY": 50,
            "sphere_kakeraY: 25,
            "chaos_sphere_kakeraY": 0
- Added lazy workaround for issue where $dk was not resetting power until next $tu - for now, upon $dk, power is reset to 100%
- Added megasphere support

**17/03/2026:**
- Tentative fix to click green button kakera (still haven't been able to test if this works)

**18/03/2026:**
- Add pause when slash command maintenance is detected (Command under maintenance! (For 3 minutes, reboot))

**20/03/2026:**
- Add starwish emoji support (starwish_emojis in preset)
- Allow kakera priority to be set from presets.json ("kakera_priority" - no numbers required, just make sure they're in the desired order)

**21/03/2026:**
- Fix free (kakeraP) & discounted (chaos, sphere) kakera not being clicked when you don't have enough kakera for a normal reaction at the start of a roll session

**28/03/2026:**
- Added automatic $daily and $pokeslot support (only works when rolling is enabled)
