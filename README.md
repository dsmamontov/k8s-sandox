# k8s-sandox

# to remember
```
vagrant plugin install vagrant-vbguest
```

# to deploy
```
vagrant up
```

# to reprovision
```
vagrant provision
```

# to deploy k8s
```
ansible-playbook -i inventory/mycluster/inventory.ini  --become --become-user=root cluster.yml
```
