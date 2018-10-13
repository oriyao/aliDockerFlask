# aliDockerFlask

## From ALI Docker Test

2018/10/13 git 

docker build -t oriyaoflaskimage .

docker run -d --name OriyaoFlask -p 80:80 -v /home/Flask/app:/app --privileged=true -e FLASK_APP=main.py -e FLASK_DEBUG=1 oriyaoflaskimage flask run --host=0.0.0.0 --port=80




