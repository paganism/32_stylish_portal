# Shared CSS Library

# Install nginx
```
$ sudo (apt|dnf|yum) install nginx
```

# How to Test

Create symbolic link to your nginx.conf
```
ln -s /etc/nginx/nginx.conf path_to_your_32_stylish_portal/nginx.conf
```
Then reload or restart nginx:
```
sudo nginx -s reload
```
or 
```
sudo systemctl restart nginx
```

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
