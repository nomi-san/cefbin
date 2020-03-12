# CEFBin
C/C++ header & pre-built binary for CEF Win32

### Resources

- [Cef SDK](https://www.nuget.org/packages/cef.sdk)
- [Cef Redist x86](https://www.nuget.org/packages/cef.redist.x64)
- [Cef Redist x64](https://www.nuget.org/packages/cef.redist.x86)

### Directory

```erlang
cef3.xxxx.xxxx/
      |----include/...                                  -> header files
      |----resources/...                                -> resources files
      |----bin/                                         -> binaries & locales
            |----debug/ & release/
            |      |----vsxxxx/
            |      |      |----libcef_dll_wrapper.lib   -> static lib for C++
            |      |----libcef.lib                      -> linking lib
            |----libcef.dll                             -> dynamic linking binary
            ...
```

### Download

#### Visit my [repo's releases](https://github.com/wy3/cefbuild/releases) or download below.

| CEF | Chromium | x86 | x64 |
|-|-|-|-|
|3.3239.1723|63.0.3239|[download](https://github.com/wy3/cefbuild/releases/download/cef3.3239.1723/cef3.3239.1723_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.3239.1723/cef3.3239.1723_x64.7z)|
|3.3239.1716|63.0.3239|[download](https://github.com/wy3/cefbuild/releases/download/cef3.3239.1716/cef3.3239.1716_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.3239.1716/cef3.3239.1716_x64.7z)|
|3.3202.1686|62.0.3202|[download](https://github.com/wy3/cefbuild/releases/download/cef3.3202.1686/cef3.3202.1686_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.3202.1686/cef3.3202.1686_x64.7z)|
|3.2987.1601|57.0.2987|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2987.1601/cef3.2987.1601_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2987.1601/cef3.2987.1601_x64.7z)|
|3.2987.1597|57.0.2987|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2987.1597/cef3.2987.1597_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2987.1597/cef3.2987.1597_x64.7z)|
|3.2883.1552|55.0.2883|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2883.1552/cef3.2883.1552_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2883.1552/cef3.2883.1552_x64.7z)|
|3.2883.1545|55.0.2883|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2883.1545/cef3.2883.1545_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2883.1545/cef3.2883.1545_x64.7z)|
|3.2785.1486|53.0.2785|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2785.1486/cef3.2785.1486_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2785.1486/cef3.2785.1486_x64.7z)|
|3.2785.1482|53.0.2785|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2785.1482/cef3.2785.1482_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2785.1482/cef3.2785.1482_x64.7z)|
|3.2785.1478|53.0.2785|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2785.1478/cef3.2785.1478_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2785.1478/cef3.2785.1478_x64.7z)|
|3.2704.1432|51.0.2704|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2704.1432/cef3.2704.1432_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2704.1432/cef3.2704.1432_x64.7z)|
|3.2704.1418|51.0.2704|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2704.1418/cef3.2704.1418_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2704.1418/cef3.2704.1418_x64.7z)|
|3.2623.1401|49.0.2623|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2623.1401/cef3.2623.1401_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2623.1401/cef3.2623.1401_x64.7z)|
|3.2623.1396|49.0.2623|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2623.1396/cef3.2623.1396_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2623.1396/cef3.2623.1396_x64.7z)|
|3.2526.1362|47.0.2526|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2526.1362/cef3.2526.1362_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2526.1362/cef3.2526.1362_x64.7z)|
|3.2454.1344|45.0.2454|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2454.1344/cef3.2454.1344_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2454.1344/cef3.2454.1344_x64.7z)|
|3.2357.1287|43.0.2357|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2357.1287/cef3.2357.1287_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2357.1287/cef3.2357.1287_x64.7z)|
|3.2272.32|41.0.2272|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2272.32/cef3.2272.32_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2272.32/cef3.2272.32_x64.7z)|
|3.2171.2069|39.0.2171|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2171.2069/cef3.2171.2069_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2171.2069/cef3.2171.2069_x64.7z)|
|3.2171.1979|39.0.2171|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2171.1979/cef3.2171.1979_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2171.1979/cef3.2171.1979_x64.7z)|
|3.2171.1972|39.0.2171|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2171.1972/cef3.2171.1972_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2171.1972/cef3.2171.1972_x64.7z)|
|3.2171.1949|39.0.2171|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2171.1949/cef3.2171.1949_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2171.1949/cef3.2171.1949_x64.7z)|
|3.2062.1898|37.0.2062|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2171.1949/cef3.2062.1898_x86.7z)|[download](https://github.com/wy3/cefbuild/releases/download/cef3.2171.1949/cef3.2062.1898_x64.7z)|

