fabric-api (AlexIIL's fork)
==============================

## This fork

###  [1.16-alexiil-single-project](https://github.com/AlexIIL/fabric-api/tree/1.16-alexiil-single-project) (Warning: Incomplete)!

This branch is an attempt to allow expsting fabric-api as a single eclipse project. This means:

 + (Positive) Per-project settings apply to all of fabric-api, rather than needing to be confiured indivudally.
 + (Positive) You can clone fabric-api multiple times and rename each clone (in the same workspace).
 - (Negative) Access Wideners apply to every module, rather than just the module they are for. (I haven't fixed this for "gradle build" yet).
 - (Negative) Modules can access any other module when edited in eclipse. However "gradle build" works correctly.
