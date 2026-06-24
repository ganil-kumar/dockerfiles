# Used to run the container, executed at the time of running the container.
# it will not execute at the time of building..
#we can have multiple RUN instructions inside dockerfile. but only one CMD instruction
FROM redhat/ubi9
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]