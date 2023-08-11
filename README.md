# graphhopper
graphhopper docker compose  

for use this service:
1-you need to necessary resource.
2- down load the osm.pbf map file from https://download.geofabrik.de/ 
3- create a directory with map name and copy osm.pbf map file inside it.
4- change map name in command of docker-compose 
  command: -c " java -Ddw.graphhopper.datareader.file=/data/iran-latest.osm.pbf -Ddw.graphhopper.graph.location=iran-gh -jar *.jar  server config-example.yml"
5- docker compose up -d 

enjoy it
