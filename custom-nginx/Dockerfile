<<<<<<< HEAD
# Use Python as the base image
FROM python:3.10-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the Python script into the container
COPY calculator.py /app/

# Install any dependencies (if needed)
# Using RUN to demonstrate execution at build time
RUN echo "Building the Docker image and setting up the environment..."

# Use ENTRYPOINT to ensure the script is always run with Python
ENTRYPOINT ["python", "calculator.py"]

# Set a default CMD for the container
CMD ["add", "10", "20"]
=======
FROM nginx
COPY index.html /usr/share/nginx/html/index.html
>>>>>>> 12513370407538c4b782e3a2ee5098719f0e2d37
