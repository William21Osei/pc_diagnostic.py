
# PC Diagnostic Tool

A Python command-line application that collects basic computer system information and generates a diagnostic report.

## Features

- Detects the operating system and version
- Displays computer name and system architecture
- Reports the processor information available to Python
- Shows total, used, and free disk space
- Saves the results to `diagnostic_report.txt`
- Uses Python's standard library without external dependencies

## Technologies

- Python 3
- `platform`
- `shutil`
- `os`
- `datetime`

## Requirements

- Python 3.9 or later
- Windows, Linux, or macOS

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

   ```bash
   python pc_diagnostic.py
   ```

   On some Windows systems, use:

   ```bash
   py pc_diagnostic.py
   ```

4. View the diagnostic information in the terminal.
5. Open `diagnostic_report.txt` to read the saved report.

## Example Output

```text
========================================
       PC DIAGNOSTIC REPORT
========================================
Computer Name: MY-COMPUTER
Operating System: Windows
OS Version: 11
Architecture: AMD64
Python Version: 3.x
Disk Total (GB): 500.0
Disk Used (GB): 200.0
Disk Free (GB): 300.0
========================================
```

*Example values are illustrative; actual results depend on the computer.*

## Limitations

This project reports basic system information. It does not test component health, measure temperatures, detect all hardware faults, or repair computer problems.

## Author

**William Osei Sarpong**

Computer Science Student | Software Development | IT Systems & PC Hardware

- GitHub: [William21Osei](https://github.com/William21Osei)
- Interests: Python, C++, JavaScript, PC assembly, networking, and technical troubleshooting

## Future Improvements

- Add memory usage information
- Add clearer error handling
- Export reports in additional formats
- Add automated tests
