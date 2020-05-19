## Install Preview Version of Python SDK
run `install_env_track2.sh`(in linux)   
or you can install these packages using `pip install` from the `install/packages` directory by yourself (as listed in the script).

When installing on Windows, you might run into this error:

    ERROR: Could not install packages due to an EnvironmentError: [Errno 2] No such file or directory

To solve this, you'll need to remove the MAX_PATH limitation by setting the registry value `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem@LongPathsEnabled` to `1`.

Reference: [Installing Python 3.7 on Windows](https://docs.python.org/3.7/using/windows.html)
