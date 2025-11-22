FROM python:3.9.25-slim
WORKDIR /app
RUN pip install flask
COPY app.py .
RUN mkdir /data
EXPOSE 5001
ENTRYPOINT [ "python" ]
CMD ["app.py"]