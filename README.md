# test_script

foobar

build:
docker build -t pythonimage .

run:
docker run --entrypoint="python" pythonimage "/home/main.py"
