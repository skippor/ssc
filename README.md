# ssh tool

1. put .sscconfig to /root
2. add ssh host in .sscconfig
3. put ssc-prompt to /etc/bash_completion.d/

## usage: 
    ssc <name>                  - ssh connect to remote host
    ssc <name> -p <filename>    - put file to /tmp on remote host 
    ssc <name> -g <filename>    - get file from remote host to current directory
