# YesCoin script process
## First gain  super user permissions by running the command below
```sh
sudo su
```
### 1. Open Your VPS
```sh
cd YesCoin
```
### 2. Edit your env file, input your API ID and API HASH in the spaces provided for it, edit other enviromental variables your taste.
```sh
nano .env
```
### 3. After editing your .env file, save it:
CTRL O

ENTER 

CTRL X
### 4. Install requirementsts
```sh
python install.py
```
### 5. Run main.py
```sh
python main.py
```
### 6. Create a session
```sh
1
```
Enter a name for your session input any name you like

ENTER

enter your telegram phone number, include your country code while typing it. e.g 2348145698452

ENTER

check your telegram app for otp and input it

ENTER
### 7. Create a screen
```sh
screen -R Yescoin
```
### 8. Run main.py again
```sh
python main.py
```
### 9. Run clicker
```sh
2
```
CTRL AD
### 10. Close the VPS and open and run the next script
