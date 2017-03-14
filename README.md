# IngestingDroneData
Ingesting Drone Data into Big Data Platforms


# Notes

upsert into dronedata (datekey, inception, fileName, gPSAltitude, gPSLatitude, gPSLongitude, orientation,geolat,geolong) 
values ('${'date'}','${inception:escapeCsv()}','${'filename'}','${'GPS Altitude'}','${GPS Latitude:escapeCsv()}','${GPS Longitude:escapeCsv()}','${'Orientation'}', '${'geo:lat'}','${'geo:long'}')

# References

https://community.hortonworks.com/content/kbentry/72702/drones-uav-data-ingest-methods.html

https://community.hortonworks.com/articles/73355/adding-a-custom-processor-to-nifi-linkprocessor.html

https://github.com/tspannhw/DroneDataIngest

https://community.hortonworks.com/articles/58265/analyzing-images-in-hdf-20-using-tensorflow.html

https://community.hortonworks.com/articles/80339/iot-capturing-photos-and-analyzing-the-image-with.html

https://community.hortonworks.com/articles/59349/hdf-20-flow-for-ingesting-real-time-tweets-from-st.html

https://community.hortonworks.com/articles/76935/using-sentiment-analysis-and-nlp-tools-with-hdp-25.html

https://community.hortonworks.com/articles/83100/deep-learning-iot-workflows-with-raspberry-pi-mqtt.html

https://community.hortonworks.com/articles/77988/ingest-remote-camera-images-from-raspberry-pi-via.html


# Sections

1. Processing Images with TensorFlow for Image Recognition 

https://community.hortonworks.com/articles/83100/deep-learning-iot-workflows-with-raspberry-pi-mqtt.html
https://community.hortonworks.com/articles/77988/ingest-remote-camera-images-from-raspberry-pi-via.html

2. Processing Text with Various Sentiment Analysis frameworks 


https://github.com/tspannhw/nifi-corenlp-processor
https://github.com/tspannhw/nifi-nlp-processor
https://github.com/tspannhw/nlp-utilities
https://github.com/tspannhw/iot-scripts

3. Java 8 for analyzing HTML 
https://github.com/tspannhw/linkextractor
https://community.hortonworks.com/articles/60480/using-images-stored-in-hdfs-for-web-pages.html

4. Writing a Java 8 Microservice for retrieving Phoenix/Hbase data 
https://community.hortonworks.com/content/kbentry/56642/creating-a-spring-boot-java-8-microservice-to-read.html
https://community.hortonworks.com/content/repo/75498/apache-phoenix-hbase-spring-boot-microservices.html
https://github.com/tspannhw/phoenix
https://github.com/tspannhw/dronemap



5. Writing a Java 8 Microservice for retrieving Hive data 
https://community.hortonworks.com/articles/53629/writing-a-spring-boot-microservices-to-access-hive.html
https://github.com/tspannhw/hive



6. Writing a NiFi flow to wire it all together


https://github.com/tspannhw/nifi-extracttext-processor
https://github.com/tspannhw/linkextractorprocessor

4. Writing a Java 8 Microservice for retrieving Phoenix/Hbase data 
https://community.hortonworks.com/content/kbentry/56642/creating-a-spring-boot-java-8-microservice-to-read.html
https://community.hortonworks.com/content/repo/75498/apache-phoenix-hbase-spring-boot-microservices.html
https://github.com/tspannhw/phoenix
https://github.com/tspannhw/dronemap

5. Writing a Java 8 Microservice for retrieving Hive data 
https://community.hortonworks.com/articles/53629/writing-a-spring-boot-microservices-to-access-hive.html
https://github.com/tspannhw/hive

