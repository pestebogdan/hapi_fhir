# Running HAPI FHIR & associated PostgreSQL DB with docker-compose

## Instructions

1. Clone this repository
2. Make sure you have docker and docker-compose' for docker-compose, make sure you have a newer version that knows how to work with configs: (e.g: v2.16.0); see startup.sh script to automatically configure an Ubuntu machine for this
3. Create a persistent-volume with 2 subfolders: web/ and /db/ ; this is where persistent data will be stored for the 2 containers so that in the event of a restart, no data will be lost.
3. docker-compose up -d
