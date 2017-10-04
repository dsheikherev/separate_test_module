"as_separate_project" branch demonstrates how to separate Android Application code 
and Instrumentation Tests for this application as independent Android project.

This is possible if you are using:
  1. Android Studio 3.0 Beta 6 and higher
  2. Android Gradle Plugin: 'com.android.tools.build:gradle:3.0.0-beta6' and higher
  3. Gradle Wrapper: 4.1-all
It is impossible if you will use lower versions.

How to run tests:
  1. Create new configuration for the test module:
     In the configuration dropdown menu select "Edit Configurations..." to open the "Run/Debug Configurations" dialog.
     Click the "+" and select "Android Instrumented Tests".
     Change the name and select the right tests module in "Module" dropdown.
     Save the new configuration.
  2. Now run your newly created configuration to start tests.
