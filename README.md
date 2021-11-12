# CINEMA MANAGER
---
## RUN ON LINUX SERVER
```bash
sudo mysql -u root -p
```
Enter password: root123

```bash
CREATE DATABASE theatre;
exit;
```
Run
```bash
sudo mysql -u root -p < initialise.sql
python3 app.py
```
---
## RUN ON WINDOWS

```bash
ssh  -N -f -L localhost:8081:localhost:5000 sang@128.199.128.140
```
Open web browser: localhost:8081

