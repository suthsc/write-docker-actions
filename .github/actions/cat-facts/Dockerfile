FROM python:3

COPY requirements.txt ./

RUN pip install --no-cache-dir -r requiements.txt

COPY . .

CMD [ "python", "/src/main.py" ]
