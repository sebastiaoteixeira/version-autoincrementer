# Version Autoincrementer
Simple bash scripts to autoincrement version in a version.h file for C projects.

## version.h
It's a code::blocks autoverioning like header file model that store project version data.

## incBuildCount.h
It should be called on every build, even if no changes have been made.

It can receive one parameter, target file ("version.h" by default).

## incVersion.h
It should be called on build, only if changes have been made.

It can receive one parameter, target file ("version.h" by default).
