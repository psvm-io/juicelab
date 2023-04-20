JuiceLab
======
**JuiceLab** is a docker compose script that deploys a pentesting environment for the OWASP Juice Shop web application.

## Install
```
$ git clone https://github.com/psvm-io/juicelab.git
$ cd juicelab
$ docker compose up -d
```

## Instructions
Enter Kali's CLI with:
```
$ docker attach juicelab-kali
```
Install the tools you need using APT, or for the default headless tools use:
```
apt -y install kali-linux-headless
``` 

By default, the target web application can be found at:
- 10.92.0.2:3000  (from Kali)
- http://localhost:3000  (from host)

Custom IP addresses and hostname can be specified in the .env file

## Content
* OWASP Juice Shop
* Kali Linux (Rolling)

## Contact
#### Federico Mattalia
* Homepage: https://github.com/psvm-io
* e-mail: git@psvm.io
