# QuickShut

A lightweight and efficient Windows utility designed for instantaneous and forceful system termination.

## Overview

**QuickShut** is a specialized batch script tailored for users who require an immediate system shutdown. Unlike the standard shutdown process, QuickShut bypasses common delays by forcefully terminating the Windows shell and triggering a zero-second shutdown sequence.

## Features

- **Forceful Shell Termination**: Automatically terminates `explorer.exe` to prevent UI-related hang-ups during shutdown.
- **Instant Execution**: Utilizes the `/t 0` flag for an immediate power-down sequence.
- **Force Flag**: Employs the `/f` parameter to override any "waiting for background programs" prompts, ensuring a guaranteed shutdown.

## Installation & Usage

1. **Clone the repository** (or download `QuickShut.bat` directly):
   ```bash
   git clone https://github.com/Luksa/QuickShut.git
   ```
2. **Execution**:
   Navigate to the directory and run the script with administrative privileges for best results:
   ```cmd
   QuickShut.bat
   ```

## ⚠️ Warning

This script performs a **forced shutdown**. It will not prompt you to save open work and will immediately terminate all running applications. Use with caution.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
