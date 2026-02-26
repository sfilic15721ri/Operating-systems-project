# Operating-systems-project
A project implementing core Operating Systems concepts—concurrency, synchronization, memory management, and low-level system interactions—to demonstrate system-level programming skills.

XV6 Custom Console Project
Modifications

Console: Added history of the last 3 commands with ↑ / ↓ navigation.

Input color: Currently selected command shown in light gray (0x0300), normal input is white (0x0700).

Cursor and scroll: Improved line deletion and scrolling, preventing cursor overflow.

Fully compatible with existing syscalls (read, write, etc.).

Usage

Run xv6.

Type commands in the console.

Use ↑ and ↓ to navigate the last 3 commands.

All other syscalls and standard functionality work normally.
