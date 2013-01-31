Nanoko
======


Updating all projects
---------------------

    git submodule foreach git pull

Compiling
---------

	mvn clean install

Be aware that optipng and jpegtrans are required by tests. Skip tests with:

	mvn clean install -DskipTests

	