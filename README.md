# Vicmooc@v0.2.0 

(based on [vismooc-data-server@v0.3.0](https://github.com/HKUST-VISLab/vismooc-data-server/releases/tag/v0.3.0) and [vismooc-web-server@v0.3.0](https://github.com/HKUST-VISLab/vismooc-web-server/releases/tag/v0.3.0)).

## Requirement:

### OS
OS: Debian 8 (amd64)

### Software
- Docker

### Hardware
- CPU: Intel core i5-6500 @3.20GHz， 4 cores
- RAM: 8G
- Disk: Hard disk, >= 100Gb (actually, it depends on the size of dbsnapshot)

## Installation

### Docker
1. install Docker and Docker-compose

### vismooc
1. Build the images and run the container `sudo docker-compose up -d`