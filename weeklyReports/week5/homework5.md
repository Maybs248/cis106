# Definition, Usage, and Example of the following commands

## Definitions
- **mkdir:** Allows users to make or create new directories 
- **touch:** Allows users to create files 
- **rm:** Allows users to delete files
- **rmdir:** Allows users to remove directories 
- **mv:** Allows users to rename files and directories, also allows users to move files and directories from one directory to another
- **cp:** Allows users to copy 
- **ln:** Allows users to create a link between files
- **man:** Allows users to display the user manual  

## Usage and Examples
When you use **mkdir** you are essentially making a directory in your home directory, Example: **`mkdir IceCream`**.
When you use **touch** you are essentially making a file inside your directory, Example: **`touch IceCream/sprinkles`**.
When you use **rm** you are removing files from your directory, Example: **`rm ~/IceCream/sprinkles`**.
When you use **rmdir** you are removing a directory from your directory, Example: **`rm -r ~/IceCream`**.
When you use **mv** you are moving your files/directories into another directory, Example: **`mv IceCream/fudge.png IceCream-images/`**.
When you use **cp** you are copying your files into a directory, Example: **`cp bananasplit-sprinkles-hotfudge.png Pictures/IceCreamMenu/`**.
When you use **ln** you are creating a link between files, Example: **`ln -s milkshake.txt sundae.txt`**.
Lastly, when you use **man** the user manual will pop up to help you with what you're looking for, Example: **`man`** or **`man man`**.

## Brace expansion and how to use it
Brace expansion is used to generate arbitrary strings. These strings are used to **ALL** possible combinations surrounding prefixes and suffixes. It may appear as a series of comma-separated strings or an expression of braces. In order to use a brace expansion you must at least add an unquoted opening and closing brace and at least one unquoted comma. A way to use it by doing it like this: **`echo 1{2,3,4,5}6`**. Then the outcome would look like this: **`126, 136, 146, 156`**. If you don't want something to be a part of the brace expansion you can do that in a single command. For example, I don't want 77 to be a part of my expansion so I will type the command along the lines of this, **`/{77/1{44,55,66}2`**.

