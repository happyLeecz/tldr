# chgrp

> Change group ownership of files and folders.

- Change the owner group of a file/directory:

`chgrp {{group}} {{path/to/file_or_directory}}`

- Recursively change the owner group of a folder and its contents:

`chgrp -R {{group}} {{path/to/folder}}`

- Change the owner group of a symbolic link:

`chgrp -h {{group}} {{path/to/symlink}}`

- Change the owner group of a file/directory to match a reference file:

`chgrp --reference={{path/to/reference_file}} {{path/to/file_or_directory}}`
