Project Maverick Website using Ghost
=================================

## Development Setup
1. Install Docker, using [this link](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
2. Run the following command to pull the Ghost docker image
```txt
docker pull ghost
```
3. Run the following command, replacing the path to the folder as required:
```txt
docker run -p 2368:2368 -v [PATH_TO_FOLDER]/ghost/content:/var/lib/ghost/content ghost
```
Example:
```txt
docker run -p 8080:2368 -v /home/alex/Documents/websites/pmaverick.com/ghost/content:/var/lib/ghost/content ghost
```
