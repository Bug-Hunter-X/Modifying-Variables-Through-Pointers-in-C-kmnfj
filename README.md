# Modifying Variables Through Pointers in C

This repository demonstrates a simple C program that modifies a variable's value using a pointer.  While seemingly straightforward, this highlights a fundamental concept that often leads to subtle bugs in C programming.  The example shows how directly modifying a variable via its pointer can unexpectedly change its value, affecting the program's behavior if not handled carefully.

**Understanding the Bug:**
The key issue lies in the way pointers are used to indirectly access and manipulate variables in memory.  If not managed correctly, this can lead to unintended side effects or even memory corruption.

**Solutions and Best Practices:**
The provided solution offers a more robust way of handling the variable modification, illustrating how to avoid potential pitfalls associated with pointer usage.