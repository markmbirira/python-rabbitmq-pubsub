# Using RabbitMQ with Python

> This example uses [https://github.com/pika/pika](Pika RabbitMQ client)

## Installation

Install RabbitMQ: Ubuntu/Debians-based OS's:

```
sudo apt-get install rabbitmq-server
```

Install RabbitMQ's Python Client:

```
pip install -r requirements.txt
```

## Run producer

Open the project in your terminal and run your `producer` Producer with:

```
python producer.py
```

## Run consumer
 
Open another tab/terminal and run your `notify` Consumer with:

```
python notify.py
```

## Run producer

Open another tab/terminal and run yout `report` Consumer with:
```
python report.py
```

Find more docs at [https://pika.readthedocs.io/en/stable/index.html](pika's documentation)