# [synano](https://github.com/IBPX/synano)
`synano` is a collection of syntax files for the `nano` text editor.
It is public domain under the [CC0 license](http://creativecommons.org/publicdomain/zero/1.0/). For more info, see `LICENSE.txt`.

## Installation

### Locating your nanorc

If you want a system-wide install of `synano`, your **nanorc** is usually `/etc/nanorc` or similar.

For a user specific install, it's generally placed in `~/.nanorc`.

### Choosing a file

You can either use `synano.nanorc`, which is a file containing all the syntaxes, or choose an individual syntax from `syntax/`.

### Include method

Download the file you want and place it somewhere publicly accessable _(/usr/share/nano/, prehaps?)_.
Then edit your **nanorc** and add this line:  

     include /wherever/you/put/the/file/you/chose.nanorc

### Copy-paste method

Alternatively, you can copy the contents of the file you chose and append it to your **nanorc**.
