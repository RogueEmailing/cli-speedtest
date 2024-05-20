# cli-speedtest

To use this script, please use these commands in this order.
`sudo nano ~/.bashrc`
Then at the end of the file, enter the following line:
`alias speedtest="mkdir -p /share/speedtest && curl https://raw.githubusercontent.com/RogueEmailing/cli-s> | python - --share --secure > /share/speedtest/result & echo You can view the result in this file: /share/speedtest/result"`
Next you will need to type these commands:
`sudo source ~/.bashrc`
`sudo speedtest`
Now you are able to run a speedtest directly from your CLI on Linux.