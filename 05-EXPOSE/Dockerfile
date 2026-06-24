#Expose useful to display the port information of container. 
#it will not really open the port but provides information only to the users
FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80
CMD [ "nginx", "-g", "daemon off;" ]
