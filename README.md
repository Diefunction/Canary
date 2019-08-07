# Canary

The purpose of this tool is to bruteforce x64 Canary, Framepointer, return Address using multiprocessing

## Installation
```
apt-get update
apt-get install python3 python3-dev python3-pip git
pip3 install --upgrade git+https://github.com/arthaud/python3-pwntools.git
git clone https://github.com/DieFunction/Canary.git
```

### Examples
import it or just add
```python
if __name__ == '__main__':
  Canary('127.0.0.1', 1337, b'\x41' * offset, b'Bye')
```
after adding the main
```
python3 Canary.py
```
![Canary Example Image](https://raw.githubusercontent.com/DieFunction/Canary/master/img.png)
### About

HTB: https://www.hackthebox.eu/home/users/profile/47396 | https://www.hackthebox.eu/profile/47396 <br />
Twitter: @diefunction <br />
Discord: Diefunction#1337
