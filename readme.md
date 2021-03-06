## Install the *Preview* Version of the Python SDK
On Linux or MacOS, run `install_env_track2.sh` from the `install` directory.

You can also install the packages using `pip install` from the `install` directory by yourself:

    pip install azure_core-1.4.1-py2.py3-none-any.whl
    pip install azure_mgmt_compute-0.1.0-py2.py3-none-any.whl
    pip install azure_mgmt_resource-0.1.0-py2.py3-none-any.whl
    pip install azure_mgmt_network-11.0.0-py2.py3-none-any.whl
    pip install azure-identity

When installing on Windows, you might run into this error:

    ERROR: Could not install packages due to an EnvironmentError: [Errno 2] No such file or directory

To solve this, you'll need to remove the MAX_PATH limitation by setting the registry value `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem@LongPathsEnabled` to `1`.

Reference: [Installing Python 3.7 on Windows](https://docs.python.org/3.7/using/windows.html)

## Install the *Current* Version of the Python SDK
On Linux or MacOS, Run `install_env_track1.sh` from the `install` directory.

You can also install the packages using `pip install` from the `install` directory by yourself (as listed in the script).
