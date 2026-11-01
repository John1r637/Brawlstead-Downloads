# Brawlstead — official Windows alpha downloads

[**Download BrawlsteadSetup.exe**](https://github.com/John1r637/Brawlstead-Downloads/releases/latest/download/BrawlsteadSetup.exe)

Run the installer once. It creates the **Brawlstead** desktop shortcut, checks for updates, and launches the game. Future updates replace files in the same permanent folder; no new ZIP extraction is needed.

- Windows 10/11, 64-bit. Godot and a GitHub account are not required.
- Installation: `%USERPROFILE%\Games\Brawlstead\Game`.
- Close the game before updating. Settings and controls are preserved.
- Hold **Shift** while opening the shortcut to keep the updater open. **Restore previous** rolls back and pauses updates; **Resume updates** re-enables them. A `Manage Updates.lnk` shortcut is also inside `%USERPROFILE%\Games\Brawlstead`.
- The previous two installations are retained internally for rollback. Online play needs a matching client and server version.
- Multiplayer currently uses the free US East alpha host. Sessions expire after one hour; **Start a match** can start a matching host when the free slot is available.

This alpha does not yet have a commercial Windows code-signing certificate, so Windows may display an unknown-publisher warning. Obtain the installer only from this repository. The updater verifies signed update manifests and every game file before installation.

Only compiled game releases, installer files, notices and instructions are public here. The game source repository remains private. See the notices included with the game for third-party licenses.
