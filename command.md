

## apply for node
srun -N 1 -n 1 -p dgx2 --gres=gpu:1 --pty /bin/bash

srun -p arm128c256g --pty /bin/bash

srun -p arm128c256g -n 60  --pty /bin/bash

scontrol update job 12345 priority=1500

salloc -p debug -n 2 /bin/bash

salloc -p dgx2 -N 1  -n 4 --gres=gpu:2 /bin/bash

srun -p pmemtest -n 48 --reservation=pmem --pty /bin/bash

srun -p cpu -N 2 --exclusive --pty /bin/bash


## scontrol
查看预约节点
scontrol show reservation
