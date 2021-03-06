# Introduction to kore mustach

`kore mustach` is a [kore](https://kore.io) integration of the C implementation
`mustach` [gitlab](https://gitlab.com/jobol/mustach), of [mustache](http://mustache.github.io "main site for mustache")
template specification.


## Using kore mustach

The file **src/mustach.h** is the main documentation. Look at it.

The current source files are:

- **src/mustach.c** core implementation of mustache in C
- **src/mustach.h** header file for core definitions
- **src/kore_mustach.c** implementation and integration of mustach with kore
- **gen_tmpl.sh** tool used to generate tmpl.c
- **src/tmpl.c** file generated by running gen_tmpl.sh
- **src/page.c** example usage of this implementation

To use this implementation simply copy src/mustach.c, src/mustach.h, src/kore_mustach.c
and gen_tmpl.sh.
Then run gen_tmpl.sh to link your assets/* with their respective file names.
