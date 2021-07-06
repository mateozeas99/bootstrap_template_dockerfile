# bootstrap_template_dockerfile
Dockerfile with Bootstrap Template for Lesson 1002

# Lesson 01
Create a Dockerfile inside the folder and edit.
Base Image: nginx
Copy all the files to this path /usr/share/nginx/html
Expose the port 80

Here is a previem
https://preview.bootstrap.build/appwebsite/index.html

After you create the Dockerfile need to Build the image.

docker build -t [username_docker]/nginx_lesson:1.0 .

Then test the container if is working in the port 5000

docker run --name lesson_01 --rm -p 5000:80 [username]/nginx_lesson:1.0

Test the new URL is working and send to Skype Chat and email to Mateo Zeas.
