# hash
Toolkit for calculating hash-value of a file.

Currently under development. Only md5 supported at this time.

(Created as a mock application for https://devopswithdocker.com/ course)

## Requirements
Runs under most Linux distributions, requires sh-shell.

## Usage
Get the md5 hash of a file:
./hash <filename>

## Docker
Also available as a docker image at: https://hub.docker.com/repository/docker/igufi/hash

### Usage via Docker:
```bash
docker run -v $(pwd):/usr/src/app hash <filename in $pwd>
```
Example:
```bash
$ docker run -v $(pwd):/usr/src/app hash test
6f5902ac237024bdd0c176cb93063dc4  test
```
