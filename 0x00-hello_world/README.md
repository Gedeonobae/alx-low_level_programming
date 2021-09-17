<h1>0x00. C - Hello, World</h1>
<h3>Tasks</h3>
* **0. Preprocessor **
  Write a script that runs a C file through the preprocessor and save the result into another file.

   * The C file name will be saved in the variable $CFILE
   * The output should be saved in the file c
  '''
julien@ubuntu:~/c/0x00$ cat main.c 
#include <stdio.h>

/**
 * main - Entry point
 *
 * Return: Always 0 (Success)
 */
int main(void)
{
    return (0);
}
julien@ubuntu:~/c/0x00$ export CFILE=main.c
julien@ubuntu:~/c/0x00$ ./0-preprocessor 
julien@ubuntu:~/c/0x00$ tail c
# 942 "/usr/include/stdio.h" 3 4

# 2 "main.c" 2


# 3 "main.c"
int main(void)
{
 return (0);
}
julien@ubuntu:~/c/0x00$ 
'''
