#Our image can be used by someone else, but we want to put some conditions to use our image.
#That can be enforced using ONBUILD instruction.

FROM almalinux:9
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
# This instruction runs when someone use this image
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]