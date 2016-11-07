# grafana_dashboards
Collection of Grafana dashboards

## Usage

Clone the repo and then log into Grafana. Click the orange swirl in the upper left corner and then choose Dashboards. Now select Import and then upload file.

You will need to change the names used in the query to whatever matches your infrastructure.

Click any chart or dial and choose edit. Now select Metrics and look at the
query line, which will usually start with A.

See https://kodywilson.com/2016/11/07/infrastructure-metrics-with-grafana-and-influxdb/ for more information.

You will want to change "array" = 'something' to your array name.
