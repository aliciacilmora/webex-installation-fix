# Webex Installation Fix

If you encounter the error while installing Webex:
webex depends on libgl1-mesa-glx; however: Package libgl1-mesa-glx is not installed.


You can fix it by installing the required package manually from an older version of Ubuntu.

## Steps to Fix:

1. Download the `libgl1-mesa-glx` package:
   ```bash
   sudo wget http://de.archive.ubuntu.com/ubuntu/pool/universe/m/mesa/libgl1-mesa-glx_23.0.4-0ubuntu1~22.04.1_amd64.deb
   ```

2. ```bash
    sudo apt install ./libgl1-mesa-glx_23.0.4-0ubuntu1~22.04.1_amd64.deb
    ```

3.  ```bash
    sudo apt dpkg -i Webex.deb
    ``` 