# Brawlstead — official Windows alpha downloads

[**Download BrawlsteadSetup.exe**](https://github.com/John1r637/Brawlstead-Downloads/releases/latest/download/BrawlsteadSetup.exe)

Run the installer once. It creates the **Brawlstead** desktop shortcut, checks for updates, and launches the game. Future game updates replace files in the same permanent folder; no new ZIP extraction is needed.

**Existing players: run the latest installer once to upgrade the launcher’s integrity checks.** It uses your existing game folder and preserves settings.

- Windows 10/11, 64-bit. Godot and a GitHub account are not required.
- Installation: `%USERPROFILE%\Games\Brawlstead\Game`.
- Close the game before updating. Settings and controls are preserved.
- Hold **Shift** while opening the shortcut to keep the updater open. **Restore previous** rolls back and pauses updates; **Resume updates** re-enables them. A `Manage Updates.lnk` shortcut is also inside `%USERPROFILE%\Games\Brawlstead`.
- The previous two installations are retained internally for rollback. Online play needs a matching client and server version.
- Multiplayer uses the free US East alpha host. Sessions expire after one hour; **Start a match → Create Server** can start a matching host when the free slot is available. Browsing alone never starts one.

The launcher verifies the signed installation, repairs changed or missing files, and rejects unexpected files. Direct game starts also verify the installation. If the game shows **Repair required**, reopen the desktop launcher; if needed, rerun the latest installer. Keep extra files outside the `Game` folder. The release ZIP is an updater payload, not a standalone installation.

These checks detect ordinary tampering and corruption; they cannot make local files impossible to inspect or deliberately modify. This alpha does not yet have a commercial Windows code-signing certificate, so Windows may display an unknown-publisher warning. Obtain the installer only from this repository. Signed update manifests are separate from Windows executable signing.

Only compiled game releases, installer files, notices and instructions are public here. The game source repository remains private. See the notices included with the game for third-party licenses.
