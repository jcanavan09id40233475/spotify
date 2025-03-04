FROM python:3.4

MAINTAINER jcanavan

EXPOSE 8081
ENV PYTHONUNBUFFERED=1

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

CMD ["/env/bin/python", "-m", "bottle", "-s", "cherrypy", "-b", "0.0.0.0:8081", "--debug", "main"]
