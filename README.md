# :question:What is ShellCheck?
ShellCheck is a static analysis tool that does exactly what PSScriptAnalyzer does, but for `sh`, `bash`, `dash`, and `ksh` scripts. 

# :ocean:How to use ShellCheck

## 1. Install the Tool
Since it is a compiled tool, you install it via your system's package manager:

**Windows (via Winget):**
```powershell
winget install koalaman.shellcheck
```

**Linux (Ubuntu/Debian):**
```bash
sudo apt install shellcheck
```

## 2. How to Use It
Once installed, you can point it at any `.sh` file to get a report of warnings, errors, and best-practice violations.

To scan a specific script, use this command:
```powershell
shellcheck ./your_script.sh
```

<img width="2594" height="1040" alt="image" src="https://github.com/user-attachments/assets/7735982b-e2d5-42d1-a2cd-3709ddf9b3d0" />

<br>
<br>

If you use VS Code, there is also an official ShellCheck extension that will highlight your `.sh` files with squiggly lines in real-time as you type, just like a modern IDE.
