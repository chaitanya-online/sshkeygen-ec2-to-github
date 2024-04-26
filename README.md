# sshkeygen-ec2-to-github

1) ssh-keygen -t ed25519 -C "your email address"

![image](https://github.com/chaitanya-online/sshkeygen-ec2-to-github/assets/60810937/12f6557f-30b9-4bb9-aae7-2df348540c85)

2)   eval "$(ssh-agent -s)"

![image](https://github.com/chaitanya-online/sshkeygen-ec2-to-github/assets/60810937/efb2dc6b-4f6b-4fa2-9cf1-128ab9e2a094)

3) ssh-add ~/.ssh/id_ed25519

4) cat ~/.ssh/id_ed25519.pub

   It will show the key copy  and add it to the github
