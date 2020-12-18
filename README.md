Modificacion de la plantilla lanzada desde el script: https://github.com/oscarmash/create_vm_ubuntu1804_hyperv

Como se lanza desde el servidor **ansible**
```
ansible-playbook main.yml
git add . && git commit -am 'Modificar VM: template.... 1' && git push
```
Se ha de anadir al fichero: vim /etc/ansible/hosts
```
[template]
172.26.0.21
```

