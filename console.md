$ gcc -o foobar5 foo5.c bar5.c
$ gcc -c addvec.c mulvec.c
$ ar rcs libvector.a addvec.o mulvec.o
$ gcc -shared -fPIC -o libvector.so addvec.c mulvec.c
$ gcc -rdynamic -O2 -o p3 dll.c -ldl
