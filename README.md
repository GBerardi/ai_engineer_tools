# AI engineer tools

Content
- [screen basics](#screen-basics)
- [docker basics](#docker-basics)

## screen basics

| action | command |
| ----- | ----- |
| sessions list | ```screen -ls``` |
| new named section | ```screen -S session_name``` |
| detach | ```ctrl + a, d``` |
| attach | ```screen -r session_name``` |
| close attached session | ```exit``` |
| close detached session | ```screen -XS session_name quit``` |

## docker basics
| action | command |
| ----- | ----- |
| containers list | ```docker ps -a``` |
| stop container | ```docker stop container_name``` |
