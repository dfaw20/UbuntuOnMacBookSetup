# インストール

```bash
sudo apt-get update
sudo apt-get install ansible
```

# 実行

パスワード入力あり

```
cd SelfProvisioning/
ansible-playbook -i hosts setup.yml --ask-become-pass
```