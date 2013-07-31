DemoMsTest
==========

Dummy solution that implements unit tests using MsTest, also includes a .msbuild file with targets for build, test, cobertura analisys.

Open DemoMstes.msbuild file and edit <MsTestPath>...</MsTestPath> to your path to mstest.exe.
```
...
<MsTestPath>C:\Program Files\Microsoft Visual Studio 10.0\Common7\IDE\mstest.exe</MsTestPath>
...
```

Open a console, cd to folder path and run command:
```
msbuild DemoMsTest.msbuild /t:CI
```

The previous MsBuild target, compile the solution, run unit tests, perform cobertura analisys and generate report to folder /reports.
