# Composer With php 7.4

You can build with below code:

    docker build -t <your docker hub's username>/<tag> .

After build it, you can use it like below:

    docker run --rm -it -volume $PWD:/app:z <your docker hub's username>/<tag> composer install <Package name>

OR

    docker run --rm -it -volume $PWD:/app:z <your docker hub's username>/<tag> composer remove <Package name>
OR

    docker run --rm -it -volume $PWD:/app:z <your docker hub's username>/<tag> composer update