# simple-neo4j-py2neo
this repository belongs to my database class project's

In this project, I run neo4j with docker container.

>> docker run --publish=7474:7474 --publish=7687:7687 --volume=$HOME/data:/data neo4j

Since Docker is immutable infrastructure, please make sure you have <b>/data</b> under your home directory to save all your docker container data. Otherwise docker will wipe out all the data in the next run.
