FROM almalinux:9
RUN dnf install nginx -y
RUN useradd chinna

USER chinna
CMD ["nginx","-g","daemon off;"]