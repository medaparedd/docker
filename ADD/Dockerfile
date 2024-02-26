FROM almalinux:8
RUN yum install nginx -y
ADD https://raw.githubusercontent.com/daws-76s/notes/master/session-01.txt /tmp/session-1.txt
ADD sample-1.tar /tmp/
CMD ["nginx","-g","daemon off;"]