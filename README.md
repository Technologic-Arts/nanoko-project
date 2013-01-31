Nanoko
======

Getting everything
------------------

	git clone git@github.com:nanoko-project/nanoko-project.git
	cd nanoko-project
	git submodule init
	git submodule update
	git submodule sync

Updating all projects to get latest versions
--------------------------------------------

    git submodule foreach git pull

Compiling
---------

	mvn clean install

Be aware that optipng and jpegtrans are required by tests. Skip tests with:

	mvn clean install -DskipTests

