# isvt - Windows virtual terminal utility

A simple tool to report and change the virtual terminal mode for the current console.
Run without arguments to see if VT/ANSI mode is enabled for console input and output.
Use the following flags to turn VT mode on and off:
- `i+ / i-` &rarr; Enable/disable VT input.
- `o+ / o-` &rarr; Enable/disable VT output.
- `a+ / a-` &rarr; Enable/disable VT input and output.
- `i/o=xxxx` &rarr; Set a custom mode (hex or flag names). Names and hex values can be combined with `|`.
- `-p pid` &rarr; Attach to process identified by `pid`.
- `-l` &rarr; Show valid input/output flags.
- `-h` &rarr; Show help.
