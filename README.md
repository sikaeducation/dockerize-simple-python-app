## Dockerize Simple Python App

Write a Dockerfile to run the script in the `/src` directory. It should:

* Use a light operating system with Python 3.11 installed
* Install all the dependencies in `src/requirements.txt` with `pip install -r requirements.txt`
* Start with `python app.py`

Compile it with `docker build -t helloworld:latest .`, and then run it with `docker run helloworld`. If done correctly, you should see "Hello, world!" printed to the screen along with a timestamp.
