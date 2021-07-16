# python-password-checker

This is a personal password checker to check if your password have even been breached in data breach event. 
It uses haveibeenpwned API to securly check your password.

### Why use this instead of the one on haveibeenpwned website?


Although it uses the same method as password checker on https://haveibeenpwned.com website it's more secure because the data doesn't travel through the internet.


## Required tools

* Python interpreter instaled on your computer
* requests module intsalled on your computer
  ```pip install requests```


## How to use?

### Windows
1. Copy the **checkmypass.py** file into your local computer.
2. Open the Windows PowerShell in the file directory
3. Run ```python checkmypass.py <password>``` in the command line (*this can take many arguments*)

**Example:**
```python checkmypass.py password123 qwerty lignaigawdbnaguj```


### MacOS/Linux

1. Copy the **checkmypass.py** file into your local computer.
2. Open the terminal in the file directory
3. Run ```python3 checkmypass.py <password>``` in the command line (*this can take many arguments*)

**Example:**
```python3 checkmypass.py password123 qwerty lignaigawdbnaguj```
