## Linux Dependencies:

Please install the following packages

~~~ patchelf
~~~

On OpenSuse Leap 42.2 this package is available on the official repositorym
patchelf is necessary to install *casanova*

## INSTALLING CASANOVA

On this approach, we're working with the [Casanova project](https://github.com/kaspervd/casanova), 
which is added as a submodule on this repository.

Execute the following commands in order to initialize casanova submodule and download it

~~ git submodule init
   git submodule update
~~

Follow the instructions on the README file you will find on the casanova folder. Keep
in mind that you must have installed the patchelf program, you can install it using
the package manager provided by your GNU/Linux distribution.

