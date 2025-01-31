# dsci-310-tutorial-4

`docker run --rm -e PASSWORD="pizza" -p 8787:8787 rocker/rstudio:4.4.2` 
- `--rm`: Makes the container delete itself upon exiting the container.
- `-e PASSWORD="pizza"`: Set the environment variable PASSWORD="pizza"
- `-p 8787:8787`: Specifies the ports to map a web app to; maps with local host 8787 and Docker host 8787.
