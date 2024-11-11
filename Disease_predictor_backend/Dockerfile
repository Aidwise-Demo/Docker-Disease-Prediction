# Use Python 3.9 image as base
FROM python:3.9

# Set the working directory in the container
WORKDIR /app
RUN apt-get update && apt-get install -y libgl1

# Copy the requirements file into the container
COPY requirements.txt .

# Install the dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the rest of the application code into the container
COPY . .

# Expose the port that Uvicorn will run on
EXPOSE 8000

# Set the command to run the application with Uvicorn
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000", "--reload"]
