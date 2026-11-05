In this project, I developed a sample web application using Node.js and Express.js and automated its build and image publishing process using GitHub Actions.

I created a CI/CD pipeline that automatically runs application tests whenever code is pushed to the main branch. If the tests pass, GitHub Actions builds a Docker image and pushes it to Docker Hub.

I used GitHub Secrets to securely store Docker Hub credentials and Docker to package the application into a container
