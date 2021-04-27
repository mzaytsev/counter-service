# docker build -t cp-docker .
# docker run --rm -it --name cp-docker -p 8090:80 cp-docker

FROM python:latest
RUN pip3 install flask
COPY counter-service.py /
EXPOSE 80
CMD ["python3", "/counter-service.py"]