# shorkoff

A shutdown helper utility for SHORK OSes that safely brings the system to a controlled halt before a manual power off. It is intended as an explicit utility that the user can call to sync write cache to help prevent data corruption or loss on especially older hardware when faced with a manual power off, then halts the system so the user can switch the power off without interrupting any active operations. It displays a "safe to turn off your computer" message reminiscent of what Windows 95, 98 and Me can display.
