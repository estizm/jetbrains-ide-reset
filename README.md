# JetBrains IDE Evaluation Reset Script

This script resets the evaluation state of various JetBrains IDEs by removing specific evaluation files and user identifiers. It's useful for developers who need to reset their evaluation period for testing purposes.

## Supported IDEs

The script supports the following JetBrains products:

- IntelliJ IDEA
- CLion
- RustRover
- PhpStorm
- GoLand
- PyCharm
- WebStorm
- Rider
- DataGrip
- RubyMine
- AppCode

## Requirements

- Bash shell
- `plutil` command (for macOS)
- `sed` command

## Usage

1. **Download the Script**: Save the script as `reset.sh`.

2. **Make the Script Executable**:
   ```bash
   chmod +x reset.sh
  ./reset.sh

The script will automatically detect your operating system (macOS or Linux) and execute the appropriate commands to reset the evaluation states.

## Notes

- macOS: The script will kill the cfprefsd process to clear caches before removing evaluation files.
- Linux: The script removes evaluation files and user preferences stored in ~/.java/.userPrefs.

## Disclaimer
This script is intended for personal use and should not be used to bypass licensing agreements. Use it responsibly.



  
