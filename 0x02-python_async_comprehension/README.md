## ASYNC COMPREHENSION

File | Description
---- | -----------
[0-async_generator.py](./0-async_generator.py) | A coroutine function ***async_generator*** that:<br>~ Takes no arguments.<br>~ Loops 10 times.<br>~ Each time it loops it asynchronously waits 1 second then yields a random number between 0 and 10
[1-async_comprehension.py](./1-async_comprehension.py) | Script that:<br>~ Imports ***async_generator*** from [0-async_generator.py](./0-async_generator.py)<br>~ Writes a coroutine function ***async_comprehension*** that takes arguments.<br>~ The coroutine collects 10 random numbers using async comprehension over ***async_generator*** then returns the 10 radom numbers.
[2-measure_runtime.py](./2-measure_runtime.py) Script that:<br>~ Import ***async_comprehension*** from [1-async_comprehension.py](./1-async_comprehension.py).<br>~ Writes a ***measure_runtime*** coroutine that executes ***async_comprehension*** 4 times in parallel using ***asyncio.gather****
