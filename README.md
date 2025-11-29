# Bandit Level 0 → 1

## 🎯 Objective:
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.


## 🛠 Tools Used:
- SSH
- ```$ ls``` command
- ```$ cat``` command

## 📝 Steps:
1. Connect using SSH:
```$ ssh  bandit0@bandit.labs.overthewire.org -p 2220 ```
```password is : bandit0```
