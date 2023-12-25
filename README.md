## Project 1: Advanced scheduler
- Edit /src/threads/Make.vars Line 7 : change bochs for qemu
- 'make' in folder /src/threads
- Edit your path in file **pintos-gdb**, **pintos** (line 103,257,621), **pintos.pm**(line 362) in folder  **/src/utils**
- Edit your path in hiden file /.bashrc
- 'source ~/.bashrc'
- cd /threads/build, then 'make check'
## Project 2: Syscall
- Edit your path in file **pintos-gdb**, **pintos** (line 103,257,621), **pintos.pm**(line 362) in folder  **/src/utils**
- source ~/.bashrc
- 'make' in folder /src/userprog
- cd /userprog/build
- 'pintos-mkdisk filesys.dsk --filesys-size=2'
- 'pintos -f -q'.
- 'make' in folder /src/examples
- 'pintos -p ../src/examples/echo -a echo -- -q' ( replace by link of echo.c)
- pintos -q run 'echo x'
- 'make check'
