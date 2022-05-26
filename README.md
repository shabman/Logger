# Logger
Basic C++ Logger


```cpp
setLevel(int code);
```
- The logging level to be set.
- 4 presets are
  - Normal
  - Info
  - Warning
  - Error

```cpp
setMessage(std::string);
```
- The message to be displayed

```cpp
log(void);
```
To activate the logging.
