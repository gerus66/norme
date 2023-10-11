## Norminette code style
Mandatory codestyle for all projects, written in `C language` at Ecole 42. \
_[full version in pdf](https://github.com/gerus66/norme/blob/master/norme.en.pdf)_
### Each *.c file
* has at most 5 function definitions

### Each function
* must be no longer than 25 lines
* can take at most 4 parameters
* can declare at most 5 variables

### Each variable
* should be declared at the beginning of function
* one declaration per line
* can't be assigned on declaration 

### Each line
* must be at most 80 columns wide

### Forbidden
* `for`, `goto`, `swith/case`
* nested ternary operators
* global variables
* any libraries
* any fuctions but a few basics, like _malloc()_, _free()_, _write()_, _read()_
