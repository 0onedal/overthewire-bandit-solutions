# Bandit Level 0 → 1

## 🎯 Objective:
The password for the next level is stored in a file called `-` located in the home directory


## 🛠 Tools Used:
- SSH
- ```$ ls``` command
- ```$ cat``` command

## 📝 Steps:
1. Connect using SSH:  
```$ ssh  bandit0@bandit.labs.overthewire.org -p 2220 ```  
***```password is : bandit0```***
### 2. Use listing command:  
```$ ls ```
3. Display Regular File: 
```$ cat ./-```
> **note** ```./``` used to tell the ``cat`` command dash "-" is not a opation but is a file name
