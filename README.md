# Lazy Log

Logger package wrapper on ZeroLog for Golang

```go
logger := lazylog.CreateLogger(&lazylog.LoggerSettings{
	Debug: true,            // log level
	FileLogger: true,       // creates file for log
	FilePath: "info.log",   // path to log file
})

logger.Info().Interface("some_var", "some_value").Msg("Hello World")
```
