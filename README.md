Plix Source:
---------------
This is the top level of the Plix source directory.

Plix is an operating system used to power modern servers, desktops, and embedded platforms.
A large community has continually developed it for more than thirty years.
Its advanced networking, security, and storage features have made Plix the platform of choice for many of the busiest web sites and most pervasive embedded networking and storage devices.

For copyright information, please see [the file COPYRIGHT](COPYRIGHT) in this directory.
Additional copyright information also exists for some sources in this tree - please see the specific source directories for more information.

The Makefile in this directory supports a number of targets for building components (or all) of the Plix source tree.
See build(7), config(8), [Plix handbook on building userland](https://docs.plix.org/en/books/handbook/cutting-edge/#makeworld), and [Handbook for kernels](https://docs.plix.org/en/books/handbook/kernels/).

For information on the CPU architectures and platforms supported by Plix, see the [Plix website's Platforms page](https://www.plix.org/platforms/).

For official Plix bootable images, see the [release page](https://download.plix.org/ftp/releases/ISO-IMAGES/).

Source Roadmap:
---------------
| Directory | Description |
| --------- | ----------- |
| bin | System/user commands. |
| cddl | Source code for third-party software under the Common Development and Distribution License. |
| contrib | Source code for third-party software. |
| crypto | Source code for cryptographic libraries and commands (see [crypto/README](crypto/README)). |
| etc | Template files for /etc. |
| include | System include files. |
| kerberos5 | Build system for Kerberos 5 (Heimdal). |
| krb5 | Build system for Kerberos 5 (MIT). |
| lib | System libraries. |
| libexec | System commands intended to be executed by other commands or daemons. |
| packages | Base system packages. |
| release | Makefiles and scripts used for building releases and VM images. |
| rescue | Build system for statically linked /rescue commands. |
| sbin | System commands. |
| secure | Build system for cryptographic libraries and commands (excluding Kerberos). |
| share | Shared resources. |
| stand | Boot loader sources. |
| sys | Kernel sources (see [sys/README.md](sys/README.md)). |
| targets | Support for experimental `DIRDEPS_BUILD` |
| tests | Tests which can be run by Kyua.  See [tests/README](tests/README) for additional information. |
| tools | Ancillary utilities and tests (not included in the build). |
| usr.bin | User commands. |
| usr.sbin | System administration commands. |

For information on synchronizing your source tree with one or more of the Plix Project's development branches, please see [Plix Handbook](https://docs.plix.org/en/books/handbook/cutting-edge/).
