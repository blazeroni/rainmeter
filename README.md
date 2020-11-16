This Rainmeter fork enables changing Game Mode via [bangs](https://docs.rainmeter.net/manual/bangs/):
```
Z:\Path\to\Rainmeter.exe !EnableGameMode
Z:\Path\to\Rainmeter.exe !DisableGameMode
```

This functionality is intended to be used by external scripts.  Purpose-built skins could use `!EnableGameMode`, but cannot disable it because they will be disabled themselves.

##### Patch Installation
Download `Rainmeter.dll` from a release and drop it in your existing install directory.  Alternatively, you can build from source and do the same thing.

To restore the original functionality just reinstall Rainmeter.

Note: The provided `.dll` is 64-bit.  Only use a `.dll` for the same Rainmeter version and build.

----

*Rainmeter* is a desktop customization tool for Windows. For more information and downloads, visit [rainmeter.net](http://rainmeter.net/).

For build instructions, see [this](https://github.com/rainmeter/rainmeter/blob/master/Docs/Building.md).