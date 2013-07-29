DemoMsTest
==========

Dummy solution that implements unit tests using MsTest, also includes a .msbuild file with targets for build, test, cobertura analisys.

Open a console, cd to folder path and run command:
```
msbuild DemoMsTest.msbuild /t:CI
```

The previous MsBuild target, compile the solution, run unit tests, perform cobertura analisys and generate report to folder /reports.
