# Use the Alpine image
FROM alpine:latest

# Install Nginx using the apk package manager
RUN apk update && apk add nginx

# Set the command to run nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
