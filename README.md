# flocker
Flask + Docker standard template. This project shows how to run Flask in a Docker container.

I used Docker-Compose to create two containers. The first one will run the Flask application using the WSGI server gunicorn. The second container will run a nginx reverse proxy. It will serve all static files much faster than the WSGI server could do it. It's necessery to have Docker and Docker-Compose installed. Python version recommendation - 3.6+
