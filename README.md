# Shiny Server
[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/1320)

Shiny Server Version: 1.5.9.923
R Version: 3.5.1

Singularity container for Shiny Server.

Run a Shiny app:
```
$ singularity pull --name shiny.simg shub://mcw-rcc/shiny-server:1.5.9.923
$ singularity run shiny.simg app.R
```
The run command will display a URL. Open a browser and enter the URL to interact with the app.
