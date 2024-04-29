# Analyzing HTTP Basic Authentication

In this project, we will analyze traffic on HTTP authentication using Wireshark. Wireshark has the capability of revealing credentials entered on an insecure website. The website to be used in this project uses the GET method for authentication.

Website: [http://httpbin.org/basic-auth/username/password](http://httpbin.org/basic-auth/username/password)

### Correct credentials:
- Username: username
- Password: password

Step 1: Open Wireshark and enter Port 80 to capture HTTP traffic. Double-click Wi-Fi
![image](https://github.com/ookelvyn/Wireshark-for-Network-Security-Analysis/assets/30266503/e79fbdc8-5f09-4f58-a916-ff0891dc3861)

Step 2: Enter the website on your browser and observe the traffic
![image](https://github.com/ookelvyn/Wireshark-for-Network-Security-Analysis/assets/30266503/29b5413f-c393-4302-b73f-88d35cb2c2c2)

Step 3: Attempt to enter incorrect credentials.For example Username: username; Password: admin123.
