
Android Automatic Backup Sample
===================================

Sample demonstrating how to selectively disable Automatic
          Backups in Android M, either by adjusting the location where data
          files are stored or by using a custom XML configuration file.

Introduction
------------

This sample demonstrates how to selectively disable Automatic Backups in Android M, either by
adjusting the location where data files are stored using [getNoBackupFilesDir()][1], or by using a
custom XML configuration file.

This sample can also be used as a utility to test the behavior of the Automatic Backup feature.
Executing:

    adb shell bmgr restorecom.example.android.autobackup

from a terminal will cause the sample's data to be cleared and replaced with a copy from the backup
server.

[1]: http://developers.google.com/reference/android/content/Context.html#getNoBackupFilesDir()

Pre-requisites
--------------

- Android SDK v23
- Android Build Tools v23.0.0
- Android Support Repository

Screenshots
-------------

<img src="screenshots/1-main.png" height="400" alt="Screenshot"/> <img src="screenshots/2-settings.png" height="400" alt="Screenshot"/> 

Getting Started
---------------

This sample uses the Gradle build system. To build this project, use the
"gradlew build" command or use "Import Project" in Android Studio.

Support
-------

- Google+ Community: https://plus.google.com/communities/105153134372062985968
- Stack Overflow: http://stackoverflow.com/questions/tagged/android

If you've found an error in this sample, please file an issue:
https://github.com/googlesamples/android-Automatic Backup

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub. Please see CONTRIBUTING.md for more details.

License
-------

Copyright 2014 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
