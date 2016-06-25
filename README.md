# Simple web mapping application from scratch by using geoserver
* sample dataset includes 1132877 location-based twitters, download from this link: https://www.dropbox.com/s/xz4ymg5t5fdbu7z/tweets.tsv?dl=0 
* read the "instruction.txt" file to know how to COPY the tsv file into PostgreSQL, how to generate geometry, and how to publish data from GeoServer

1. Install geoserver, PostgreSQL/PostGIS
2. Go to your "GeoServer/data_dir/www" directory
3. You can serve html files in GeoServer by placing them in the www subdirectory in your GeoServer's data directory
4. Create a folder for your project, and put your files in this folder
5. Let's start...
6. Publish your data: log in geoserver (localhost:8080/geoserver), and import data from PostGIS
7. Put the sample files in the folder
8. Finally, you can access your application --- localhost:8080/geoserver/www/[project folder]/index.html

