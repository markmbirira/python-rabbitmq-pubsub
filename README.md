# Using RabbitMQ with Python

> This example uses [pika RabbitMQ client](https://github.com/pika/pika)

## Installation

Install RabbitMQ: Ubuntu/Debians-based OS's:

```
$ sudo apt-get install rabbitmq-server
```

Install RabbitMQ's Python Client:

```
$ pip install -r requirements.txt
```

## Run producer

Open the project in your terminal and run your `publish` Producer with:

```
$ python publish.py
```

To produce multiple (e.g 20) to the queue messages you can use this convenience `$bash one-liner`:
```
$ for i in {1...20}; do python publish.py; done
```


## Run consumer
 
Open another tab/terminal and run your `notify` Consumer with:

```
$ python notify.py
```

## Run producer

Open another tab/terminal and run yout `report` Consumer with:
```
$ python report.py
```

> Find more docs at [pika's documentation](https://pika.readthedocs.io/en/stable/index.html)
