# ESD (exception stacktrace dump)

Библиотека основанная на boost::stacktrace

## Зависимости

Boost\
C++20+

## Использование в проекте

```cpp
import esd;

/* ... */

try /* something */
catch (/* one more something */)
{
    esd::show_exception_stacktrace();
}
```

В cmake:

```cmake
add_target_stacktrace_dump_lib_on_debug(<your target>)
```
