FROM python:3.11.1

# Set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN pip install --upgrade pip

# Expose port 8000
EXPOSE 8000

# Use gunicorn on port 8000
#CMD ["gunicorn", "--bind", ":8000", "--workers", "2", "airline.airline.wsgi"]

# CodeSandbox supports debian and ubuntu based images




RUN apt update && apt install -y python3 python3-pip


RUN apt update && apt install -y python3 python3-pip
