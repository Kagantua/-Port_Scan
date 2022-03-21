# Port_Scan

A simple python tool to easily get the opened port

# Features

Multi-threading

# Basic usage

```
 ____            _   ____
|  _ \ ___  _ __| |_/ ___|  ___ __ _ _ __   ___ _ __
| |_) / _ \| '__| __\___ \ / __/ _` | '_ \ / _ \ '__|
|  __/ (_) | |  | |_ ___) | (_| (_| | | | |  __/ |
|_|   \___/|_|   \__|____/ \___\__,_|_| |_|\___|_|   v3.0


[Usage]
    python portscaner_v3.py -i ip -p [port_scope|top_num] [-t thread_num]
    python portscaner_v3.py -u url -p [port_scope|top_num] [-t thread_num]

[Example]
    python3 portscaner_v3.py -i 127.0.0.1 -p 1000 -t 100
    python3 portscaner_v3.py -u https://www.baidu.com -p 1-65535

[Value]
    ip              0.0.0.0-255.255.255.255
    top_num         [50|100|1000(default)]
    port_scope      1-65535
    thread_num      [int|10(default)]
```

# Example

```
python port_sacanber3.py -i 127.0.0.1 -p 1000 -t 10

 ____            _   ____
|  _ \ ___  _ __| |_/ ___|  ___ __ _ _ __   ___ _ __
| |_) / _ \| '__| __\___ \ / __/ _` | '_ \ / _ \ '__|
|  __/ (_) | |  | |_ ___) | (_| (_| | | | |  __/ |
|_|   \___/|_|   \__|____/ \___\__,_|_| |_|\___|_|   v3.0

[RESULT]

   135 [OPEN]
   443 [OPEN]
   902 [OPEN]
  1001 [OPEN]
  1556 [OPEN]
  3306 [OPEN]
  5357 [OPEN]
 10000 [OPEN]
[end time] 168.5435492992401s
```







