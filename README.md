# TDD-in-C
Learning project for Test Driven Development using Raspberry Pi and Embedded programming.

# Set up
 - Connect Raspberry pi to power source. Remember to use appropriate voltage if screen is to be connected.
 - Connect Raspberry pi to internet. Use same router as laptop.
 - Check IP address of Raspberry pi.
 - Try to connect through terminal on laptop:
```
shh pi@<ip_address>
```

# cpputest setup
 - Install GCC (I used cygwin to install packages) and Cmake, and add them to path (Windows)
 - install cpputest:

```
 cd cpputest
 cmake CMakeLists.txt
```