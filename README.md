# paidini

Internal client for ARK: Survival Evolved, the **Microsoft Store / Xbox PC** version (v962.2). It gets manually mapped into the game and draws its own menu over ARK.

## Using it

1. Open ARK and get to the main menu.
2. Run `injector.exe` with `paidini.dll` sitting next to it.
3. Press **Delete** to open/close the menu.

Settings save to configs (Settings → Configs), so you don't have to set everything up again each time. Eject is under Settings → Menu. Use that instead of just closing the game if you want everything put back properly.

The log is at:
`%LOCALAPPDATA%\Packages\StudioWildcard.4558480580BB9_1w2mm55455e38\AC\paidini\debug.log`
If something breaks, that's the first place to look.

## Notes

- MS Store build only. Steam ARK has different offsets and none of this will line up if you inject it into Steam Ark you will be banned and that is not my fault.
- Offsets were all checked against the live game, but if Wildcard pushes an update stuff will probably need redoing, Which is not likely. 
- There's a crash guard that catches some of ARK's own UI crashes. If the game still dies, the crash site gets written to the log, so send that along.
- Full feature list is in `FEATURES.txt`.

Use it at your own risk. Servers can and do ban for this stuff.
