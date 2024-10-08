FROM ubuntu

WORKDIR /app

# Copy the requirements.txt file into the container
COPY requirements.txt /app/requirements.txt

# Copy the devops directory into the container
COPY devops /app/devops

# Install Python, pip, and venv
RUN apt-get update && \
    apt-get install -y python3 python3-pip python3-venv

# Set up virtual environment
RUN python3 -m venv /app/venv

# Activate virtual environment and install dependencies
RUN /app/venv/bin/pip install --upgrade pip && \
    /app/venv/bin/pip install -r /app/requirements.txt

# Ensure that the virtual environment is used
ENV PATH="/app/venv/bin:$PATH"

# Set entrypoint and run the application
ENTRYPOINT ["python3"]
CMD ["manage.py", "runserver", "0.0.0.0:8000"]





