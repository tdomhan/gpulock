gpulock
=======

python gpu locking for linux

Usage
-----

```python
from gpulock import GPULock

with GPULock() as lock:
    print lock.device_id
    #do stuff on the GPU...
```
