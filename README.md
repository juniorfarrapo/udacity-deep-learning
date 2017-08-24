Assignments for Udacity Deep Learning class with TensorFlow
===========================================================

Course information can be found at https://www.udacity.com/course/deep-learning--ud730

Running the Docker container from the Google Cloud repository
-------------------------------------------------------------

    docker run -p 8888:8888 --name tensorflow-udacity -it gcr.io/tensorflow/udacity-assignments:1.0.0

Note that if you ever exit the container, you can return to it using:

    docker start -ai tensorflow-udacity

Accessing the Notebooks
-----------------------

On linux, go to: http://127.0.0.1:8888

On mac, find the virtual machine's IP using:

    docker-machine ip default

Then go to: http://IP:8888 (likely http://192.168.99.100:8888)
