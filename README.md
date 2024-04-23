# Linux

## Note:

For any Linux command you can check the usage and different input flags it expects by runnig the command followed by `--help`

## Commands

- `pwd` : This represents what is the current directory at.

- `ls` : you can print the content of the current directory we are in. All the files and sub-directories will be printed.

  - `ls -l` : list down more details about the file such as owner, permissions, data, etc.

  - `ls -lh` : works like `ls -l` but also gives the size of the file.

  - `ls -a` : also list files and folder starting with `.` .

- `cd` : This can help you to move into a folder and move out of a folder.

  - `cd ..` : if you want to jump one folder back from current directory.

  - `cd ../..` : if you want to make two jumps back from current directory.

  - `cd ~` : from any directory this will help you to come back to the home directory.

  - `cd directory1/directory2` : we can move into internal subdirectories directly by separating them with a forward slash `/`.

  ### Note:

  - `~` : This tilda refers to the home directory

  - `/` : This slash leads you to the root directory

  Relative path: it describes the location of a file/folder with respect to current folder.
  Whereas in an absolute path we mention the location from home directory or root directory.

  when you give an absolute path of a file/folder that means you will give the whole path of that file/folder, Whereas in the relative path you do jumps with respect to the current folder.

- `clear` : clear the working space by actually moving you to the top of the current shell.

- `mkdir <folder name>` : this help us to make a folder

- `touch <file name>` : we can create a brand new blank file.

- `touch <folder name/<file name>` : we can create a file without `cd` the dirctory. 

- `cat <file name>` : prints the whole content of the file.

- `rm <file name>` : this command deletes the file.

- `rmdir <folder name>` : this command deletes a empty folder.

- `rm -r <folder name>` : the `-r` flag enables `rm` to recursively delete all the content of the folder and than delete the folder. 

## Vim

- `vim <file name>` : this will create a file (if it doesn't exist) and then open it in the vim editor in normal mode. In normal mode we can not do changes to the file but we can read it and navigate it. You can also do `vi <file name>` to do same things.

- Now after opening vim if want to start making changes you need to, first of all, make it change the mode from `normal` to `insert` mode. To go into the insert mode we can press `i`. If you want to come back to `normal` mode then press `Esc` key.

- `esc + :q` : if you want to exit a file we can do this.

- `esc + :q!` : if file has some changes and we want to exit without saving changes.

- `esc + :wq` : if file has changes and we want to save it and then exit.

- `l` : in normal mode, you can move the cursor right.

- `h` : in normal mode, you can move the cursor left.

- `j` : in normal mode, you can move the cursor down.

- `k` : in normal mode, you can move the cursor up.

- You can use normal right, left, up, down arrow keys as well to nevigate.

- `dd` : in normal mode, it will delete the line the cursor is currently at.

- `gg` : in normal mode, it will make cursor go on the first line.

- `G` : in normal mode, it will make cursor go on the last line.

- `w` : in normal mode, it will make you jump one word.

- `2w` : in normal mode, it will make you jump two words.

- `d2w` : then this will delete two words.

- `esc + :s/foo/bar` : in normal mode, To search for the occurrence of the string `foo` in the current line and replace it with `bar`.

- `esc + :%s/foo/bar` : in normal mode, to replace all occurrences of `foo` with `bar`.

- `yw` : in normal mode, it copies one word.

- `yy` : in normal mode, it copies a whole line.

- `p` : for pasting in normal mode.

- ### Vim config file

  - `vim ~/.vimrc` : this command open vim config file, set these values.


  ```
    :syntax on

    set number

    set autoindent

    filetype plugin indent on

    set tabstop=4 softtabstop=4

    set shiftwidth=4

    colorscheme murphy

    :se mouse+=a
  ```

- `tail -n 2 <file name>` : Prints last 2 lines of "file", useful for checking recent entries.

- `head -n 2 data.txt` : Displays first 2 lines of "file", ideal for quick file previews.