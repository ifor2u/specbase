# specbase
groupadd -g 2000 spec
useradd -g spec -u 2000 specuser
visudo
ssh-keygen -t rsa
ssh-copy-id -i /home/specuser/.ssh/id_rsa.pub xxx
