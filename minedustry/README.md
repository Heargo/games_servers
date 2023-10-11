# setup
download server.jar from itch.io and copy in root directory.

Then execute the following commands
```bash
docker compose up -d
docker compose exec minedustryServer bash
java -jar server.jar
```

# lancer le serveur minedustry

### Host une map :
Open the server. Will default to survival and a random map if not specified.
```bash
host [mapname] [mode]
```

### Host a save :
Load a save from a slot.
```bash
load <slot>
```

list all slots : 

```bash
saves
```

### close server

```bash
stop
exit
```

```bash
docker compose down
```



