
![Logo](/GoFakeS3.png)

This is a fork of [johannesboyne/gofakes3](https://github.com/johannesboyne/gofakes3).

Notable differences:

* Use [minio/xxml](github.com/minio/xxml) as xml parser 
* Func `getVersioningConfiguration` will return empty when unversioned
* New func in `backend` interface: `CopyObjcet`