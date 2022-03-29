# Issue with rules_docker 0.23.0 on macOS

This repository fails to build on macOS, while it builds successfully on Linux. Building is done by

```
bazel build ...
```

If rules_docker 0.22.0 is loaded in WORKSPACE, the build succeeds on macOS.

