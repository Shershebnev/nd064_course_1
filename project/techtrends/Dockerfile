FROM python:3.8
EXPOSE 3111
COPY . .
RUN pip install -r requirements.txt
RUN python init_db.py
CMD python app.py
