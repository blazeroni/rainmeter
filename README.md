*Rainmeter* is a desktop customization tool for Windows. For more information and downloads, visit [rainmeter.net](http://rainmeter.net/).

For build instructions, see [this](https://github.com/rainmeter/rainmeter/blob/master/Docs/Building.md).

----

This fork enables changing Game Mode via [bangs](https://docs.rainmeter.net/manual/bangs/):
```
Z:\Path\to\Rainmeter.exe !EnableGameMode
Z:\Path\to\Rainmeter.exe !DisableGameMode
```

This functionality is intended to be used by external scripts.  Purpose-built skins could use `!EnableGameMode`, but cannot disable it because they will be disabled themselves.
