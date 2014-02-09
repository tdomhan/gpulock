gpulock
=======

Python gpu locking for linux. Adapted version of: [http://homepages.inf.ed.ac.uk/imurray2/code/gpu_monitoring/]

Usage
-----

```python
from gpulock import GPULock

with GPULock() as lock:
    print lock.device_id
    #do stuff on the GPU...
```
