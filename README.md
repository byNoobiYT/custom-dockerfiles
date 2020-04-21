# Custom Dockerfiles
> This repository contains custom Dockerfiles which are adjusted for my purpose by me

## Dockerfiles

### How to build the Dockerfiles:
* Clone the repository:
```sh
git clone https://github.com/byNoobiYT/custom-dockerfiles.git
```
* Build Dockerfiles: 
```sh
docker build -t <tag> -f <dockerfile> .
```
> Replace
> ```
> <tag> with the name of the image
> ```
> and
> ```
> <dockerfile> with the file name of the Dockerfile you want to build
> ```
* Use Docker image:
```dockerfile
FROM <tag>

# Your Dockerfile instructions

CMD [ "your", "start", "up", "command" ]
```
> Replace ```<tag> with the name of your image you built in the previous step```

### JDK files
* [`maven-3.6.3-alpine`](https://github.com/byNoobiYT/custom-dockerfiles/blob/master/maven-3.6.3-alpine) - Docker [OpenJDK](https://github.com/docker-library/openjdk) image based on [Alpine linux](https://github.com/alpinelinux/docker-alpine) with [Maven](https://maven.apache.org/) | Updated version of [Zenika/alpine-maven](https://github.com/Zenika/alpine-maven) (Licensed under the terms of [MIT License](https://mit-license.org/))