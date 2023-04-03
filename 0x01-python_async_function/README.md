## PYTHON ASYNC

File | Definition
---- | ----------
[0-basic_async_syntax.py](./0-basic_async_syntax.py) | Asynchronous coroutine that takes in an integer argument wait_random that waits for a random delay between 0 and ma_delay seconds and eventually returns it
[1-concurrent_coroutines.py](./1-concurrent_coroutines.py) | Function that:<br>~ Import wait_random from [0-basic_async_syntax.py](./0-basic_async_syntax.py).<br>~ Spawns wait_random n times with specified max_delay.
[
