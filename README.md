# can-msgs

This message is for can communication.

## member variable description

|name|type|description|
|-|-|-|
|header|std_msgs/Header|msg header|
|id|uint32|can id|
|data|array of uint8|can data|
|is_extended|bool|extend frame flag|
|is_remote|bool|remote frame flag|

## build

```sh
# in any workspace
cd src
git clone https://github.com/naga-karupi/can-msgs.git
cd ../
colcon build
```
