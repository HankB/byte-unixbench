# Unit Tests

Added by <https://github.com/HankB> for the purpose of testing some code modifications. At present there is no plan to add unit tests to existing code.

## Wrinkles

It seems not possible to extract a function from `Run` and I'm reluctant to modify the original content any more than absolutely needed. To debug the code for various platforms, it will be copied into a `test_...` program, worked on and then copied back to `Run`.

## getCpuInfo()

This function is not producing correct results on ARM systems (e.g. Raspberry Pi.)

```text
cd byte-unixbench/UnixBench/unit_test
./test_getCpuInfo
```
