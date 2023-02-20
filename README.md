# exitcode

Preferred system exit codes as defined by [`sysexits.h`](https://man.openbsd.org/sysexits).
This library is inspired by this [rust library](https://docs.rs/exitcode).

## Example

All constants from the manpage [sysexits(3)](https://man.openbsd.org/sysexits) are available without the `EX_` prefix.

``` python
import exitcode
import sys

sys.exit(exitcode.OK)
```