# zswap3to6
This repository is to migrate zswap from linux3.12.60 to linux6.4.3


This repository is based on linux6.4.3, with several files changed:
- zswap.c: Original zswap.c was deleted, current zswap.c is in fact from Linux3.12.60
- myInterface.c: the interface file for migration
- myInterface.h: the interface file for migration