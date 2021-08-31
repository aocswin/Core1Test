# Core1Test

This is a test file for Core 1.

Copy the MainActivityTest.kt file into your androidTest directory. <AndoridStuiodProjects>/<projectname>/app/src/test/java/<package sub folders>/MainActivityTest.kt
Edit Pakage name: Edit MainActivityTest.kt line 1 'package au.edu.swin.sdmd.core1sample' to match your environment. See your MainActivity.kt package name. 
Add test module library to dependency list: Insert `  androidTestImplementation 'androidx.test:rules:1.4.0'  ` to the dependencies section of your Gradle Module build file. build.gradle (Module: <appname>.app). 

To run the tests, click on the arrows next to `class MainActivityTest`. This will open an emulator (or use your device) and run through the steps in the tests. Test statuses will be shown at the bottom of the IDE (under Run). 

If you are unable to run the tests, the test cases are described in the files for you to test manually.

Note at this stage colour is unable to be reliably tested.
