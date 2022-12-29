- 👋 Hi, I’m @furkanunay15
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
furkanunay15/furkanunay15 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
version: '3.7'

services:
    phoneinfoga:
      container_name: phoneinfoga
      restart: on-failure
      image: sundowndev/phoneinfoga:latest
      command:
        - "serve"
      ports:
        - "80:5000"
