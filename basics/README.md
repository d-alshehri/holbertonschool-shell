pwd: a script that prints the absolute path name of the current working directory
ls: shows the files and folders in the directory you are currently in
cd ~: changes the working directory to the user's home directory
ls -l: display the current directory contents in a long format
ls -l -a: display the long format of the current directory contents, including the hidden files
ls -l -a -n: display the current directory contents in a long format that also shows user and group IDs numerically, including hidden files
mkdir /tmp/my_first_directory: creates a directory named my_first_directory in the /tmp/ directory
mv /tmp/betty /tmp/my_first_directory: move the betty file into the myfirstdirectory
rm /tmp/my_first_directory/betty: delete the file betty
cd -: changes the working directory to the previous one
ls -l -a . .. /boot: list all files in the current directory, the parent directory, and the /boot directory in long format
rm -r /tmp/my_first_directory: delete the directory my_first_directory that is in the /tmp directory