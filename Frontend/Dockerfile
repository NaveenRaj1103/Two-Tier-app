# Use official Nginx image
FROM nginx:alpine

# Copy HTML into Nginx public directory
COPY index.html /usr/share/nginx/html/index.html

# Expose port
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
