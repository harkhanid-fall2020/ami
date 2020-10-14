# ami

## Steps to run the project

1. fork the repository in your account and do the git clone.
2. Install packer in your system.
3. open the terminal and run
```yml
packer validate ami.json
```
4. change parameter according to your profile and run
```yml
 packer build \
    -var 'aws_access_key=YOUR KEY' \
    -var 'aws_secret_key=YOUR SECRET KEY' \
    -var 'subnet_id=SUBNET ID'\
    -var 'ami_users=USERS'\
    ami.json
```

