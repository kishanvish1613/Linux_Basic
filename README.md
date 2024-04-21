# Linux

```
For any Linux command you can check the usage and different input flags it expects by runnig the command followed by `--help`
```

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