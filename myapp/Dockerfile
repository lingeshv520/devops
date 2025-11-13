# Use Nginx to serve static files
FROM nginx:alpine

# Set working directory in Nginx
WORKDIR /usr/share/nginx/html

# Copy all project files into Nginx web directory
COPY . .

# Expose port 80 (Nginx default)
EXPOSE 80

# Run Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
