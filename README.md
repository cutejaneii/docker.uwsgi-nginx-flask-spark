## docker.uwsgi-nginx-flask-spark ##

Base on  **[tiangolo/uwsgi-nginx:python2.7](https://github.com/tiangolo/uwsgi-nginx-docker)**, we also installed following software into container for use.

- uwsgi
- nginx
- flask
- spark
- pandas
- cassandra

## Comparison between my repository ##

To find the fittest repository by the following image.


![](git-repository-comparison2.png)

Go to [cutejaneii/docker.uwsgi-nginx-flask-spark](https://github.com/cutejaneii/docker.uwsgi-nginx-flask-spark)

Go to [cutejaneii/spark-streaming-kafka-to-cassandra](https://github.com/cutejaneii/spark-streaming-kafka-to-cassandra)

Go to [cutejaneii/docker.nginx-cassandra-spark-emperor](https://github.com/cutejaneii/docker.nginx-cassandra-spark-emperor)

Go to [cutejaneii/docker.uwsgi-nginx-flask-emperor](https://github.com/cutejaneii/docker.uwsgi-nginx-flask-emperor)

### Usage ###

To run it:

> docker run -d -p 8899:80 --name api -v {folder}:/app cutejaneii/docker.uwsgi.nginx-flask-spark

### Important! ###

DO NOT FORGET TO MAP HOST FOLDER WHEN BUILD A CONTAINER, SINCE THIS IMAGE DO NOT HAVE ANY API CODE IN
IT.

