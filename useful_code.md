# Useful Code
### Here we'll add some useful snippets of code that you can use to help format your code!

* #### Getting multiple units of output from a block of code:
	- *Just two lines of code!*

    ```
    from IPython.core.interactiveshell import InteractiveShell

    InteractiveShell.ast_node_interactivity = "all"
    ```

	- *Put this in a block at the top of your notebook, and all subsequent blocks can output multiple things!*
	- *For more info, look [here](https://stackoverflow.com/questions/34398054/ipython-notebook-cell-multiple-outputs)*

* #### Uh-oh! What's the encoding of this file?!?!
	- *Go to command line*
	- *Type:* file \<filenamehere\>
	- *This will show you the encoding of the file!*
	- *Still doesn't work? Google is your friend!!*
