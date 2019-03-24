```
virtualenv -p $(which python3) minecraft
source minecraft/bin/activate
pip install -r requirements.txt
ansible-galaxy install -r roles.yml
ansible-playbook -i inventory site.yml
```
