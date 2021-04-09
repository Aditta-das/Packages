# Packages
```
pip install folder
```

##Example

start create
```
from folder.cp import createproject
createproject("YOURPROJECTNAME", False) ## for default folder alignment
```

for custom align
```
from folder.cp import createproject
createproject("YOURPROJECTNAME", True) ## for custom folder alignment
```

if folder name already exists
```
Choose Different Name. Folder Already Exists, Are you want to delete previous one?
Press Y to YES: Y
Press N to NO: N
Press: 

Directories for default


	YOURPROJECTNAME
	|
	|___ input
	|___ models
	|___ create
	|___ notebooks
	|___ src
	|___ LICENCE
	|___ README.md
```

Directories For custom

```
	YOURPROJECTNAME
	No. of subfolders: 4 (as an example)
	folder_0 : models
	folder_1 : deep learning
	folder_2 : machine learning
	folder_3 : basic
	|
	|___ models
	|___ deep learning
	|___ machine learning
	|___ basic
	|___ LICENCE
	|___ README.md
```
