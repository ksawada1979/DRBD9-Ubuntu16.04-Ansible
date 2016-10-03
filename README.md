# DRBD9-Ubuntu16.04-Ansible
実行環境はUbuntu16.04で確認済み<br>
<br>
鍵交換コマンド<br>
ssh-copy-id -i ~/.ssh/id_rsa.pub root@<サーバIPアドレス><br>
<br>
ansible実行コマンド<br>
ansible-playbook -i ansible_hosts drbd9.yml<br>
<br>
以下のIPアドレスは環境に応じて変更してください。<br>
ansible_hosts<br>

詳しくは以下をご参照ください。<br>
