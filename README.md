#Document link : https://www.remnote.com/a/NGINX/6551b5ddb78d27192981c665

Reverse Proxy

nginx -s stop	#fast shutdown
nginx -s quit	#graceful shutdown
nginx -s reload	#changing configuration, starting new worker processes with a new configuration, graceful shutdown of old worker    processes
nginx -s reopen	#re-opening log files 

# 127.0.0.1:81  === localhost:81
# 127.0.0.1:82  === localhost:82
# or localhost:81 localhost:82  
# or if you're on a network static-ip:81 static-ip:82  

1) Start Nginx: Open Command Prompt as Administrator and navigate to the directory where Nginx is installed. Then, start Nginx by running the start command: 
cd C:\path\to\nginx 
start nginx 

2) Check Nginx Configuration: Before reloading the configuration, it's a good practice to check if the configuration is correct. You can do this using the command below:
nginx -t 

3) Reload Nginx Configuration: If the configuration is correct, you can reload the Nginx service to apply the changes. This can be done using the command below:
nginx -s reload 

4) To stop the Nginx server on Windows, you can use the -s stop command. Open Command Prompt as Administrator, navigate to the directory where Nginx is installed, and run the following command:  
cd C:\path\to\nginx 
nginx -s stop 

Run two servers on two ports

Server1 listening at http://localhost:3000  
Server2 listening at http://localhost:3001  

configuration code 
https://remnote-user-data.s3.amazonaws.com/vClROqYxAt_B4dlNcCkbSS75qcX-nJ-1YGjZgBfSJ8J-TDqAwcF1H6QDCubtDrVT6DBJM1Kjob8BeK3nXR7_HxpMl1I-dSVfWXJtSkWtewFg6BrMcERWfu0BIaJoVx96.png 

https://remnote-user-data.s3.amazonaws.com/c_cVwP8YEHcPwVPb2gayG0CdfMQPTJghP4GX9l45OLcfHOMcg6-lDs9dvO17ZJV3aUp0UERmA87NeMRdTLV8vHkptGfk0NQEQa7IKzkcI9tz4dYuWiJGRbQSnWd-jioS.png #   N G I N X - g e t s t a r t 
 
 
