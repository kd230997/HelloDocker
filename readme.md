## Installation

**Create Virtual Environment**
```
python3 -m venv .venv
```
**Activate Virtual Environment**
```
.venv/Scripts/activate
```
**Deactivate Virtual Environment**
```
deactivate
```
**Create an images**
```
docker build -t hellodocker .
```
**Create a container**
```
docker run -it --name hellodocker -p 5000:5000 hellodocker
```
**Create a container and kill when exit**
```
docker run -it --name hellodocker --rm -p 5000:5000 hellodocker
```
**Run container**
```
docker start hellodocker
```
**Kill container running**
```
docker kill hellodocker
```