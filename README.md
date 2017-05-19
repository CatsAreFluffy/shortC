# shortC
shortC is a "programming language" for code golfing. Frequently-used C functions/keywords are shortened into capital letters.

To build the 'interpreter', type `make`.

To compile a shortC program, type `./shortC <SHORTSOURCEFILE.sc >CSOURCEFILE.c && gcc CSOURCEFILE.c`.

Here are the conversions that shortC currently performs:

 - A -> `int main(int argc, char **argv){`
 - C -> `char `
 - D -> `#define `
 - E -> ` else `
 - F -> `if(`
 - G -> `getchar()`
 - H -> `switch(`
 - J -> `puts(`
 - I -> `int `
 - L -> `long `
 - M -> `strcmp(`
 - O -> `for(`
 - P -> `putchar(`
 - Q -> `gets(`
 - R -> `printf(`
 - S -> `strlen(`
 - T -> `return `
 - U -> `usleep(`
 - W -> `while(`
 - X -> `while(1){`
