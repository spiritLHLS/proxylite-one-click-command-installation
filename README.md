# proxylite-one-click-command-installation

## Language

[English](README.md) | [中文文档](README_zh.md)

## **Introduction**

The proxylite is an option that allows users to earn money by sharing your traffic.

You'll receive 

4512 К (corporate) - about 45.12RUB - 0.64USD

6761 K (mobile, wireless) - about 67.61RUB - 0.97USD

1176 K (hosting) - about 11.76RUB - 0.17USD

for the 1G traffic you share.

This script supports data center network or home bandwidth.

This is the **first one-click installation script of the whole network** to automatically install dependencies and pull and install the latest docker, and the script will continue to be improved according to the platform update.

It has below features:

1. Automatically install docker based on the system, and if docker are already installed, it will not installed again.

2. Automatically select and build the pulled docker image according to the architecture, without the need for you to manually modify the official case.

3. Use Watchtower for automatic mirror update without manual update and re-entry of parameters.

(Watchtower is a utility that automates the updating of Docker images and containers. It monitors all running containers and related images, and automatically pulls the latest image and uses parameters when initially deployed to restart the corresponding container.)

## Notes

- Verified on AMD64 and ARM
- Try it if you are interested via my --> [referrals](https://proxylite.ru/?r=JLEU2ZZQ) <--, you will get 60 coin.

## Install

### Interactive installation

```shell
curl -L https://raw.githubusercontent.com/spiritLHLS/proxylite-one-click-command-installation/main/proxylite.sh -o proxylite.sh && chmod +x proxylite.sh && bash proxylite.sh
```

After the registration link is registered, copy the token in the upper left corner, run my script, paste the token, and press Enter to start the installation.

### One command installation

```shell
curl -L https://raw.githubusercontent.com/spiritLHLS/proxylite-one-click-command-installation/main/proxylite.sh -o proxylite.sh && chmod +x proxylite.sh && bash proxylite.sh -t 000000000
```

Change to your ID at the end of this command

## Uninstall

```shell
bash proxylite.sh -u
```

uninstall service

## Experience

The benefits of this script are extremely low

## Disclaimer

This program is for learning purposes only, not for profit, please delete it within 24 hours after downloading, not for any commercial use. The text, data and images are copyrighted, if reproduced, please indicate the source.

Use of this program is subject to the deployment disclaimer. Use of this program is subject to the laws and regulations of the country where the server is deployed, the country where it is located, and the country where the user is located, and the author of the program is not responsible for any misconduct of the user.

