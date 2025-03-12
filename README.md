# Prerequisites: you can run it locally or in a Virtual Machine in Huawei Cloud
- vCPU: at least 8vCPU
- RAM: 16GB for 7B parameters
- Ubuntu: 22.04
- Disk: 100GB General Purpose SSD
- Elastic IP (optional to access by public network): 100Mbit/s 
# Deploy DeepSeek with UI instantly

## Step 1: Update and install
```
sudo apt update
sudo apt install docker.io docker-compose -y
```

## Step 2: Clone Repo
```
git clone https://github.com/jeremyaldama/deepseek-docker-compose.git
```

## Step 3: Enter to the directory and run containers
```
cd deepseek-docker-compose
docker-compose up -d
```
### Now you can enter to http://public-ip:3000 port and create an account to start using DeepSeek!
![image](https://github.com/user-attachments/assets/00b265dc-0a0d-467b-b54b-627058ef8e1a)

### Fill the form to create an admin account
![image](https://github.com/user-attachments/assets/3f9655f1-0cf4-489c-88be-31fd5eeedbff)

