iNTERACTIVE oPEN sOURCE
====

Open Source iOS Feature Requests

This open source app was created to allow iOS developers to self-promote homebrew technologies. This app is available for download on the Apple App Store: https://itunes.apple.com/us/app/open-source/id883033675

We are in no way associated with Apple(c) nor do we intend to infringe on any of their legal rights.

===
##Installation

Obtain the Source:

  1) Git Command Line: 
  ```
  git clone --recursive https://github.com/jcope/OpenSource.git
  ```
---
##Modifying Demos

Because I have chose to fork the Demo's into submodules, things can get complicated. After all, preserving submodules with git requires some sort of expert knowledge.

Be sure to 're-attach' the submodule branchs IFF you want to make changes in a forked branch:

```
cd demos/[SUB_MODULE]
git checkout master
```


---
##Install Your Own Demo:

1) Import your new source code as a new folder in the >ios/Demos directory. Include all resources and media that may be require. Try to be kind to the directory source tree.

2) Create a class that implements the DemoApp Delegate. See comments for protocal descriptions.

3) Navigate to DemoNC+Apps.m and import your DemoApp Delegate.

4) Initialize and add your demo to the demoAppArray.

5) Enjoy :-)

---
##Legal

This project and its code is open source and is forever intended to stay that way. All code and examples have been collected from the open source community and therefor is a collection of various licences. Each component is suggested to include their own license, restrictions, and rights which will be applied when permitted. When no license can be found, the GNU General Public License (GPLv3) is assumed to be applied.
