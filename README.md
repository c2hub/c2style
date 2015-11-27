This is an implementation of one of the tools specified at
http://github.com/c2lang/c2compiler

C2Style only finds and parses recipe.txt and executes astyle
on all the files in the target specified for formatting.

It is also possible to format all targets in a recipe.txt.

Versions for both Windows and Linux provided. I don't know
how to work with Mac OSX, so I don't know what the differences
are. Hopefully Linux version will work on Macs.

##Installation

In order to compile c2style, latest version of c2c is required.
Installation guide can be found at http://github.com/c2lang/c2compiler .

Once you have c2c installed, compilation of c2style is very easy
(This installation steps are for installing to $HOME/c2style,
you can, however, replace the folder with whichever one you want)

```
cd path/to/folder/where/c2style/is
export C2_LIBDIR=path/to/folder/where/c2style/is/
cd Linux OR cd Windows
c2c
```

A folder called output should be generated which contains c2style executable.
You can then add it to the path, link it to some bin folder or just carry
it over to where you need to use c2style.

Note that c2style requires astyle to function. One can find information
about astyle at http://astyle.sourceforge.net/ . astyle should be in path
in order for c2style to be able to use it.