chmod u+x {actualfilename} for checking ./{filename}

0) "**echo $(pwd)**" => prints the absolute path name of the current working directory
1) "**ls -1**" => Display the contents list of your current directory
2) "cd ~" => changes the working directory to the user’s home directory (for checking source ./2-bring_me_home)
3) "**ls -l**" => Display current directory contents in a long format.
4) "**ls -la**" => Display current directory contents, including hidden files (starting with .). Use the long format.
5) "**ls -lna --numeric-uid-gid**" => Display current directory contents. => Long format, with user and group IDs displayed numerically, And hidden files (starting with. 
6) "**mkdir /tmp/my_first_directory**" => Create a script that creates a directory named my_first_directory in the /tmp/ directory. fc(file /tmp/my_first_directory/)
7) "**mv /tmp/betty /tmp/my_first_directory**" => Move the file betty from /tmp/ to /tmp/my_first_directory.
8) "**rm /tmp/my_first_directory/betty**" => Delete the file betty.
9) "**rmdir /tmp/my_first_directory**" => Delete the directory my_first_directory that is in the /tmp directory.
10) "**cd -**" =>  changes the working directory to the previous one.
11) "**ls -la . .. /boot**" =>  lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12) "**file /tmp/iamafile**" => prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
13) "**ln -s /bin/ls __ls__**" => Create a symbolic link to /bin/ls, named __ls__.
14) "**cp -u *.html ..**" =>  copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
15) "**mv $(find . -type f -name '[A-Z]*') /tmp/u**" => moves all files beginning with an uppercase letter to the directory /tmp/u
16) "**rm *~**" => deletes all files in the current working directory that end with the character ~
17) "**mkdir -p welcome/to/school**" => creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. 
