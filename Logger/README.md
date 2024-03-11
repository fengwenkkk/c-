class LogLevel：定义日志级别。并提供将日志级别与文本之间的互相转化

class Logger：日志器。定义日志级别，设置输出地，设置日志格式。

class LogEvent：记录日志事件。主要记录一下信息

class LogEventWarp：日志事件包装器。将logEvent打包，可以直接通过使用该类完成对日志的定义。

class LogFormatter：日志格式化。

class LogAppender：日志输出目标。有两个子类 class StdoutLogAppender 和 class FileLogAppender，可以分别输出到控制台和文件

class LoggerManager：日志管理器。单列模式.

# class LogLevel（日志级别）

枚举

```
/* 打印级别 */
#define LOG_NULL            0
#define LOG_DETAIL          1
#define LOG_INFO            2
#define LOG_WARN            3
#define LOG_ERROR           4
#define LOG_FAIL            5
#define LOG_FATAL           6
```

