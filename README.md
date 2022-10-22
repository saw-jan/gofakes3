
![Logo](/GoFakeS3.png)

This is a fork of [johannesboyne/gofakes3](https://github.com/johannesboyne/gofakes3).

Notable differences:

* Use modified xml library to handle more control chars
* Func `getVersioningConfiguration` will return empty when unversioned
* New func in `backend` interface: `CopyObjcet`
* Support authentication with AWS Signature V4 