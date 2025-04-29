# Commonly Used Linux Commands

## Printing currently logged in user
```
whoami
```
![image](https://github.com/user-attachments/assets/6bf47cd5-a768-4405-8a7b-1938024b9b80)

## Printing your present working directory
```
pwd
ls
cd Downloads
pwd
```
![image](https://github.com/user-attachments/assets/c40f3f06-0f3e-4328-873f-11020f0fd427)


## Listing files and directories
```
ls
```
![image](https://github.com/user-attachments/assets/251b3e03-7c9e-4d99-b3e4-29d6f5b57f9d)

Long list will list files and folders in list format
```
ls -l
```
![image](https://github.com/user-attachments/assets/31cd1689-bb41-4cbf-bcee-f64e6058a770)

Listing hidden files and folders
```
ls -lha
```
![image](https://github.com/user-attachments/assets/e3c705c5-0885-418a-a882-0b804631e55f)

## Create a new directory named sriram in your home directory
```
cd ~
pwd
mkdir -p sriram
ls
```
![image](https://github.com/user-attachments/assets/51b76d85-55f0-48e0-a2d8-7cf208b193ab)

## Creating a new user as an administrator
```
sudo useradd -m nitesh
```

Changing the password for newly created nitesh user, when it prompts for password type root as the password
```
passwd nitesh
```

