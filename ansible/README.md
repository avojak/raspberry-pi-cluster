https://github.com/k3s-io/k3s-ansible

```bash
$ ansible-playbook play.yml -i inventory/pi-cluster/hosts.ini --ask-pass
```

To get access to your Kubernetes cluster just:

```bash
$ scp pi@master_ip:~/.kube/config ~/.kube/config
```