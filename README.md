# Description:

A little project to setup a Jupyter Lab with some scientific libraries with Docker (from imakecodes repository)

# Installing:

To install docker, I recommend [This Tutorial](https://www.digitalocean.com/community/tutorials/como-instalar-e-usar-o-docker-no-ubuntu-18-04-pt) untill complete **Step 2**.

```
pip install docker-compose
```

# Building Environment:

To build the environment run this command in your terminal (on data-science-environment folder):
```
docker-compose up --build
```

This command will install all components specified in requirements.txt, and may take a while...

# Run Environment:

```
docker-compose up
```
