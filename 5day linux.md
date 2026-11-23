## Permissions

chmod is the file command that will allow you to manage permissions of file and directories. 
> in this **ch** stands for change AND **mod** is also referred as permissions on Linux

to change a permission of any file, use chmod | ugoa-user, group, other, all | operator +-= | rwx | file or directory name. 
` chmod g+w sales.txt`  = this will add write permission to the group to which sales.txt belongs to . 
---
chgrp will change the group of the file
`chgrp sales sales.log` this will add sales group to this file 


### Contents of the files
`cat file_name` - this will display contents of the file.

`more file_name` - Browser through text file. 

`head fileName` - will display first 10 lines of file only. n\
`tail fileName` - will display last 10 line of file only.


`tail -f fileName` - this will follow the file and show you all the changes file is going through live

