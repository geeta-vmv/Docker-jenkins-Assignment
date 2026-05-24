Successfully configured and deployed Jenkins instances using Docker on Ubuntu.

## Steps Completed:
1. **Created Docker Volume:** Created a persistent storage volume named `jenkins-data` to ensure data safety.
2. **Jenkins with Volume (Port 8081):** Deployed a persistent Jenkins container, completed setup wizard, and configured the Admin User.
3. **Jenkins without Volume (Port 8082):** Deployed a temporary/independent Jenkins container as per final assignment requirements.
4. **Verification:** Confirmed both instances are running simultaneously using the `sudo docker ps` command.

---

## Jenkins Assignment 2 - Practical Verification

This section includes the practical verification and proof for Jenkins Assignment 2.

### Key Milestones Completed:
1. **Jenkins Freestyle Job:** Created, configured, and successfully executed.
2. **Jenkins Pipeline Job:** Written a Jenkinsfile pipeline script to automate stages.
3. **Git Integration:** Successfully configured Source Code Management to clone code automatically from GitHub into the Jenkins Workspace.
4. **Build Automation:** Simulating Maven Clean Install and Docker Image Build processes within the build steps.
5. **Log Analysis:** Verified and checked all execution steps via Console Output logs.

*All assignment goals have been practically implemented and verified inside the Dockerized Jenkins container.*
