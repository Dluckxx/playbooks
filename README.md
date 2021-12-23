# Dluck Server Deploy Solution

## Get Stareted

1. Install ansible
2. Pull code from repository
3. Run ansible env command
```bash
$ ansible-playbook --tags=env \
--inventory-file=playbooks/hosts/hosts.ini \
playbooks/all.yml
```
4. Run ansible deploy command
```bash
$ ansible-playbook --tags=deploy \
--inventory-file=playbooks/hosts/hosts.ini \
playbooks/all.yml
```

## Deploy Application List

- kubenetes
    - docker
    - kubectl
    - minikube
    - kuboard
- jellyfin