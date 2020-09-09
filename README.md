# EasyShell
Easy reverse shell generator

Based on https://github.com/0xroman1/LazyShell


Available shells:
- bash
- netcat
- python
- php
- ruby

### Installation
```bash
./install.sh
```

### Usage
Generates choosen reverse shell with random PORT and IP from eth0
```bash
python3 shell.py
```

Generates choosen reverse shell with specified PORT and IP
```sh
python3 shell.py --ip 13.13.37.37 --port 1337
```
