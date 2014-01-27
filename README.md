# Wordnik open-source components

## Overview
This project contains a number of tools for common routines, mongodb usage & administration, and swagger

### To build
You'll need Java6 to compile this.

The compile step may throw unrelated errors if running on Java 5 such as:

Detected sbt version 0.12.2
Can't start up: not enough memory


./sbt compile

This will build all the OSS modules.  You can see more on each modules home page:

[common-utils](https://github.com/wordnik/wordnik-oss/blob/master/modules/common-utils/README.md) Common convienence utilities

[mongo-utils](https://github.com/wordnik/wordnik-oss/blob/master/modules/mongo-utils/README.md) Core MongoDB utilities

[mongo-admin-utils](https://github.com/wordnik/wordnik-oss/blob/master/modules/mongo-admin-utils/README.md) Set of tools to maintain a production MongoDB deployment

