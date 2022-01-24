# 常用的环境变量

| 变量名                  | 代表的含义  					       |
| ----                    | ----         					       |
| HOSTNAME 	          | 对于批处理作业，此变量被设置为批处理脚本所执行节点的节点名 | 
| SLURM_JOB_CPUS_PER_NODE | 每个节点上分配给作业的CPU数				       |
| SLURM_TASKS_PER_NODE    | 每个节点加载的任务数，MPI指每个节点启动的MPI数目           |
| SLURM_JOB_NODELIST      | 作业分配的节点列表					       |
| SLURM_JOB_NUM_NODES     | 作业分配的节点数据 					       |
| SLURM_JOB_ID		  | 作业的JobID						       |
| SLURM_SUBMIT_DIR        | 提交作业时的job目录					       |
	
