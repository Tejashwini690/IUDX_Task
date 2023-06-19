# Use the official Python base image
FROM python:3.9

# Set the working directory in the container
WORKDIR /app

# Copy the requirements file to the container
COPY requirements.txt .

# Install the Python dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the rest of the application code to the container
COPY . .

# Set the Flask app's environment variable
ENV FLASK_APP=app.py

# Expose the Flask app's port
EXPOSE 5000

# Start the Flask app
CMD ["flask", "run", "--host=0.0.0.0"]
