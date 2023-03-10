## General
| **PLUGIN** | **API** | **VERSION** |
| :-----: | :-----: | :-----: |
| FixItemUI | 4.0.0 | 1.0.0 |

## Feature
- This is a plugin that allows players to repair items with `money` or `exp`
- You can repair an item but don't change the `name`, `lore` or `enchantment` that it was in before 
- `Parcent` in config is the amount or exp that you have to pay for each item's durability 
- `Price` in the config is the minimum amount a player needed to be able to use  `Fix Money` or `Fix Exp`
<br>

- Idea by: `PeaceVN`

<br>

## Config
<details>
 <summary>Click to see</summary>
 
 ```yaml
 ---
#
#░█████╗░░█████╗░██████╗░███████╗
#██╔══██╗██╔══██╗██╔══██╗██╔════╝
#██║░░╚═╝██║░░██║██║░░██║█████╗░░
#██║░░██╗██║░░██║██║░░██║██╔══╝░░
#╚█████╔╝╚█████╔╝██████╔╝███████╗
#░╚════╝░░╚════╝░╚═════╝░╚══════╝
#
#
#██████╗░██╗░░░██╗
#██╔══██╗╚██╗░██╔╝
#██████╦╝░╚████╔╝░
#██╔══██╗░░╚██╔╝░░
#██████╦╝░░░██║░░░
#╚═════╝░░░░╚═╝░░░
#
#
#
#░█████╗░██╗░░░░░██╗░█████╗░██╗░░██╗███████╗██████╗░████████╗██████╗░░█████╗░███╗░░██╗
#██╔══██╗██║░░░░░██║██╔══██╗██║░██╔╝██╔════╝██╔══██╗╚══██╔══╝██╔══██╗██╔══██╗████╗░██║
#██║░░╚═╝██║░░░░░██║██║░░╚═╝█████═╝░█████╗░░██║░░██║░░░██║░░░██████╔╝███████║██╔██╗██║
#██║░░██╗██║░░░░░██║██║░░██╗██╔═██╗░██╔══╝░░██║░░██║░░░██║░░░██╔══██╗██╔══██║██║╚████║
#╚█████╔╝███████╗██║╚█████╔╝██║░╚██╗███████╗██████╔╝░░░██║░░░██║░░██║██║░░██║██║░╚███║
#░╚════╝░╚══════╝╚═╝░╚════╝░╚═╝░░╚═╝╚══════╝╚═════╝░░░░╚═╝░░░╚═╝░░╚═╝╚═╝░░╚═╝╚═╝░░╚══╝

menu:
  title: "§l§a•[ §bMenu §cRepair Item§a ]•"
  exit: "§l§a• §cExit§a •"
not-items-or-armor: "§l§cIn your hand is not §bTools or §bArmor"

money:
  title: "§l§a•[ §cRepair Item §bMoney§a ]•"
  button-not-enough: "§l§a• §cFix §bMoney§a •\n§bYou Don't Have Enough Money To Repair"
  button-enough: "§l§a• §cFix §bMoney§a •"
  confirm: "§l§a• §cConfirm §a•"
  no: "§l§a• §cNo §a•\n§bFor me back"
  percent: 1 #Each durability percentage is equal to x(number) exp, please default to 1!!
  price: 1000
  successfully: "§l§aYou have repaired item §6{item_name} a for §b{price} money"
  fail: "§l§cYou do not have enough §6{price} §cmoney to fix this item!"
exp:
  title: "§l§a•[ §cRepair Item §bEXP§a ]•"
  button-not-enough: "§l§a• §cFix §bExp§a •\n§bYou Don't Have Enough Exp To Repair"
  button-enough: "§l§a• §cFix §bExp§a •"
  confirm: "§l§a• §cConfirm §a•"
  no: "§l§a• §cNo §a•\n§bFor me back"
  percent: 1 #Each durability percentage is equal to x(amount) exp, please default to 1!!
  price: 10
  successfully: "§l§aYou have repaired item §6{item_name} a for §b{price} exp"
  fail: "§l§cYou do not have enough §6{price} §cexp to fix this item!"

#NOTE
#{price} = repair money
#{item_name} = item name
```
</details>

## Command and Permission
>- /fix - Open menu fix item
>- fixitem.command
<br>

## Plugin Support
- [FormAPI](https://github.com/jojoe77777/FormAPI)(jojoe77777)
- [EconomyAPI](https://github.com/onebone/EconomyS)(onebone)
<br>

## Download

- If you use a computer, you probably already know how to download
- If you are using Android or you don't know how to download it on my computer, please click <a href="https://github.com/Clickedtran/FixItemUI/archive/refs/heads/Master.zip">to here</a>
- If you are Vietnamese, download the Vietnamese version <a href="https://github.com/Clickedtran/FixItemUI/releases/download/Vietnamese/FixItemUI_Vie.zip">in here</a>

## Install
>- Step 1: Click <a href="https://github.com/Clickedtran/FixItemUI/archive/refs/heads/Master.zip">here</a> to download plugin
>- Step 2: Unzip and cut files to folder `plugins/`
>- Step 3: Restart server and play
