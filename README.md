# Command-line Speedtest

To use this script, please use these commands in this order.
```bash
sudo nano ~/.bashrc
```
Then at the end of the file, enter the following line:
```
alias speedtest="sudo mkdir -p /share/speedtest && sudo curl https://raw.githubusercontent.com/RogueEmailing/cli-speedtest/main/speedtest> | sudo python - --share --secure > /share/speedtest/result & echo You can view the result in this file: /share/speedtest/result"
```
Next you will need to type these commands:
```bash
sudo source ~/.bashrc
```
Now to run the speedtest whenever you need, you just type:
```bash
sudo speedtest
```
Now you are able to run a speedtest directly from your CLI on Linux.
