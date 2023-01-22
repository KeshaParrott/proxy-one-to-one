## ⚡️ Quick start

### Requirements

1. check that 3proxy allready install, this way

```
/usr/bin/3proxy -v
```

2. verify that the directory exists

```
ls -ld /usr/local/3proxy/
```

3. now you can run the script
```
git clone https://github.com/KeshaParrott/proxy-one-to-one.git
cd proxy-one-to-one 
./createProxy <UserName> <Password> <Port> <In_IP_Address> <Out_IP_Address>
```

4. For check

###### to create
```
./createProxy ready9 12345 40010 65.109.173.118 65.109.173.118
```
###### then 
```
curl -x http://ready11:12345@65.109.173.118:40011 https://ifconfig.me
```

5. For stop service 

```
systemctl stop 3proxy_<UserName>.service
```

6. For start

```
systemctl start 3proxy_<UserName>.service
```

7. For restart

```

systemctl restart 3proxy_<UserName>.service

```

