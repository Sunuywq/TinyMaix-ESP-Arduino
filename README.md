# TinyMaix-ESP-Arduino
Port [TinyMaix](https://github.com/sipeed/TinyMaix) to esp32-c3

# How to Build
install platformio and run `run.bat`

# Result
| config | mnist | cifar | vww96  | mbnet128 | Note |
| ------ | ----- | ----- | ------ | -------- | ---- |
| O0 CPU | 6  | 169 | 1430 | 2599   |      |
| O1 CPU | 6  | 127 | 1551 | 2370   |      |

# Question
result shows O1 is slower than O0.