# 1. Base Image
FROM nginx:alpine

# 2. INTENTIONAL ERROR: This command does not exist
#RUN install-magic-devops-tools --version 99.0

# 3. Application Code
COPY app/index.html /usr/share/nginx/html/index.html

EXPOSE 80
