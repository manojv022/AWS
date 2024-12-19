<h1>STATIC WEB HOSTING</h1>
<h3>Step 1: Create instance and connect it</h3>


<h3>Step 2: Go to root user</h3>

```
sudo -i
```

<h3>Step 3: Download static website and unzip it</h3>

```
curl -O https://www.free-css.com/assets/files/free-css-templates/download/page296/oxer.zip
unzip filename
```

<h3>Step 4: Install Nginx</h3>

```
yum install nginx -y
systemctl status nginx
systemctl start nginx
systemctl restart nginx
```

<h3>Step 5: Move unzip file to nginx path</h3>

```
mv /usr/share/nginx/html
```

<h3>Step 6: Click on IP of instance and hit it on your browser </h3>



**Must have (SSH,HTTP) port in security group**
