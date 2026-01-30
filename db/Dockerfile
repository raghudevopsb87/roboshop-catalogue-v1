FROM      redhat/ubi9
COPY      mongo.repo /etc/yum.repos.d/mongo.repo
RUN       dnf install mongodb-mongosh -y
COPY      master-data.js /
ENTRYPOINT  ["bash", "/run.sh"]


