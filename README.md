# PICOCITF-Where-are-the-Robots


![image](https://github.com/user-attachments/assets/41a0c7b0-3a55-419f-a191-497c269f017b)

## Objective
The objective of this challenge is to explore and understand how web crawlers interact with a website by examining the robots.txt file. The goal is to locate hidden or disallowed paths within the file that may reveal sensitive or restricted content. This exercise enhances awareness of how misconfigured or overly permissive robots.txt entries can expose critical information to attackers.

###🧠 Skills Learned

- Understanding and analyzing the robots.txt file structure

- Using browser developer tools to inspect server responses

- Manual directory fuzzing and content discovery

- Recognizing how web misconfigurations can leak sensitive data

- Basic knowledge of how web crawlers and indexing work



### 🛠️ Tools Used
<div> <img src="https://img.shields.io/badge/-Browser%20DevTools-4285F4?&style=for-the-badge&logo=googlechrome&logoColor=white" /> <img src="https://img.shields.io/badge/-picoCTF-ff4757?&style=for-the-badge&logo=ctf&logoColor=white" /> </div>

##🧭 Step-by-Step Challenge Summary
Initial Access
- Opened the challenge-provided URL in a browser to examine the web application’s homepage.

![image](https://github.com/user-attachments/assets/6768eb06-bbb1-4cfc-8859-eb75d5fac048)

- Exploring robots.txt
Manually navigated to /robots.txt in the browser  to check for disallowed paths.

![image](https://github.com/user-attachments/assets/2aad29ca-da74-49bc-b7de-6edc6db4b5c3)


- Identifying Hidden Directory
Located a disallowed or hidden path listed in the robots.txt file that hinted at restricted or sensitive content.

![image](https://github.com/user-attachments/assets/691d9914-e0f7-4b93-93ff-9f7aee3fc66b)

![image](https://github.com/user-attachments/assets/f91f768c-d332-4fcf-91c4-36026f6882b5)


- Accessing the Hidden Path
Navigated to the hidden path via browser to explore its content and find clues or the flag.

![image](https://github.com/user-attachments/assets/a2f953a7-96eb-457f-8c45-be37bb9eca64)


- Flag Retrieval
Discovered and copied the flag displayed within the hidden directory or page.

![image](https://github.com/user-attachments/assets/b06b54e6-747d-47d0-b1fa-bcc3369d2497)
