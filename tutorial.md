# Directories and Files in the Terminal

When coding, the terminal can be an extremely helpful when organizing and testing out your code. Here are some tricks you can use to do that.

## 1. Directories
When you first open the terminal you will probably see something like this:
``` ~ ```
This just indicates that you're in the user *directory*, which holds most of your front end files on your computer. 

- **Directory**: a folder
- **Commands**: keywords that are typed in the terminal to cause a certain action, such as creating a file or directory. You must click enter after every command.

You can see what directories are in your user directory by typing `ls` and click enter. You can also use the *command* `pwd`.

- This is how you create a directory:
``` mkdir directory-name ```

- This is how you enter a directory: ```cd directory-name```

> You can combine these two actions into one by typing `take`.

- This is how you leave the directory:
```cd ..```

- This is how you delete a directory:
```rm -r directory-name```

## 2. Files
Files are quite self-explanatory but very different from directory. You cannot "enter" a file in the terminal, you can only create, name, remove, move and run the file. Changes within the file have to be done on VSCode or another editor the file uses.

- This is how you create a file:
```touch file-name```

- This is how you delete a file:
```rm file-name```

- This is how you run a file:
```node file-name```
> You can only run a file if you are in the directory of said file. Check to see in which directory you are with `pwd` and check to see if the file is in the directory with `ls`.