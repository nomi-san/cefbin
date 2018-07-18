# CEFBuild
CEF's include header + binary built for Windows.

### Sources


### Directory

```erlang

cef3.xxxx.xxxx/
      |----include/                                              -> include header files
      |----resources/
      |     |----locales/                                        -> language packages
      |     |----x86/ or x64/
      |     |      |----debug/ or release/
      |     |      |      |----vsxxxx/                           
      |     |      |      |      |----libcef_dll_wrapper.lib     -> libcef_dll_wrapper, static lib for C++
      |     |      |      |----libcef.lib                        -> libcef static library
      |     |      |----libcef.dll                               -> libcef bibary
      |     |      |...
      |     |...
      |...
      
```
