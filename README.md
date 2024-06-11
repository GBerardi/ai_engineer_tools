# AI engineer tools

Content
- [screen basics](#screen-basics)

## screen basics

| action | command |
| ----- | ----- |
| sessions list | ```screen -ls``` |
| new named section | ```screen -S session_name``` |
| detach | ```ctrl + a, d``` |
| attach | ```session -r session_name``` |
| close attached session | ```exit``` |
| close detached session | ```screen -XS session_name quit``` |
