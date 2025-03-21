# 4640-w11-lab-start-w25

We will need to install boto3 so that the aws_ec2 plugin for dynamic inventories works:
sudo apt install python3-boto3

We can then run the playbook using:
ansible-playbook -i inventory playbook.yml

Here is our screenshot showing the frontend running:

![image](https://github.com/user-attachments/assets/4e2424ba-de32-4c4f-ade4-e79d0a1274cd)

Another screenshot showing our aws frontend instance:

![image](https://github.com/user-attachments/assets/1e954118-b3a2-41e3-abbc-8bd1ca5b0c22)
