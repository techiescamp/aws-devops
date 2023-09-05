## 🖥️ Create an EC2 Instance

### 📝 Task 01

- 🐧 Create an Ubuntu EC2 instance. Make sure to set up a custom security group that allows traffic on ports 22 and 80.
- 🌐 Connect to the instance and install Nginx.
- 🌍 Access Nginx using the browser by entering the Public IP of the server.

### 📝 Task 02

- 🛠️ Create a service using an EC2 user data script that installs Nginx.
- ⚙️ Set up cloud config to set the hostname.

#### Example
```
#cloud-config
hostname: nginx-server
```

