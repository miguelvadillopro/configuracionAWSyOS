from google/cadvisor

RUN mount -o remount,rw '/sys/fs/cgroup'
RUN ln -s /sys/fs/cgroup/cpu,cpuacct /sys/fs/cgroup/cpuacct,cpu
