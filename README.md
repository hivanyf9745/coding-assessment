# coding-assessment

## Steps to run the codes

1. You can build the docker image by running: `docker build -t next-login-app .`
2. You can then run the Docker container by running`docker run -p 3000:3000 next-login-app`

After running these commands, you should be able to access the login form at http://localhost:3000/login.

**NOTE: This is a basic example, and you might want to handle form submission and user authentication differently based on your requirements. The form is set up to simply log the form values when the form is submitted.**
