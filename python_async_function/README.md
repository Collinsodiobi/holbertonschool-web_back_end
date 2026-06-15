# Python - Async

## Description
This project covers asynchronous programming in Python using `asyncio`. It explores `async`/`await` syntax, running concurrent coroutines, creating asyncio tasks, and using the `random` module to generate random delays.

## Learning Objectives
At the end of this project, you should be able to explain:
- `async` and `await` syntax
- How to execute an async program with `asyncio`
- How to run concurrent coroutines
- How to create `asyncio` tasks
- How to use the `random` module

## Requirements
- Ubuntu 20.04 LTS, Python 3.8
- pycodestyle (version 2.5.x)
- All files must start with `#!/usr/bin/env python3`
- All files must end with a new line
- All files must be executable
- All functions and coroutines must be type-annotated
- All modules, classes, and functions must have documentation

## Tasks

### 0. The basics of async
File: `0-basic_async_syntax.py`

A coroutine `wait_random` that waits for a random delay between 0 and `max_delay` seconds (default 10) and returns that delay.

### 1. Let's execute multiple coroutines at the same time with async
File: `1-concurrent_coroutines.py`

A coroutine `wait_n` that spawns `wait_random` `n` times with the specified `max_delay`, and returns the list of delays in ascending order.

## Author
collins odi obi
