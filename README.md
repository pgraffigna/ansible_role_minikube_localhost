# ansible_role_minikube_localhost

Playbook role para crear un cluster kubernetes con minikube localmente.

Testeado con Virtualbox y Ubuntu 18.04

roles:
- docker	
- kubectl
- minikube 

script:
- ansible_install.sh