# Learn Jenkins! Complete Jenkins Course - Zero to Hero - Notes

## Docker

### Build doker image

Basic command

```bash
docker build .
```

Build docker image with tag name

```bash
docker build -t [tagName] .
```

Example:

```bash
docker build -t python-agent
```

### Upload image to Docker Hub

Repository must exists and should be avaliable

```bash
docker tag [imageTagName] [repositoryUrl]:[repositoryTagName]
```

Example:

```bash
docker tag python-agent ferlopezcarr/devopsjourney1-jenkins-101:python-agent
```

## Utils

Command to access jenkins console

```bash
docker exec -it [containerName] bash
```

Example:

```bash
docker exec -it jenkins-blueocean bash
```
