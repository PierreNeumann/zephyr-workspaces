# zephyr-workspaces
Workspaces for differents versions of Zephyr RTOS


## Initialization

```shell
# initialize the workspace
west init -m git@github.com:PierreNeumann/zephyr-workspaces.git --mr zephyr-v3.4 zephyr-workspace
# update Zephyr modules
cd zephyr-workspace
west update
```