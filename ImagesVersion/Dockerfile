# Use a base image with Python installed
FROM python:3.9-slim

# Set the working directory
WORKDIR /app

# Copy the HTML file into the container
COPY index.html .

# Expose port 80 for the web server
EXPOSE 80

# Start a simple Python HTTP server
CMD ["python", "-m", "http.server", "80"]

