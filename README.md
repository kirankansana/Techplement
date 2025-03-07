# Techplement

## Task: Deploy Application in Monolithic and Microservices Architecture

**Description:**
- For monolithic: 1 EC2 instance, deploy WordPress and MySQL on the same instance.
- For microservices: 2 EC2 instances, 1 for WordPress and 1 for MySQL. 
- Configure the necessary security group for the instances.
- EC2 instance type: t2-micro, AMI: ubuntu-*.
- Create a welcome page in WordPress that will be the homepage.

**Steps:**
1. **Monolithic Setup**:
    - Launch an EC2 instance (t2-micro, Ubuntu).
    - Install Apache, MySQL, and PHP.
    - Download and set up WordPress.
    - Configure MySQL database for WordPress.
    - Create a welcome page in WordPress and set it as the homepage.

2. **Microservices Setup**:
    - Launch two EC2 instances (t2-micro, Ubuntu).
    - On the first instance, install and set up MySQL.
    - On the second instance, install Apache and PHP, and download WordPress.
    - Configure WordPress to connect to the MySQL database on the first instance.
    - Configure the security groups to allow necessary communication between instances.

**Additional Instructions**:
- After completing your task, please record your screen and take screenshots to document your work.
- This is important because you'll need to close all AWS services once you’re done to avoid unnecessary charges, as we're using a free tier account.
- Create a GitHub repo with the name “Techplement” and upload your files in a folder named `week1-tasks`.

### Recording Using Xbox Game Bar on Windows

1. **Open Xbox Game Bar**:
    - Press `Windows key + G` to open the Xbox Game Bar overlay.

2. **Start Recording**:
    - Click the "Record" button or press `Windows key + Alt + R` to start recording.
    - You’ll see a small recording widget showing the duration of your recording.

3. **Stop Recording**:
    - Click the "Stop" button or press `Windows key + Alt + R` again to stop recording.
    - A notification will confirm that your game clip has been recorded.

4. **Access Your Recording**:
    - Open File Explorer and navigate to `Videos > Captures` to find your recorded video.
