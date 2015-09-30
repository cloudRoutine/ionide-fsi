# Ionide-FSI


The F# Interactive Panel for the [Ionide](http://ionide.io) plugin suite.

The FSI Panel is currently readonly ( input, syntax highlighting, and code completion coming later )

The commands for FSI are:

| Command                |   Function                                  |
|:---------------------- |---------------------------------------------|
| `FSI : Open`           | Open the REPL Panel                         |
| `FSI : Send Line`      | Send the line the cursor is on to the REPL  |
| `FSI : Send Selection` | Send the selected text to the REPL          |
| `FSI : Send File`      | Evaluate the entire `.fsx` file in the REPL <br>  (_ this will not work with `.fs` and `.fsi` files_  ) |
| `FSI : Reset Repl`     | Clear the REPL of all text and evaluation results |     


**_NOTE_** --

The Ionide-FSI plugin will not function properly unless F# has been installed on machine already. If the location of FSI is not part of you path you need to provide this plugin the location of FSI.exe
