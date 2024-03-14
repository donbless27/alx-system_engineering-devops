# Project 0x1A. Application server


![Image-Source](https://i0.wp.com/www.exabytes.my/blog/wp-content/uploads/2022/09/application-server.jpg?w=468&ssl=1)

**A web server‘s fundamental job is to accept and fulfill requests from clients for static content from a website (HTML pages, files, images, video, and so on). The client is almost always a browser or mobile application and the request takes the form of a Hypertext Transfer Protocol (HTTP) message, as does the web server’s response.

- An application server’s fundamental job is to provide its clients with access to what is commonly called business logic, which generates dynamic content; that is, it’s code that transforms data to provide the specialized functionality offered by a business, service, or application. An application server’s clients are often applications themselves, and can include web servers and other application servers. Communication between the application server and its clients might take the form of HTTP messages, but that is not required as it is for communication between web servers and their clients. Many other protocols are popular, including the variants of CGI.**

# Resources
*Read or watch:*

- [Application server vs web server](https://www.nginx.com/resources/glossary/application-server-vs-web-server/)
- [How to Serve a Flask Application with Gunicorn and Nginx on Ubuntu 16.04](https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-16-04)
- [Running Gunicorn](https://docs.gunicorn.org/en/latest/run.html)
- [Be careful with the way Flask manages slash in route - strict_slashes](https://werkzeug.palletsprojects.com/en/3.0.x/)
- [Upstart documentation](https://doc.ubuntu-fr.org/upstart)

#Requirements
# General
- A `README.md` file, at the root of the folder of the project, is mandatory
- Everything Python-related must be done using `python3`
- All config files must have comments
- Bash Scripts
- All your files will be interpreted on Ubuntu 16.04 LTS
- All your files should end with a new line
- All your Bash script files must be executable
- Your Bash script must pass `Shellcheck` (version `0.3.7-5~ubuntu16.04.1` via `apt-get`) without any error
- The first line of all your Bash scripts should be exactly `#!/usr/bin/env bash`
- The second line of all your Bash scripts should be a comment explaining what is the script doing

