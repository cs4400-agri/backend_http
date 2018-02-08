# backend_http
## EC2 Info
Use SSH (another socket protocol like http) to directly access our EC2. Our EC2 has **public IP : 34.204.7.160**
``` 
ssh -i path_to_key ubuntu@34.204.7.160
``` 
for example 
```
ssh -i Desktop/cs4400/cs4400_ec2_key.pem ubuntu@34.204.7.160
```
To exit from the EC2 terminal and go back to your own type "exit".

For **nginx** look to this guide: http://nginx.org/en/docs/beginners_guide.html

to start nginx 
``` nginx -s signal ```
