Successfully configured and deployed Jenkins instances using Docker on Ubuntu.

## Steps Completed:
1. **Created Docker Volume:** Created a persistent storage volume named `jenkins-data` to ensure data safety.
2. **Jenkins with Volume (Port 8081):** Deployed a persistent Jenkins container, completed setup wizard, and configured the Admin User.
3. **Jenkins without Volume (Port 8082):** Deployed a temporary/independent Jenkins container as per final assignment requirements.
4. **Verification:** Confirmed both instances are running simultaneously using the `sudo docker ps` command.
