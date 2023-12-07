# HR650X-IPMI-Auto-Fan

Use Python to automatically set fan speed for Lenovo HR650X Server


This should also works for HR630X and some other Lenovo servers with the same ipmi raw code.

# Requirements

1. install ipmitool on your system
2. install pyyaml: `pip install pyyaml`

# Usage

```bath
python ipmi_manager.py
```


Tested on Python 3.8


# TODO

1. wrap these codes into a docker container
2. support multiple devices
