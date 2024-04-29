# Analyzing HTTP Basic Authentication

This project aims to analyze HTTP authentication traffic using Wireshark, with a focus on identifying potential security vulnerabilities. Wireshark has the capability to intercept and reveal credentials entered on unsecure websites, providing valuable insights into potential risks.

## Website
The website utilized for this project employs the GET method for authentication:
[http://httpbin.org/basic-auth/username/password](http://httpbin.org/basic-auth/username/password)

## Credentials
- **Correct Credentials:**
  - Username: username
  - Password: 1234

## Steps

1. **Open Wireshark**: Launch Wireshark and configure it to capture traffic on Port 80 (HTTP).
![image](https://github.com/ookelvyn/Wireshark-for-Network-Security-Analysis/assets/30266503/e79fbdc8-5f09-4f58-a916-ff0891dc3861)
2. **Capture Traffic**: Double-click Wi-Fi interface to begin capturing HTTP traffic.
3. **Access the Website**: Enter the provided website URL in your browser and observe the captured traffic in Wireshark.
![image](https://github.com/ookelvyn/Wireshark-for-Network-Security-Analysis/assets/30266503/29b5413f-c393-4302-b73f-88d35cb2c2c2)

![image](https://github.com/ookelvyn/Wireshark-for-Network-Security-Analysis/assets/30266503/5098528d-e041-4718-b623-ef3ffa6d2e7d)

4. **Attempt Incorrect Credentials**: Try entering incorrect credentials (e.g., Username: username; Password: admin123) and observe the traffic.
![image](https://github.com/ookelvyn/Wireshark-for-Network-Security-Analysis/assets/30266503/c862523f-f479-4310-b513-2230d1f6be6b)

5. **Enter Correct Credentials**: Enter the correct credentials (provided above) and monitor the traffic in Wireshark.
![image](https://github.com/ookelvyn/Wireshark-for-Network-Security-Analysis/assets/30266503/8db63406-a562-40c0-aea1-0acc2228ed56)

6. **View Incorrect Credentials**: Analyze the captured packets to identify the transmission of incorrect credentials.
![image](https://github.com/ookelvyn/Wireshark-for-Network-Security-Analysis/assets/30266503/dcdf6b06-7115-4df3-ae33-ec173d139801)

7. **View Correct Credentials**: Identify and analyze the packets containing the correct credentials.
![image](https://github.com/ookelvyn/Wireshark-for-Network-Security-Analysis/assets/30266503/dbef453a-d88b-4caa-93c7-61cd0fc6e305)

