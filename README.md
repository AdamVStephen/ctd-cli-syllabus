# ctd-cli-syllabus
Recommended set of standard command line interface (linux/shell) skills.  Plus pointers to where
much of this comes from and where it can lead to, admittedly straining the title rather a lot.

## Unix Ethos and Basics of the Shell

1. Hello world.  Minimum viable command set : pwd, cd, ls, find, cat, less, history.
2. Distinction between shell builtin commands and other commands.  PATH and LD_LIBRARY_PATH.
3. Everything is a file and nothing is a file.  /dev/null and /dev/random
4. Text editors : nano, vi/vim, emacs, ed, sed.
5. Variables and expansion basics.
6. Redirection and pipes, including the basics of file descriptors.
7. Filesystems - including permissions, space, virtual filesystems, NFS filesystems.
8. Text manipulation on the fly : awk, sed, cut, column, grep.
9. Readline.
10. Putting it all together: bash script, shebang, shellcheck.
11. Bash is not the only shell.  Other shells are available.
12. Customisations and rc files.
13. Login shells, interactive shells, subordinate shells, ssh connections.
14. Tmux and screen.
15. ssh tips and tricks, security, keys.
16. Job control, foreground, background, signals.
17. Eye candy, fancy prompts.
18. Git.  Local, remote, command line.
19. What can go wrong, will go wrong.  Resilient bash scripts for profit.
20. Introduction to other file types : .sh, .py, .c, .cpp, .h, .o, .a, .so, .java, .jar, .tar, .gz, .tar.gz
21. Legacy packaged code : tarballs, GNU make, autoconf and friends.
22. Build tools make, cmake, maven and others.
23. Modern packaged code : apt, yum, variations on the theme.
24. Ubermodern packaged code : snap, flatpack.
25. Containers and virtualisation : VMs, containers, docker, kubernetes.
26. Security basics : users, groups, networking, files, stack smashing.
27. Networking 101 : OSI model, TCP/IP, sockets, client/server, how to speak HTTP, SMTP
28. Network 201 : RFCs, TCP/IP programming, wireshark, tshark
29. Tracing and debug : strace, pstrace, ps, gdb, printf
30. Basic compiling and linking. Pointer to GNU binary utilities.
31. Deconstructing code from the binary.  Initial hints at what is possible.
32. Most important language concepts and languages - a brief overview.  C, C++, Java, Python, Lisp, Clojure, Julia, Haskell, Tcl, Perl.
33. Aho, Sethi and Ulman.
34. Kernighan and Richie.
35. Deep C mistakes.
36. From Stroustrup to Odin the Nerd.  C++ ISO Standards committee and C++11/14/17/20/23.
37. Assembly and ISAs.   Godbolt.  Main current architectures : x86 (32/64), ARM-{A,R,M} series A32 and T32, RISC-V.
38. Building software on other architectures.
39. Building software for other architectures (cross compiling tool chains)
40. Component based software : executables, shared objects, dynamic loading and reloading.
41. Multicore software issues.
42. Concurrency.
43. IDEs and Toolchains, middleware and libraries.  ulibc, glibc.
44. Operating systems : Tanenbaum
45. Bare metal development.
46. Fundamentals of CPU design from the hardware point of view.
47. Hardware description languages : ARM revisited from another point of view.
49. VHDL and IP : the Xilinx/Zynq platform as an example.
50. Buses : getting data from A to B ; SPI, I2C, USB, PCI, PCIe, uTCA, serial
51. SoC and SoM : on-chip, off-chip, single board, multi board.
52. FPGA - tying some of the above together.
53. Embedded world : from power on, to application : what happens?
54. Bootloaders : uBoot.  Bootlin.
55. IoT, IIoT, AIoT.
56. Machine learning, AI, Tensorflow, GPU
57. HPC
58. Cloud/Edge
59. 

## Motivational Examples

### Global Search and Replace

find . -name Makefile | xargs sed -i 's/aarch64-elf-/aarch64-linux-gnu-/'

