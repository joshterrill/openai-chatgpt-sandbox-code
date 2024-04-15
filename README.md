

```bash
> cat /etc/hosts

# Kubernetes-managed hosts file.
127.0.0.1	localhost
::1	localhost ip6-localhost ip6-loopback
fe00::0	ip6-localnet
fe00::0	ip6-mcastprefix
fe00::1	ip6-allnodes
fe00::2	ip6-allrouters
10.230.93.13	e26f2ab5-5143-45ed-99b4-27193badbd58

> env

KUBERNETES_SERVICE_PORT=443
KUBERNETES_PORT=tcp://172.16.0.1:443
KERNEL_CALLBACK_ID=8e48e3a6-6d3c-46f9-95dd-8ecec21995a9
MPLBACKEND=module://matplotlib_inline.backend_inline
HOSTNAME=e26f2ab5-5143-45ed-99b4-27193badbd58
SHLVL=0
PYTHON_PIP_VERSION=24.0
LD_LIBRARY_PATH=:/usr/local/lib
HOME=/home/sandbox
OLDPWD=/
ENVIRONMENT=prod
GPG_KEY=A035C8C19219BA821ECEA86B64E628F8D684696D
PAGER=cat
PYDEVD_DISABLE_FILE_VALIDATION=1
FORCE_COLOR=1
PYTHON_GET_PIP_URL=https://github.com/pypa/get-pip/raw/dbf0c85f76fb6e1ab42aa672ffca6f0a675d9ee4/public/get-pip.py
PYTHONMALLOC=malloc
TERM=xterm-color
KUBERNETES_PORT_443_TCP_ADDR=172.16.0.1
PATH=/home/sandbox/.local/bin:/usr/local/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
PROCESS_MEMORY_LIMIT=4000000
KUBERNETES_PORT_443_TCP_PORT=443
KUBERNETES_PORT_443_TCP_PROTO=tcp
LD_PRELOAD=/usr/lib/x86_64-linux-gnu/libjemalloc.so.2
LANG=C.UTF-8
FEATURE_SET=general
DEBIAN_FRONTEND=noninteractive
CLICOLOR_FORCE=1
PYTHON_VERSION=3.11.8
PYTHON_SETUPTOOLS_VERSION=65.5.1
KUBERNETES_SERVICE_PORT_HTTPS=443
KUBERNETES_PORT_443_TCP=tcp://172.16.0.1:443
ACE_SELF_IDENTIFY=bb68eb4a-bf1d-45c4-a116-6bf0bf3e185c
GIT_PAGER=cat
PWD=/home/sandbox
MALLOC_CONF=narenas:1,background_thread:true,lg_tcache_max:10,dirty_decay_ms:5000,muzzy_decay_ms:5000
KUBERNETES_SERVICE_HOST=172.16.0.1
CLICOLOR=1
PYTHON_GET_PIP_SHA256=dfe9fd5c28dc98b5ac17979a953ea550cec37ae1b47a5116007395bfacff2ab9
JPY_PARENT_PID=3
PYDEVD_USE_FRAME_EVAL=NO
FLAG=This is not a flag. You are expected to be able to see this.

> uname -a

Linux e26f2ab5-5143-45ed-99b4-27193badbd58 4.4.0 #1 SMP Sun Jan 10 15:06:54 PST 2016 x86_64 GNU/Linux



```