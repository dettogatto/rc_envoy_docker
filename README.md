Edit envoy.yaml to set the ports and the server address (cluster address field).


To run docker run `docker compose up -d`

This will run envoy in a docker container, proxying HTTP1 traffic to port 8080 to port 9090 via HTTP2
