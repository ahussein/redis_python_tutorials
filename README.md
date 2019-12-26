## Redis Python Tutorials
Full tutorial can be found [here](https://realpython.com/python-redis/)

### Working box
An ubuntu latest docker images was used (18.04 at the time)
```shell
docker run -it --rm `pwd`/redis_python_tutorials:/opt/code ubuntu
```

**Update metadata and install curl and build tools**
``` shell
apt update
apt install -y curl build-essential python3 python3-pip
```

**Link pyhton3 to python binary**
```shell
ln -s /usr/bin/python3 /usr/bin/python
```