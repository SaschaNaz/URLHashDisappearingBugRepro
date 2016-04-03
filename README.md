# URLHashDisappearingBugRepro
A repro for UWP url hash bug

### Environment

Windows 10 Insider Preview build 14295

### Steps to repro
1. Click the first link and check your browser navigates to example.com/#example. (This fails on 14295.)
2. Click the second link and check your browser navigates to example.com/?example. (This succeeds on 14295.)
