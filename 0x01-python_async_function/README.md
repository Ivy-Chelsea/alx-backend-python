## PYTHON ASYNC

File | Definition
---- | ----------
[0-basic_async_syntax.py](./0-basic_async_syntax.py) | Asynchronous coroutine that takes in an integer argument wait_random that waits for a random delay between 0 and ma_delay seconds and eventually returns it
[1-concurrent_coroutines.py](./1-concurrent_coroutines.py) | Function that:<br>~ Import wait_random from [0-basic_async_syntax.py](./0-basic_async_syntax.py).<br>~ Spawns wait_random n times with specified max_delay.
[2-measure_runtime.py](./2-measure_runtime.py) | Script that:<br>~ Imports ***wait_n***.<br>~ Create function ***measure_time*** that measures total execution time for ***wait_n*** and returns ****total_tme*** as a float.
[3-tasks.py](./3-tasks.py) | Script containing function ***task_wait_random*** that takes an integer ***max_delay*** and returns a ***asyncio.Task***
[4-tasks.py](./4-tasks.py) | Script containing function that is similar to ***wait_n*** but ***task_wait_random*** is called
