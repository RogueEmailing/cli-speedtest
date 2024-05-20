# cli-speedtest

To use this script, please use these commands in this order.\n
`sudo nano ~/.bashrc`
Then at the end of the file, enter the following line:\n
`alias speedtest="mkdir -p /share/speedtest && curl https://raw.githubusercontent.com/RogueEmailing/cli-s> | python - --share --secure > /share/speedtest/result & echo You can view the result in this file: /share/speedtest/result"`
Next you will need to type these commands:\n
`sudo source ~/.bashrc`\n
`sudo speedtest`\n
Now you are able to run a speedtest directly from your CLI on Linux.