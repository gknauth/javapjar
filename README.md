# javapjar

You know you can use `javap` to decompile a Java `.class` file.  Have you ever wanted to decompile every class file in a Jar?  This little utility will let you do that.

Usage:

    javapjar /path/to/foo.jar

`javapjar` will go through every `.class` file in the Jar, except for inner classes (classes with `$` in the filename), and run `javap` on it.  What you end up with is output for the whole Jar file, which might be useful if you are trying to figure out what is in (or not in) a particular Jar file.

## Author

Geoffrey S. Knauth `<geoff@knauth.org>`
