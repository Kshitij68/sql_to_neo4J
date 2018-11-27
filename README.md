# sql_to_neo4J
An example on how to create a Neo4J database from existing SQL dataset

The dataset used can be found [here](https://www.kaggle.com/hugomathien/soccer)
You can download Docker container for Neo4J using `docker pull neo4j`.
Then do `docker run     --publish=7474:7474 --publish=7687:7687     --volume=$HOME/neo4j/data:/data     neo4j` to run the docker container

Please make sure docker is installed in your machine.


Visit [this link](https://hub.docker.com/_/neo4j/) for more information

### Some resources to learn Cypher Queries
- [link](https://gist.github.com/DaniSancas/1d5265fc159a95ff457b940fc5046887)

- [link](https://learnxinyminutes.com/docs/cypher/)
