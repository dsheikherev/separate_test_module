"as_separate_module" branch demonstrates how to separate Android Application code 
and Instrumentation Tests for this application as independent test module placed outside the application folder.

This is possible if you are using:
  1. Android Studio 2.3.3
  2. Android Gradle Plugin: 'com.android.tools.build:gradle:2.2.3'. This functionality is broken in version of plugin from 2.3.0.
  3. Gradle Wrapper: 3.3-all

How to run tests:
  1. Create new configuration for the test module:
     In the configuration dropdown menu select "Edit Configurations..." to open the "Run/Debug Configurations" dialog.
     Click the "+" and select "Android Instrumented Tests".
     Change the name and select the right tests module in "Module" dropdown.
     Save the new configuration.
  2. Now run your newly created configuration to start tests.
