https://hub.docker.com/r/crosscompass/ihaskell-notebook/dockerfile

PWB - current working directory

docker run --rm -p 8888:8888 -v $PWD:/home/jovyan/pwd --name ihaskell_notebook crosscompass/ihaskell-notebook:latest jupyter lab --LabApp.token=''