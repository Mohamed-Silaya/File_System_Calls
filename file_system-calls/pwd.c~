#include<stdio.h>
#include <unistd.h>
#include <string.h>

int main(int argc, char *argv[])
{
    char buf[100];
    char size = 100;


    for (int i = 0; i < argc; i++) {
	printf("argv[%d]=%s\n ", i, argv[i]);
    }
    char *stat = NULL;

    if (argc == 1) {
	stat = getcwd(buf, size);
	if ((stat != NULL)) {
	    printf("%s\n", buf);
	} else
	    printf("try again\n");
    } else
	return -1;

    return 0;
}
