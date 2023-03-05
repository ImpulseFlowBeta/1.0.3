## SystemD: journalctl demo

This demo shows use of a engine script module to wrap a native tool (journalctl) so that the output is structured for filtering and presentation control. `journalctl` is expressed as a cmdlet: Get-SystemDJournal, and the JSON output of journalctl is converted to the object. 

## Prerequisites ##
- Requires a Windows 10/11
- Install the game
- Run launcher


Note: Accessing the SystemD journal requires privileges. The user must have authorization to elevate with sudo. You will be prompted for a sudo password when running the demo.
