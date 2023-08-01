# Install & setup jupyter notebook

> Run the below command to spin up jupyter notebook docker container

`docker run -p 8888:8888 -v $(pwd):/home/ubuntu/work jupyter/tensorflow-notebook`

> Check the log file for the login url, seen with a token (example below)

http://2780170dc919:8888/lab?token=f8cf2824f472601bc0c4617cafe7ce908e68dae7bc286df9


_your current dir from where you started this container will be volume mounted to the /home/ubuntu/work folder inside the container, so all your path should be relative to this path_
