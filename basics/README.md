pwd: a script that prints the absolute path name of the current working directory
ls: shows the files and folders in the directory you are currently in
cd "$(getent passwd "$(id -u)" | cut -d: -f6)": changes the working directory to the user's home directory
<<<<<<< HEAD

=======
>>>>>>> 77b3f4f (My second commit)
