# ansible-ripple

ansible-playbook -i ./hosts ./tracking-node/ripple_tiny.yml -u centos --private-key=sshkey

# document

https://ripple.com/build/rippled-setup/#installing-rippled

# spec

## tiny

* CPU 2core
* DISK 50GB SSD (500IOPS more)
* RAM 4GB
* t2.large

## medium

* CPU 4core
* RAM 16GB
* DISK 100GB SSD
* m4.xlarge
