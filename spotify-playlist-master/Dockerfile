FROM python

MAINTAINER jcanavan

EXPOSE 8081
ENV PYTHONUNBUFFERED=1

CMD ["/env/bin/python", "-m", "bottle", "-s", "cherrypy", "-b", "0.0.0.0:8080", "--debug", "main"]
