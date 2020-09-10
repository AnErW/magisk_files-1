## Magisk (e66b0bf3) (20425)
- Upstream libsepol to support latest sepolicy binary format
- Use intent + FIFO for communication between Magisk Manager and `magiskd` for su request.
This should fix all su request dialog not showing up issues.

## Magisk Manager (e66b0bf3) (298)
- Support new su request communication scheme
- Fix quirky network status detection
- Fix manager hide on MIUI
