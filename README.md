# cytoscape

A demo app for X2.

```bash
$ git clone https://github.com/g2glab/cytoscape
$ cd cytoscape
$ docker-compose up
$ docker-compose exec neo4j bash /neo4j/neo4j_init.sh
# Wait until the script finishes.
```

Access to http://localhost:8080/

If neo4j container does not work well, please try `chown` for `neo4j/logs` folder.
