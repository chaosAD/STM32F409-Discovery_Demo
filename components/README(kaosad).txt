The following note describes stuffs that can be improved:

A. The codebase can be dramatically reduced:

1) In '/coocox-master' folder only 'syscall.c file' is used. The rest can be deleted.
2) Most files in CMSIS are not used. Only some listed in the CoIDE project are needed.
3) Most files in 'components/Components/' can be removed. Only 'lis3dsh' and 'lis302dl'
   are needed.

B. The
