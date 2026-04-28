   #                                                             ## Hello This is Cricket Html App 
  #                                                              ### testing jenkins pipeline ###
**✅ STEP 1**
Install AWS-CLI SDK from offical aws documentation
```bash
apt install unzip
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
```
**✅ STEP 2**
Give Permissions, so that jenkins will have proper permissions of docker
```bash
sudo usermod -aG docker jenkins
```
**✅ STEP 3**
Verify group 
```bash
groups jenkins
```
**✅ STEP 4**
Restart Jenkins
```bash
sudo systemctl restart jenkins
```
