# Android development ant files for NetBeans

## What are these files for?

Some weird guys (like me) develop for Android, but are not too fond of coding in Eclipse or Android Studio for some reasons. Also I happen to like tinkering with stuff like this, so here's the result. This is a collection of several files which help programmers to set up Android development in NetBeans IDE for those who like this IDE. These files contain additional ant targets for use in NetBeans. Also the subfolder `tests` contains files to ease up setting up test projects.

## How to use them?

1. Create an Android project (or upgrade the existing one) to use ant. When creating a new project, this can be done with the command `android create project`. 
2. Create a free-form project in NetBeans using the generated build file.
3. Add the files into the project folder.
4. Now you can add these additional ant targets as custom commands in the project properties.

### Added commands for regular projects:

 - Launching the app;
 - Rebuilding resources;
 - Saving release APK in a separate folder with ProGuard mapping (all releases are named according to the version tag);
 - Debugging.

### Added commands for test projects:

 - Debugging;
 - Running a single file;
 - Debugging a single file.

## License

Copyright 2014 Alexander Gazarov. Contact at malcolm [dot] soft [at] gmail [dot] com.

This work is free. It comes without any warranty, to the extent permitted by applicable law.
You can redistribute it and/or modify it under the terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See [http://www.wtfpl.net/](http://www.wtfpl.net/) for more details.