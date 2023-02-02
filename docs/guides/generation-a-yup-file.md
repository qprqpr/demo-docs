---
sidebar_position: 1
title: Generating a YUP file
---

# Generating a YUP file

Invoke the following command:

```
yupgen.exe -path .\builds\release -proj <PROJECT> -ver <VERSION>
```

As a result, in the current catalog, there should appear a file of the form `a2e61e8a631c353b59091a6b17ef64f7f358b70d.yup`

That file contains the description of your build together with the project name, version, a list of all files, and a hash of their content. Being that YUP contains hashes of all the files from the .\builds\release catalog, you must not change the content of that catalog after the build.

---

# Uploading a build

```
yupload.exe a2e61e8a631c353b59091a6b17ef64f7f358b70d.yup -check 0 -src .\builds\release -deploy -tracker http://yuptracker.gaijinent.com:27022/announce -dev https://gdn.gaijin.net/yuitem
```

This command will request a login and a password of the user on whose behalf the operation will be performed, then it will register the build in GDN and perform the build upload, making sure that all the data has been uploaded successfully and can be available for download.
