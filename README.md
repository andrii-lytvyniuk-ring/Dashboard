# Dashboard
This repository is a part of proposal of main app modularization.
Sample application has 3 features: *dashboard*, *login* and *settings*.
Also there is a core module which is *legacyapp* and 
Each feature has 1 activity and *global-navigator* module which serves to navigate between features.

This project is an example of repository for one feature.
It contains only source code of *dashboard* feature, rest is linked as dependencies.
This project has mandatory git submodule of [Connector repository](https://github.com/andrii-lytvyniuk-ring/Connector/blob/master/README.md)
So don't forget to call **git submodule update --init** after repository cloned.

## master branch
*master* branch contains version of app which is usual .apk file

## feature_bundle branch

feature_bundle is alternative way to build application. This version allows to build feature bundle.
