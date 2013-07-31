DemoMsTest
==========

Dummy solution that implements unit tests using MsTest, also includes a .msbuild file with targets for build, test, cobertura analisys.

Open DemoMstes.msbuild file and edit the value of MsTestPath path to your local path.
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

Tested on:

- Windows 7 Enterprise SP 1 32bit
- Visual Studio 2010 Ultimate
