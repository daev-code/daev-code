# daev-code

Things I build in my spare time, mostly small tools and fixes for software I use. Each
project lives in its own repo with its own install instructions.

## WoW 1.12 addons

Small addons that fix or extend other people's addons. Each one is a separate addon, so the
original is never modified and keeps updating as usual.

| Addon | What it does | Extends |
|---|---|---|
| [PallyPowerNext](https://github.com/daev-code/PallyPowerNext) | A button that casts whichever PallyPower blessing is missing next | [PallyPowerTW](https://github.com/ShikawaLePaladin/PallyPowerTW) |
| [pfUIBarOpacity](https://github.com/daev-code/pfUIBarOpacity) | Fades pfUI's action bars out of combat, per bar | [pfUI](https://github.com/brues-code/pfUI) |
| [RinseCombatOpacity](https://github.com/daev-code/RinseCombatOpacity) | Gives Rinse a separate opacity for combat | [Rinse](https://github.com/Otari98/Rinse) |
| [ShaguDPSOpacity](https://github.com/daev-code/ShaguDPSOpacity) | Fades ShaguDPS windows out of combat | [ShaguDPS](https://github.com/shagu/ShaguDPS) |
| [BagshuiEmptyBag](https://github.com/daev-code/BagshuiEmptyBag) | Empties a bag into your other bags, or compacts them | [Bagshui](https://github.com/absir/Bagshui) |
| [BagshuiTooltipFix](https://github.com/daev-code/BagshuiTooltipFix) | Stops item tooltips jumping between two items | [Bagshui](https://github.com/absir/Bagshui) |

## WoW 1.12 client DLLs

DLLs that the client loads at startup through `dlls.txt`. They change how the client runs,
not the game itself.

| DLL | What it does |
|---|---|
| [SVWriteBuffer](https://github.com/daev-code/SVWriteBuffer) | Makes `/reload` and logout faster by saving each addon's SavedVariables in one write |

## Feedback

Found a bug or want something changed? Open an issue or a pull request on that project's repo.
