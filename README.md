# flask-blog-app


## Features 
- multiple user ( admin, user ) 
- bulk delete for blogs, images, user
- bulk promote users to admin 
- admin cant see email users 
- wysiwyg editor with ckeditor 
- basic rest api 
- reset password 
- cursor pagination 
- validate email and password ( avoid duplicate ) 

## Prerequisites

Before you begin, make sure you have the following:

- A Linux system (e.g., Ubuntu)
- Python 3 and Git installed
- Docker installed (if you want to use Docker)
- MySQL (for production setup)
- SMTP details for password reset functionality

### Docker Installation

Make sure Docker is installed on your system. You can follow the official [Docker installation guide](https://docs.docker.com/engine/install/ubuntu/) to install Docker on Ubuntu.

## Installations 
```sh
apt-get install python3 git 
git clone https://github.com/gibran-abdillah/flask-blog-app.git 
cd flask-blog-app


### Build the Docker Image

To build the Docker image, run the following command:

```bash
docker build -t flask-blog-app .

# Run the Docker Container
docker run -p 5000:5000 flask-blog-app

## to do 
- improv on the frontend
- create migration database
- create a search feature on the blog
- track bugs and fix them
- whats next?
