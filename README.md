# simple-kafka

A simple example of a kafka producer and consumer

## Docker-compose

### Initialize

```bash
docker-compose up -d
```

### checking services

```bash
docker-compose ps
```

## Producer

```bash
cd producer
pip install -r requirements.txt
python3 producer.py
```

## Consumers

```bash
cd consumer
npm install
node consumer_avg.js
node consumer_sum.js
```
