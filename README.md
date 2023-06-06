# Signmykey RPM repository

* Add Signmykey repository
```
echo "[signmykey]
name=Signmykey repo
baseurl=https://rpm.signmykey.io/
enabled=1
gpgcheck=0
repo_gpgcheck=1
gpgkey=https://gpg.signmykey.io/signmykey.pub" > /etc/yum.repos.d/signmykey.repo
```

* Install Signmykey package
```
sudo yum install signmykey
```