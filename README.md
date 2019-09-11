# flightmission-map
Shiny webapp which creates a map and pulls additional data from ODK Aggregate (https://docs.opendatakit.org/aggregate-intro/) server.

Preview for the final map:
```
https://flighmission-map.azurewebsites.net/
```
You can pull the docker container from:
```
docker pull jugglingchef/flighmission-map
```
And run it using:
```
sudo docker run -p 80:80 jugglingchef/flighmission-map 
```
