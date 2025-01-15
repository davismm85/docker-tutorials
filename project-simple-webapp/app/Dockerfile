FROM python:latest

# Copy the requirements
COPY requirements.txt requirements.txt

# install app dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the application code into the container
COPY . app.py

# final configuration
ENV FLASK_APP=app
EXPOSE 5000
CMD ["flask", "run", "--host", "0.0.0.0", "--port", "5000"]
