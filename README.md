This is just the original [tdlib](https://github.com/tdlib/td/) (the library
for building Telegram clients) + the spec file, which allows to build tdlib
in the [SailfishOS community OBS](https://build.sailfishos.org/) with a config
like this:

```
<services>
  <service name="tar_git">
    <param name="url">https://github.com/monich/tdlib.git</param>
    <param name="branch">master</param>
    <param name="revision">0ce806c</param>
  </service>
</services>
```
