py3.5-ci
========

This is a super small Python 3.5 image based on the original
python:3.5-alpine image from the Docker library.

This fork only exists because CI builds with Gitlab fail because
the original image does not include bash.

Should fix this Gitlab CI build problem:
```
[8] System error: exec: "bash": executable file not found in $PATH
```
