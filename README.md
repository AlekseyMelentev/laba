# Laba

Requirements for remote host: docker, python3 and python3-pip

run commands on remote hosts:

```bash
pip install docker
```

change variables in global_vars.yaml file

and run:

```bash
git clone https://github.com/AlekseyMelentev/laba
cd laba
```

```bash
python3 -m venv venv &&
  source venv/bin/activate &&
  pip install ansible
```

```bash
ansible-playbook -i invertory.txt playbook-remote.yaml -K
ansible-playbook -i invertory.txt playbook-local.yaml -K
```