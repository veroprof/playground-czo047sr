# Welcome!

This C template lets you get started quickly with a simple one-page playground.

```C runnable
#include <stdio.h>
#include<string.h>
#include<mallloc.h>

int main() {
	char * pt=NULL;
	pt=(char *)malloc(10);
	strcpy(pt,"bonjour");
	puts(pt);
	
}

```

# Advanced usage

If you want a more complex example (external libraries, viewers...), see the [official documentation](https://tech.io/playgrounds/408/tech-io-documentation).
