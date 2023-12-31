# Reverse Proxy Configuration using NGINX

Document Link: [NGINX Reverse Proxy Guide](https://www.remnote.com/a/NGINX/6551b5ddb78d27192981c665)

### NGINX Commands

- `nginx -s stop`: Fast shutdown
- `nginx -s quit`: Graceful shutdown
- `nginx -s reload`: Change configuration, start new worker processes with new configuration, gracefully shut down old worker processes
- `nginx -s reopen`: Reopen log files

### Local Host Mapping

- `127.0.0.1:81` ➡️ `localhost:81`
- `127.0.0.1:82` ➡️ `localhost:82`
- or simply `localhost:81` and `localhost:82`
- Or, if you're on a network, use `static-ip:81` and `static-ip:82`

### Steps to Manage NGINX on Windows

1. **Start Nginx**: Open Command Prompt as Administrator and navigate to the directory where Nginx is installed. Then, start Nginx by running the following command:


2. **Check Nginx Configuration**: Before reloading the configuration, check if the configuration is correct by using the following command:


3. **Reload Nginx Configuration**: If the configuration is correct, reload the Nginx service to apply the changes:


4. **Stop Nginx Server**: To stop the Nginx server on Windows, use the following command:


### Running Servers on Different Ports

- Server1 listening at `http://localhost:3000`
- Server2 listening at `http://localhost:3001`

#### Configuration Codes

![NGINX Configuration](https://remnote-user-data.s3.amazonaws.com/vClROqYxAt_B4dlNcCkbSS75qcX-nJ-1YGjZgBfSJ8J-TDqAwcF1H6QDCubtDrVT6DBJM1Kjob8BeK3nXR7_HxpMl1I-dSVfWXJtSkWtewFg6BrMcERWfu0BIaJoVx96.png)

![NGINX Get Started](https://remnote-user-data.s3.amazonaws.com/c_cVwP8YEHcPwVPb2gayG0CdfMQPTJghP4GX9l45OLcfHOMcg6-lDs9dvO17ZJV3aUp0UERmA87NeMRdTLV8vHkptGfk0NQEQa7IKzkcI9tz4dYuWiJGRbQSnWd-jioS.png)
