# ludus_cheatsheet
cheatsheat for ludus command

## updating
### Server
```
#ssh to server
wget https://gitlab.com/api/v4/projects/54052321/packages/generic/ludus/v.1.4.5/ludus-server-v.1.4.5
chmod +x ludus-server-v.1.4.5
sudo ./ludus-server-v.1.4.5 --update
```
### Client 
```
wget https://gitlab.com/api/v4/projects/54052321/packages/generic/ludus/v.1.4.5/ludus-client_linux-amd64-v.1.4.5
sudo cp ludus-client_linux-amd64-v.1.4.5 /usr/local/bin/ludus
sudo chmod +x /usr/local/bin/ludus
ludus version
```

## Range 
```
```

## Default Machine Credentials
|Username|Password|Machine|
|--------|--------|-------|
|`kali`|`kali`| Kali (OS)|
|`kali`|`password`|Kali (KasmVNC - port 8444)|
|`localuser`|`password`|Windows (local Administrator)
|`LUDUS\domainuser`|`password`| Windows
|`LUDUS\domainadmin`|`password`| Windows (Domain Admin)
|`debian`|`debian`|Deian based boxes|
|`localuser'|`password`|Other|
