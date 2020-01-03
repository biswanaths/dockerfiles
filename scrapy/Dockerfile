FROM python:buster

LABEL org.opencontainers.image.authors="biswanath" \
      org.opencontainers.image.description="Docker image for scrapy"


RUN python -m pip install --upgrade scrapy

RUN python -m pip install --upgrade ipython 

# CMD ["scrapy", "shell", "--nolog"]

CMD ["bash"]


