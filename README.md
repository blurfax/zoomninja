# zoomninja
A fix for ZOOM ERROR 1132 (macOS) 

Zoom Ninja Mode — Beginner Instructions
======================================

What this does:
- Quits Zoom
- Clears Zoom's local cache (you may be signed out)
- Randomizes your Wi-Fi MAC address (requires admin password)
- Restarts Wi-Fi
- Launches Zoom (inside a basic sandbox when available)

How to run:
1. Double-click "Zoom Ninja Mode.app".
2. The first time macOS may say the app is from an "unidentified developer":
   - Right-click (or Control-click) the app → Open → Open again to confirm.
3. When asked for your password, enter your Mac's admin password. (You won't see characters as you type.)
4. Wait for the notification "Zoom Ninja finished." Zoom will open.

Notes & Troubleshooting:
- If macOS blocks the app, use Right-click → Open to bypass Gatekeeper.
- If sandbox-exec is not available, the app will still open Zoom normally.
- Changing MAC addresses may break access to some Wi-Fi networks or violate network policies. Use only on trusted networks.
- If Zoom does not open or networking is bad: reboot your Mac to restore the default MAC address.

How to remove:
- Delete "Zoom Ninja Mode.app"
- Optionally remove this sandbox profile file created at: ~/zoom-sandbox.sb

Permissions & Security:
- This app does not phone home or collect data. It runs local commands that modify your system (intentional).
- Always review the script text before sharing or running on someone else's machine.

Support:
- If a recipient is uncomfortable with the admin password step, they should not run the app.
