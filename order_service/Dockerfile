FROM python
WORKDIR /app
COPY ../requirements.txt .
RUN pip install -r requirements.txt
COPY order_service/ .
CMD ["python", "order_app.py"]
EXPOSE 8083

