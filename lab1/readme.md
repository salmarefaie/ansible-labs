### Task: 
- install NGINX or apache on Machine and Configure it to listen on port 8090 then change the  default page to custom index.html on 2 machines and 
Deploy your Django app to one of those machines
  - make 2 instances ec2 on aws
  - put public ip for 2 instances for ansible host in inventory.txt
  - download project from this repo: https://github.com/salmarefaie/Booster_CI_CD_Project
  - edit settings.py and put insatance ip in allowed hosts
  - run ansible code
```bash
    ansible-playbook playbook.yaml -i inventory.txt
```
  - output
  
  ![Screenshot from 2023-02-12 19-37-30](https://user-images.githubusercontent.com/76884936/218329811-c7535421-07c9-4be6-9252-cd35e4f44be9.png)
  
  ![Screenshot from 2023-02-12 19-38-26](https://user-images.githubusercontent.com/76884936/218329817-5a850244-700d-42da-bae9-e3de549c28d2.png)
  
  ![Screenshot from 2023-02-12 19-39-24](https://user-images.githubusercontent.com/76884936/218329833-299f0436-1aea-45a5-b56b-7653983a0d3c.png)
