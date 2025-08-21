
# Pylot - Web Performance Tool

Corey Goldberg (2007-2010)

This is a very old project originally hosted on [Google Code](https://code.google.com/archive/p/pylt).

Archived here for posterity.

----

### Pylot (Python Load Tester) - Web Performance Tool

Pylot is a tool for testing the performance and scalability of web services.
It runs HTTP load tests, which are useful for capacity planning, benchmarking,
analysis, and system tuning. Pylot generates concurrent load (HTTP Requests),
verifies server responses, and produces reports with metrics. Tests suites are
executed and monitored from a GUI.

### License

GNU GPLv3

### Components

- Pylot Engine and CLI: requires Python 2.5+
- Pylot GUI (optional): requires wxPythton
- Pylot Results Graphing (optional): requires Matplotlib

### Features

- HTTP and HTTPS (SSL) support
- multi-threaded load generator
- automatic cookie handling
- response verification with regular expressions
- execution/monitoring console
- real-time stats
- results reports with graphs
- custom timers
- GUI mode
- shell/console modes
- cross-platform
