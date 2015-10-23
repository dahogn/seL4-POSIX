# seL4-POSIX
seL4 POSIX
We basically achieved the POSIX interface related functions,Relevant methods are stored in libsel4support repository.
Uploaded files may be some missing, please don't direct execution.

Mainly including code file:
pthread_my.h:      POSIX Threading library header files, store the main thread structure
pthread_alloc.c:   Thread creation before environment initialization, as well as the methods 
                   of dealing with the related variables
pthread_create.c:  Thread creation and removed, and the realization of the thread priority methods
pthread_join.c:    The implementation of the thread to run method
libsync:           Communication between threads lock the implementation of the library
