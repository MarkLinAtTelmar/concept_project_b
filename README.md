# concept_project_b

use git submoudle 
init
```
git submodule add https://github.com/MarkLinAtTelmar/share_module_x.git

git submodule init
git submodule update
```

pull
```
cd share_module_x
git pull https://github.com/MarkLinAtTelmar/share_module_x.git main
```

commit, push
```
cd share_module_x
git push -a -m "<message>"
git push origin HEAD:main
```
