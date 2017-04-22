This is an implementation of one of the tools specified at
http://github.com/c2lang/c2compiler

C2Style only finds and parses recipe.txt and executes astyle
on all the files in target targets.

It is also possible to format all targets in a recipe.txt.

## Installation

In order to compile c2style, the latest version of c2c is required.
Installation guide can be found at http://github.com/c2lang/c2compiler .

Once you have c2c installed, compilation of c2style is very easy
(This installation steps are for installing to $HOME/c2style,
you can, however, replace the folder with whatever you want)

```
cd $HOME
git clone https://github.com/luciusmagn/c2style
cd c2style
export C2_LIBDIR=$HOME/c2style/c2libs	#c2style needs its interface files
cd Linux OR cd Windows
c2c
```

A folder called output should be generated which contains c2style executable.
You can then add it to the path, link it to some bin folder or just carry
it over to where you need to use c2style.

Note that c2style requires astyle to function. One can find information
about astyle at http://astyle.sourceforge.net/ . astyle should be in path
in order for c2style to be able to use it.
