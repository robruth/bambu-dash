# bambu-dash 

## Description

Simple BambuLabs Grafana dashboard using [mqtt-exporter](https://github.com/kpetremann/mqtt-exporter), [Prometheus](https://hub.docker.com/r/prom/prometheus) and [Grafana](https://hub.docker.com/r/grafana/grafana/)  

### Configuration

The minimum configuration required is to set IP, password and topic:

  * `MQTT_ADDRESS`: IP or hostname of BambuLabs printer 
  * `MQTT_TOPIC`: device/<your printers serial>/repo 
  * `MQTT_PASSWORD`: Access Code found in Settings -> Network 

Your serial number can be found by connecting to MQTT via desktop client such as [MQTT Explorer](http://mqtt-explorer.com) 

### Deployment

docker-compose up -d
