FROM python:3

WORKDIR /usr/src/app
COPY requirements.txt ./

RUN pip install no-cashe-dir --upgrade -r ./requirements.txt

EXPOSE 3001

CMD [ "python3" "./src/server.py" ]