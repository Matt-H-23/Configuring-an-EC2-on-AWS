# EC2 Setup 💻
### Step 1: Log into your AWS account ➡️
- If you haven't already, go ahead and create an account for AWS
![AWS LogIn](https://github.com/user-attachments/assets/3d75dbc8-ffb4-4431-9d13-d7256e7f11f1)

### Step 2: After configuring your AWS account, search up **EC2** in the search bar, or select it if you have used it before ➡️
![EC2](https://github.com/user-attachments/assets/a9645cbe-7f8a-40a4-ae7a-19579d7a74d8)

### Step 3: Launching the Instance
- After you select '**Launch Instance**'
![Launch Instance](https://github.com/user-attachments/assets/24ac8f77-0269-47b6-a540-ac0fcfc2707a)
- You are going to name your instance (something sensible), and select **Windows** as your **AMI** 
![Provision your Instance](https://github.com/user-attachments/assets/10f5b319-dc15-4fce-8ff4-66f6bb6aaa83)
- For the '**Instance Type** the **t2.micro** is enough to get the lab done
- I already had a key pair created, so if you don't have one, go ahead and select '**create new key pair**' (don't forget to name it) and it will automatically download to your computer
- And although it's not impossible, for security purposes, under the **Networking** tab, change it from '**Anywhere**' to '**My IP**' to prevent unwanted guests from accessing your Instance
![Create Key Pair](https://github.com/user-attachments/assets/50fd5347-1206-480f-a582-ae850cfd0e24)
- **Congrats!** You've provisioned your first **EC2** instance on AWS to run and configure a Windows Server, now go ahead and hit launch
![](https://github.com/user-attachments/assets/9997eb07-9bfd-442b-83ec-ceeb3d03b8ec)
- After hitting launch, you'll be sent to another page, and at the top you are going to hit the underlined portion of the sentence in the **green** bubble
![Next Steps](https://github.com/user-attachments/assets/87587d09-06d1-4721-a6a4-80221f435c19)
- After getting sent to the next page, select the **check box** for your newly provisioned instance, and click on **connect** towards the top of the page
![Connect to the instance](https://github.com/user-attachments/assets/d424c555-dde8-4ae6-86f3-8ac278e004d5)
- Since we provisioned a **Windows** machine, we are going to select '**RDP Client**' and click '**Download Remote desktop file**'
- **NOTE**: Before you are able to get the password for the RDP, you have to wait a few minutes before you are able to retrieve the password
![RDP and get password](https://github.com/user-attachments/assets/b4106c5e-35d2-4eed-a337-e0a1a2cf9d81)
![Be Patient](https://github.com/user-attachments/assets/7013c1aa-dc8e-405d-9bfd-df20f366566c)
- After AWS allows you to hit **get password**, you are going to **upload your Private Key File**, select **Decrypt Password**, and then copy the password to clipboard, we're going to need it in a second
![Password](https://github.com/user-attachments/assets/90c71971-27fd-4e17-b938-008f94786355)
- Remeber when we downloaded the **RDP** file? Go ahead and open it, and you should be prompted to enter the password for the RDP Client, and welcome to your first AD Server!
![Establishing RDP](https://github.com/user-attachments/assets/af04bde7-d635-470f-908e-9ea9724d2e4d)

