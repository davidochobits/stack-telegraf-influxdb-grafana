# stack-telegraf-influxdb-grafana
Stack for Docker with Telegraf, Influxdb and Grafana

This stack is an adaptation of the one shown in this entry: https://wmartins.github.io/2017/10/creating-a-monitoring-stack-with-docker-swarm-grafana-influxdb-and-telegraf/ Thanks in advance to William Martins for his work

<h3>Previous requirements</h3>

The stack has been tested in a Stack with three nodes, a manager and two worker, using Docker Swarm. 

One of the workers must have added the tag "grafana = true", and the other "influxdb = true"

In addition, previously we have to create the network overlay "metrics"
