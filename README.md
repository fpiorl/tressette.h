tressette.h
===========

minimal tressette implementation in C as a State Machine with no heap allocations.
could be potentially converted into the TRESSETTE MULTITAPE TURING MACHINE with LLM assistance.

with low kernel mode usage (random number generator and `__builtint_memcpy` and `__builtin_memset` on linux)
kernel mode usage can be reduced to none by: 
- implementing a DOOM-style `__builtin_memcpy` and `__builtin_memset`
- having a source of randomness on embedded system
