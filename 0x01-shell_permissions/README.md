SHELL PERMISSONS

su betty >>>Change your user ID to betty.

whoami >>> Print the effective userid of the current user.

groups >>> Print all the groups the current user is part of.

chown betty hello >>>  Changes the owner of the file hello to the user betty.

touch hello >>> Create an empty file called hello.

chmod u+x hello >>> Adds execute permission to the owner of the file hello.

chmod u+x hello>>> Add execute permission to the owner and the group owner, and read permission to other users, to the file hello.

chmod 007 hello>>> Add execution permission to the owner, the group owner and the other users, to the file hello.

chmod 753 hello>>> Sets the mode of the file hello to this: -rwxr-x-wx

chmod 007 hello >>>Owner: no permission at all

       >>> Set the mode of the file hello the same as olleh’s mode 
       
chmod a+X *>>> Add execute permission to all subdirectories of the current directory for the owner, the group owner and all other user

mkdir -m 751 my_dir >>> Create a directory called dir_holberton with permissions 751 in the working directory.

chgrp school hello >>> Change the group owner to holberton for the file hello.

chgrp school hello >>> Change the owner to betty and the group owner to holberton for all the files and directories in the working directory.

chown -h vincent:staff _hello >>>  Change the owner and the group owner of the file _hello to betty and holberton respectively.

chown -h vincent:staff _hello >>> Change the owner of the file hello to betty only if it is owned by the user guillaume.

telnet towel.blinkenlights.nl >>>  Play the StarWars IV episode in the terminal.
