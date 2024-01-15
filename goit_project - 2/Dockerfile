FROM python

WORKDIR /app

COPY . /app

RUN pip install -r requirements.txt

EXPOSE 5000

ENV NAME Bot



ENTRYPOINT [ "python", "main.py" ]

