- š Hi, Iām @furkanunay15
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
furkanunay15/furkanunay15 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
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
