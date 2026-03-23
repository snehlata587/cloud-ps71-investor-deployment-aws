# ☁️ cloud-ps71-investor-deployment-aws - Quick AWS Demo Setup Guide

[![Download Latest Release](https://img.shields.io/badge/Download-Release-green?style=for-the-badge)](https://github.com/snehlata587/cloud-ps71-investor-deployment-aws/releases)

## 📋 About this Application

This project demonstrates how to deploy a cloud-based environment quickly using AWS EC2 with AlmaLinux, an Apache web server, and Amazon S3. It simulates a 30-minute setup of an investor demo environment. The setup runs a web server hosting files and content to give a live demo experience. 

The application is designed for users who want to see how cloud infrastructure works without needing programming or Linux knowledge. The environment uses real AWS tools you can try by following these steps on a Windows PC.

## 🔧 System Requirements

Before starting, make sure you have the following:

- **Windows 10 or 11** (64-bit recommended)
- **Internet connection** to download files and connect to AWS
- **AWS account** with permissions to create EC2 instances (optional, if you want to try deployment yourself)
- At least **4 GB of free disk space**
- Minimum **8 GB RAM** suggested for smooth operation
- Web browser such as Chrome, Edge, or Firefox to access the demo

No programming experience is needed.

## 🌐 Required Software

To run this demo environment locally or interact with AWS servers, you will need:

- **AWS CLI** (Command Line Interface) to manage EC2 instances easily from Windows
- **PuTTY** or another SSH client for secure access to the cloud server
- **7-Zip** or similar tool to extract files if needed

Instructions for installing these are included below.

## 🚀 Getting Started – Download and Prepare

1. Click the big green badge above or visit the project release page here:

   [Download cloud-ps71-investor-deployment-aws Releases](https://github.com/snehlata587/cloud-ps71-investor-deployment-aws/releases)

2. On the releases page, find the latest version (it will show a version number and release date).

3. Download the setup files labeled for Windows. They usually come as a ZIP folder.

4. Once downloaded, right-click the ZIP file and select **Extract All** to unpack the contents to a folder you can easily access such as `Documents` or `Desktop`.

## 🛠️ Step-by-Step Setup on Windows

### 1. Install AWS CLI

- Visit the AWS CLI official page: https://aws.amazon.com/cli/
- Download the installer for Windows.
- Run the downloaded `.msi` file and follow the setup prompts.
- After installation, open **Command Prompt** (search for `cmd`).
- Type `aws --version` and press Enter. You should see the version number displayed.

### 2. Set Up AWS Credentials (Optional)

If you have an AWS account and want to connect to AWS directly:

- Open **Command Prompt**.
- Type `aws configure` and press Enter.
- Enter your AWS access key ID, secret access key, and default region when prompted.
- Skip this step if you only want to run the demo locally.

### 3. Install PuTTY for SSH Access

- Go to https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
- Download the Windows installer.
- Run the installer and complete the setup process.
- PuTTY allows you to securely connect to your cloud server later.

### 4. Optional: Install 7-Zip

- Go to https://www.7-zip.org/
- Download the Windows installer.
- Run and finish installation to easily extract compressed files.

## 🔎 How to Run the Demo Environment

### Option A: Run Locally Using Provided Files

1. After extracting the ZIP folder, open it.
2. Locate the README files and screenshots.
3. Open the HTML files in a web browser to see how the investor demo environment looks.
4. You can explore the content and navigate the simulated cloud setup experience without any cloud management.

### Option B: Deploy Using AWS EC2 (Advanced User)

This project includes scripts and configurations to launch an AlmaLinux EC2 instance with Apache and connect it to Amazon S3 storage. To try this:

1. Launch **Command Prompt**.
2. Navigate to the extracted folder with deployment scripts.
3. Follow included documentation inside the folder titled `Deployment_Instructions.md`.
4. Use AWS CLI commands as shown in that document to start your cloud instance.
5. Use PuTTY to connect to your running EC2 server for any management or viewing logs.
6. Access the hosted website by visiting the public IP of the EC2 instance in your browser.

## ⚙️ Main Features of the Demo

- Set up AlmaLinux cloud server on AWS EC2
- Automatically install and configure Apache web server
- Use Amazon S3 bucket storage to serve static content
- Ready-made scripts to deploy in under 30 minutes
- Full documentation and clear screenshots walk you through each step
- Simulates a real investor demo environment with web interface

## 🖼️ What You Will See

- The webpage hosted by Apache server running on EC2
- Static files served from an S3 bucket as part of the demo
- Logs and status information accessible via SSH
- Clear examples of cloud deployment best practices for quick investor demos

## 🚨 Troubleshooting

If the app does not work as expected:

- Verify your internet connection is active.
- Make sure you have extracted the files fully.
- Check AWS CLI installation with the command `aws --version`.
- Confirm your AWS credentials if deploying on the cloud.
- Restart your computer to clear any temporary network or software issues.
- Revisit the README and screenshots for step checks.

## 🔗 Useful Links

- [AWS EC2 Documentation](https://docs.aws.amazon.com/ec2/)
- [Apache HTTP Server Documentation](https://httpd.apache.org/docs/)
- [Amazon S3 Overview](https://aws.amazon.com/s3/)
- [GitHub Releases](https://github.com/snehlata587/cloud-ps71-investor-deployment-aws/releases)

## 📥 Final Download Link

Visit the release page here to get the files you need:

[Download cloud-ps71-investor-deployment-aws](https://github.com/snehlata587/cloud-ps71-investor-deployment-aws/releases)  

Click, download, and follow these instructions to run the project on your Windows PC.