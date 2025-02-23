# Tcl Loose Comparison Bug

This repository demonstrates a common, yet subtle, bug in Tcl code related to loose comparisons. The `badproc` procedure incorrectly uses loose comparison (`==`) instead of strict comparison (`eq`) for numerical values.

The `bug.tcl` file contains the buggy code. The `bugSolution.tcl` file provides a corrected version.

## Running the Code

You can run the Tcl code using the `tclsh` interpreter.

For the buggy code:
```bash
tclsh bug.tcl
```

For the corrected code:
```bash
tclsh bugSolution.tcl
```