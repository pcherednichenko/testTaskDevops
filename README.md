## Test task for devops 

Here is two microservices for Linux systems: the name of the first **main**, the second **main2**
You need to create a `docker-compose.yml` file, so that when you run the command `docker-compose up` you get the normally running application
I recommend using the `alpine: 3.5` image for docker

Applications defaults run on port `8080`

For the first application, you need to specify two *ENV* variables:
- **USERNAME** to see your name in the welcome screen
- **TWO_URL** address for connection to the second service (service name in the docker-compose file)

After the start, the main application sends the request to the main2 application and, if successful, shows a secret key on the main page (localhost:8080/)

Say this secret phrase to me and push to your repository the finished version of the docker-compose file with the main files

Good luck and *may the Force be with you*!