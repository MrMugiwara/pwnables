# chal1

For your debugging convenince, a single-thread version of the server is available. Note that the addresses will change, but it will make the first steps easier.

Turn off ASLR to poke at the server on the client side.

Not verified with ASLR enabled. Turn off for best results.

If you recompile with 'make' the addresses will change.

## Disable ASLR

This is temporary until reboot.

with sudo:

echo 0 > /proc/sys/kernel/randomize_va_space
