docker build -t my-jupyter-image .


# From bash
docker run -d -p 8888:8888 -v "$(pwd):/home/jovyan/work" test

# From powershell
docker run -d -p 8888:8888 -v C:/Users/rfronteddu/Desktop/volatile/git/deep_learning/1:/home/jovyan/work test
