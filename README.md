# AI engineer tools

Content
- [cpdex basics](#codex)
- [screen basics](#screen-basics)
- [docker basics](#docker-basics)
- [vim basics](#vim-basics)

## Codex

### skills
- ask codex to write the SKILL.md given the pipeline of a repeated task
- when indicating the pipeline try to be the most specific as possible, you do this once well and it is repeated forever
- skills can be saved in ~/.codex/skills/skill-name/SKILL.md, keep only one level of directory after "skills" and use "-" instead of "_"

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
| install tmux inside the container to have multiple shells that lasts after detaching | ```apt-get update && apt-get install -y tmux``` |

## vim basics

| action | command |
| ----- | ----- |
| copy text chuncks into vim | ``` :set paste ``` |
| multi line comment | ``` ctrl + v, arrow up or down to select lines, shift+i, #, esc ``` |
| multi line decomment | ``` ctrl + v, arrow up or down to select lines, x ``` |
