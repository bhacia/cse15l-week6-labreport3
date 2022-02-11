# Streamline `ssh` Configuration
This will be a tutorial to show you how to long into `ieng6` much easier **and** faster!

## Steps
1. In VS Code, open a folder named `.ssh`.

![Image](https://bhacia.github.io/cse15l-week6-labreport3/vscode-open-ssh-folder.png)

2. See if you have a file named `config`.

![Image](https://bhacia.github.io/cse15l-week6-labreport3/vscode-see-if-you-have-config-file.png)

If you do, great! Continue onto step 5!
If you don't, continue onto step 3!

3. Make the `config` file manually.

![Image](https://bhacia.github.io/cse15l-week6-labreport3/vscode-make-config-file.png)

Here, I used `ni` in the command line to make the file since I'm on windows, but you
could also use different commands such as `vim` on other devices, or even just clicking
the `New File` option in VS Code next to the `.ssh` folder name!

4. Open, edit, and save the `config` file.


![Image](https://bhacia.github.io/cse15l-week6-labreport3/vscode-open-and-edit-config-file.png)

Remember that `wi22` is replaced by the time you're taking this class, and `apl` is
replaced by the letters in your course-specific account! Also, you can simply save
the file by typing `ctrl+S`, or by clicking `File` then `Save`.

5. Try the `ssh ieng6` command to log into the server!

![Image](https://bhacia.github.io/cse15l-week6-labreport3/vscode-ssh-ieng6-command.png)

See how much easier and faster that is?!

6. Log out of the server by typing `exit` in the command line.

7. Open a different folder and use the `scp` command to copy a file to the server. Then use the
`ssh ieng6` command again to log onto the server and use the `ls` command to see if the file
you moved is there.

![Image](https://bhacia.github.io/cse15l-week6-labreport3/vscode-scp-file.png)

## Congrats!
Now that `ssh ieng6` makes things easier, the `scp` command is also easier! We **no longer**
have to type out ALL of our information again! :D
