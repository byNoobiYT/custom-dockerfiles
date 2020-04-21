# Custom Dockerfiles
> This repository contains custom Dockerfiles which are adjusted for my purpose by me

## Dockerfiles

### How to build the Dockerfiles:
* Clone the repository:
```sh
git clone https://github.com/byNoobiYT/custom-dockerfiles.git
```
* `cd` into directory of Dockerfile
* Build Dockerfiles: 
```sh
docker build -t <tag> .
```
> Replace `<tag> with the name of the image`
* Use Docker image:
```dockerfile
FROM <tag>

# Your Dockerfile instructions

CMD [ "your", "start", "up", "command" ]
```
> Replace `<tag> with the name of your image you built in the previous step`

### JDK files
* [`maven-3.6.3-alpine`](https://github.com/byNoobiYT/custom-dockerfiles/blob/master/maven-alpine)
