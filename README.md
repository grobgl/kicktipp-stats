# Kicktipp Stats

Visualise distribution of football match result predictions on kicktipp.

To run:
``` bash
docker run --rm -p 8888:8888 -e EMAIL=<KICKTIPP_EMAIL> -e PASSWORD=<KICKTIPP_PASSWORD> -v "$PWD":/home/jovyan/work jupyter/datascience-notebook
```
