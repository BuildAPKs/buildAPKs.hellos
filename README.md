# [buildAPKs.hellos](https://github.com/BuildAPKs/buildAPKs.hellos)
Android APK app sources that build in [Termux](https://github.com/termux) in Amazon, Android and Chrome. 

[This repository](https://github.com/BuildAPKs/buildAPKs.hellos) is a submodule for [buildAPKs](https://github.com/BuildAPKs/buildAPKs).  In order to install it in its' proper place to attempt to make these applications on smartphone, tablet an TV, copy and paste the following into [Termux](https://github.com/termux):

```

   apt install curl 

   curl -O https://raw.githubusercontent.com/BuildAPKs/buildAPKs/master/setup.buildAPKs.bash

   bash setup.buildAPKs.bash

   ~/buildAPKs/scripts/bash/build/build.hellos.bash

```
To see all possible APK projects run ` cat ma.bash ` in the root directory of this project.   Enjoy!
<!--README.md EOF-->
