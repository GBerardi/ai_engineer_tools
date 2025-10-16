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
| attach to the main process of a container (exit will also exit the container) | ```docker attach container_name``` |
| detach from a container without exiting it | ```ctrl (hold) + P than Q``` |
| attach to a container creating a new shell | ```docker exec -it <container_name_or_id> /bin/bash (for a Bash shell)``` |
