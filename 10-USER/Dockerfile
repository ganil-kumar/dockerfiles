#to mention the user that container should be running on
FROM almalinux:9
RUN dnf install nginx -y
# root access required to create user or install packages
RUN useradd roboshop

USER roboshop
#CMD [ "nginx", "-g", "daemon off;" ]
CMD [ "sleep","100" ]