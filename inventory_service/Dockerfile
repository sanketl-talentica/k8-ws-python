FROM python
WORKDIR /app
COPY ../requirements.txt .
RUN pip install -r requirements.txt
COPY inventory_service/ .
CMD ["python", "inventory_app.py"]
EXPOSE 8082

