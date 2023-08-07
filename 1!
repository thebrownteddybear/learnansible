ssh-keygen 
#creates pub / pri key pair
#copy the key to esxi, 
#The ssh-copy-id command won’t work with ESXi hosts because the authorized_keys file is in a none standard location.

#Assuming you’ve already created a key pair on your local machine, running the following command on each host should copy your public key to the correct location.

cat ~/.ssh/id_rsa.pub | ssh root@10.1.1.11 'cat >> /etc/ssh/keys-root/authorized_keys'
