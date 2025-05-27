```
open the vscode container

open a terminal in vscode container

cd to app

open `/zmk/app/build` on the host outside docker to get files

west build -d build/left -b nice_nano_v2 -- -DSHIELD=ogre_ergo_left

west build -d build/right -b nice_nano_v2 -- -DSHIELD=ogre_ergo_right
```
